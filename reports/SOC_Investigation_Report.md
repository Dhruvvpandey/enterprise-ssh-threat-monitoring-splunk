SOC Investigation Report

Incident Summary

Analysis of Linux SSH authentication logs identified indicators of brute-force attacks, reconnaissance scanning, and unauthorized authentication attempts.

⸻

Investigation Scope

Data Source:

* Linux SSH Authentication Logs

Monitoring Platform:

* Splunk Enterprise SIEM

⸻

Timeline of Activity

Phase 1 – Reconnaissance

Evidence of network scanning and service discovery activity.

Indicators:

* Nmap scanning signatures
* Service enumeration attempts

⸻

Phase 2 – Credential Attacks

Repeated authentication failures targeting SSH services.

Indicators:

* High-volume failed logins
* Repeated username targeting

⸻

Phase 3 – Access Attempts

Authentication attempts against privileged and commonly used accounts.

Examples:

* root
* admin
* ubuntu

⸻

Indicators of Compromise

Attacker Behavior

* Brute-force authentication attempts
* Service discovery
* Repeated login failures

Targeted Services

* SSH (Port 22)

⸻

Security Findings

Finding	Severity
SSH Brute Force Activity	Critical
Reconnaissance Activity	High
Unauthorized Login Attempts	High

⸻

Containment Recommendations

1. Block malicious source IP addresses
2. Enable MFA
3. Disable direct root login
4. Deploy Fail2Ban
5. Strengthen password policies

⸻

Investigation Conclusion

Observed activity is consistent with external threat actors attempting reconnaissance and credential-based attacks against exposed SSH services.

Overall Severity:

HIGH