# 🚨 Incident Report – SIEM Alert Investigation

## Incident Details
- Incident ID: IR-SIEM-001
- Incident Type: Suspicious Authentication Activity
- Severity: Medium
- Status: Closed
- Analyst: Archana Malviya

---

## Executive Summary
A SIEM alert was triggered due to multiple failed authentication attempts from a single external IP address. The alert was investigated using Splunk search queries. No successful compromise was identified.

---

## Detection
- Detection Source: Splunk SIEM
- Alert Type: Multiple Failed Login Attempts

---

## Investigation Summary
- Reviewed alert metadata
- Analyzed authentication logs
- Identified repeated failures from same IP
- No successful login observed

---

## Indicators of Compromise (IOCs)
- Source IP: `<Suspicious_IP>`
- Target Service: Authentication Service

---

## Impact Assessment
- System Compromised: No
- Data Loss: No

---

## Response Actions
- Alert validated and closed
- IP recommended for monitoring/blocking

---

## MITRE ATT&CK Mapping
- **Tactic:** Credential Access
- **Technique:** Brute Force – Password Guessing
- **Technique ID:** T1110.001
---
## Lessons Learned
- SIEM alerts help detect early attack attempts
- Correlation rules reduce investigation time
