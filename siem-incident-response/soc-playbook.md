# 📘 SOC Playbook – Authentication Abuse (SIEM)

## Trigger Conditions
- Multiple failed logins from same IP
- SIEM alert triggered

## Investigation Steps
1. Review alert details
2. Identify source IP
3. Check for successful login

## Response
- Block IP if required
- Escalate if successful login detected

## Closure
- Close incident if no compromise detected
