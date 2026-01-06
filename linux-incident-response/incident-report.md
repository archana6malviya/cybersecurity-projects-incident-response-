# 🚨 Incident Report – SSH Brute-Force Attack

## Incident Details
- Incident ID: IR-LINUX-001
- Severity: Medium
- Analyst: Archana Malviya

---

## Summary
Multiple failed SSH login attempts were detected from an external IP address indicating a brute-force attack.

---

## Detection Source
- Linux Authentication Logs (`/var/log/auth.log`)

---

## Investigation
- Repeated failed password attempts
- Same IP targeting multiple users
- No successful login found

---

## IOCs
- Source IP: `<Malicious_IP>`
- Port: 22 (SSH)

---

## Impact
- No compromise
- No data loss

---

## Response
- IP blocked using firewall
- Monitoring continued

---

## Lessons Learned
- SSH should be hardened
- Brute-force attempts are common
