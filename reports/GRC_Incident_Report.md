# GRC Incident Report

## Incident Summary

A brute-force SSH attack was detected through Splunk SIEM analysis.

Severity: High

Status: Investigated

## Findings

- Excessive failed login attempts
- Multiple attacker source IPs
- Automated attack behavior

## MITRE ATT&CK

T1110 - Brute Force

## Risk Rating

High

## Recommendations

- Enable MFA
- Restrict SSH access
- Configure account lockout policies
- Monitor authentication logs continuously


