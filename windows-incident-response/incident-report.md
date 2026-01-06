# 🚨 Incident Report – Windows Failed Logon Attempts

## Incident Details
- Incident ID: IR-WIN-001
- Severity: Medium
- Analyst: Archana Malviya

---

## Summary
Multiple failed Windows logon attempts were detected indicating possible credential abuse.

---

## Detection Source
- Windows Event Viewer
- Event ID: 4625

---

## Investigation
- Repeated failures
- Same user accounts targeted
- No successful login

---

## IOCs
- Usernames
- Logon failure events

---

## Impact
- No account compromise

---

## Response
- Accounts monitored
- Events documented

---

## MITRE ATT&CK Mapping
- **Tactic:** Credential Access
- **Technique:** Brute Force
- **Technique ID:** T1110
- **Sub-technique:** Password Guessing (T1110.001)

---

## Lessons Learned
- Account lockout policies are important
