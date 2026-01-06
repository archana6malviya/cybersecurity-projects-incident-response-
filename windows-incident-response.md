# 🚨 Incident Report – Windows Failed Logon Attempts

## Incident Details
- Incident ID: IR-WIN-001
- Severity: Medium
- Analyst: Archana Malviya

---

## Summary
Multiple failed Windows logon attempts were detected indicating a possible brute-force or credential misuse attempt.

---

## Detection Source
- Windows Event Viewer
- Event ID: 4625 (Failed Logon)

---

## Investigation
- Multiple failures from same source
- No successful authentication found

---

## IOCs
- Username attempts
- Logon failure events

---

## Impact
- No account compromise
- No data loss

---

## Response
- Event documented
- Account monitoring enabled

---

## Lessons Learned
- Failed logon events are critical indicators
- Account lockout policies are important
