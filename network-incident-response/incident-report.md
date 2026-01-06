# 🚨 Incident Report – Network Traffic Anomaly

## Incident Details
- Incident ID: IR-NET-001
- Severity: Medium
- Analyst: Archana Malviya

---

## Summary
Suspicious network traffic was detected indicating possible scanning or reconnaissance activity.

---

## Detection
- Tool: Wireshark / tcpdump
- Method: Packet capture analysis

---

## Investigation
- Repeated packets from same source
- Multiple ports targeted

---

## IOCs
- Source IP: `<Suspicious_IP>`
- Protocols: ICMP / TCP

---

## Impact
- No service disruption
- No data exfiltration

---

## Response
- Traffic documented
- IP flagged for monitoring

---

## MITRE ATT&CK Mapping
- **Tactic:** Reconnaissance
- **Technique:** Network Service Scanning
- **Technique ID:** T1046

---

## Lessons Learned
- Network monitoring detects early-stage attacks
