# 🚨 Incident Report – Linux SSH Brute-Force Attack

## Incident Details
- Incident ID: IR-LINUX-001
- Severity: Medium
- Analyst: Archana Malviya

---

## Summary
Multiple failed SSH login attempts were detected from an external IP, indicating a brute-force attack attempt.

---

## Detection Source
- Linux Authentication Logs (`/var/log/auth.log`)

---

## Investigation
- Repeated failed login attempts
- Same IP targeting multiple usernames
- No successful login detected

---

## IOCs
- Source IP: `<Malicious_IP>`
- Port: 22 (SSH)

---

## Impact
- No system compromise
- No data loss

---

## Response
- Malicious IP blocked using firewall

---

## MITRE ATT&CK Mapping
- **Tactic:** Credential Access
- **Technique:** Brute Force
- **Technique ID:** T1110
- **Sub-technique:** Password Guessing (T1110.001)

---

## Lessons Learned
- SSH hardening is required
- Brute-force attempts are common
