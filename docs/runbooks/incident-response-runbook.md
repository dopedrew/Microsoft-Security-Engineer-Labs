# Incident Response Runbook (Lab)

## Scope
This runbook documents the lab incident process from detection to closure.

## Workflow
1. **Triage**
   - Confirm signal quality
   - Identify impacted user/device/resource
2. **Scope**
   - Determine blast radius (identities, endpoints, mailboxes, cloud resources)
3. **Contain**
   - Isolate device, disable account, revoke sessions, block indicators
4. **Eradicate**
   - Remove persistence, remediate vulnerable configs, reset creds
5. **Recover**
   - Restore access/services safely and validate controls
6. **Lessons Learned**
   - Detection tuning, prevention hardening, documentation updates

## Evidence checklist
- Timeline screenshots
- KQL queries used
- Alert rule name/config
- Response actions executed
- Final summary + root cause
