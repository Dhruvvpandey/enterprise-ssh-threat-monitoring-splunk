Executive Summary

Project Overview

This project demonstrates enterprise threat detection and security monitoring using Splunk SIEM through the analysis of Linux SSH authentication logs.

The objective was to identify brute-force attacks, reconnaissance activity, unauthorized access attempts, and suspicious authentication behavior.

⸻

Security Event Statistics

Metric	Value
Total Events Analyzed	28,572
Authentication Failures	20,204
Successful Logins	1,196
Reconnaissance Events	7,004

⸻

Threat Landscape

Analysis identified multiple attack patterns targeting SSH services.

Detected Activities

* SSH Brute Force Attacks
* Nmap Reconnaissance Scanning
* Unauthorized Login Attempts
* Credential Guessing Activity
* High Volume Authentication Failures

⸻

Business Impact Assessment

If successful, the observed attack activity could result in:

* Unauthorized Access
* Credential Compromise
* Privilege Escalation
* Lateral Movement
* Service Availability Risks

⸻

Overall Risk Rating

HIGH

⸻

Strategic Recommendations

1. Enable Multi-Factor Authentication (MFA)
2. Disable direct root SSH access
3. Implement account lockout controls
4. Restrict SSH access by source network
5. Continuously monitor authentication events
6. Deploy SIEM alerting for brute-force activity
7. Regularly review authentication logs