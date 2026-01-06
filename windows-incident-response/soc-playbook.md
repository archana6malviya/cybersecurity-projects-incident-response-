# 🛡️ SOC Playbook – Windows Brute-Force Detection

## Trigger Conditions
- Multiple Event ID 4625 failures

## Investigation
- Review failed logon events
- Identify affected users

## Response
- Monitor or lock accounts
- Escalate if successful login occurs

## MITRE ATT&CK Mapping
- Credential Access – Brute Force (T1110.001)

## Closure
- No further failed attempts
