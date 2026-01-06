# 🚨 Incident Report – Network Traffic Anomaly

## Incident Details
- Incident ID: IR-NET-001
- Severity: Medium
- Analyst: Archana Malviya

---

## Summary
Suspicious network traffic was identified during packet capture analysis indicating possible scanning activity.

---

## Detection
- Tool: Wireshark / tcpdump
- Detection Method: Manual PCAP analysis

---

## Investigation
- Repeated ICMP/TCP packets
- Same source IP contacting multiple ports

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
- Source IP flagged for monitoring

---

## Lessons Learned
- Network traffic analysis helps detect early reconnaissance
