# Change Management (Lab)

## Purpose
Keep detection and automation changes controlled and reproducible.

## Rules
- Every detection/playbook update requires:
  - Reason for change
  - Before/after behavior
  - Test evidence
  - Rollback notes (if applicable)

## Where to log
- Detection updates: `incidents/templates/detection-change-template.md`
- Major changes: create an entry in `incidents/completed/<date>-<name>/`
