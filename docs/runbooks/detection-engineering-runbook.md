# Detection Engineering Runbook (Lab)

## Goals
- Build detections that are actionable, low-noise, and mapped to MITRE
- Document assumptions and tuning decisions
- Validate using test scenarios

## Standard process
1. Identify technique + data sources
2. Build a hunting query (KQL)
3. Convert to analytic rule (scheduled or NRT)
4. Add context enrichment (joins, entity mapping)
5. Test and tune (false positives / thresholds)
6. Document version history + coverage gaps

## Rule quality checklist
- Clear intent statement
- Known false positives documented
- Entities mapped (Account, Host, IP, URL)
- Severity aligned to impact
- Tuning log maintained
