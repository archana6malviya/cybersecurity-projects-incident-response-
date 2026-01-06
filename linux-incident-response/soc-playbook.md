# 🛡️ SOC Playbook – Linux SSH Brute-Force

## Trigger Conditions
- >5 failed SSH logins from same IP

## Investigation
- Review auth logs
- Identify source IP
- Check for successful logins

## Response
- Block IP
- Harden SSH configuration

## MITRE ATT&CK Mapping
- Credential Access – Brute Force (T1110.001)

## Closure
- No activity for 24 hours
