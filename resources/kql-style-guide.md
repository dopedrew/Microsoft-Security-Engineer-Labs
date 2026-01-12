# KQL Style Guide (Lab)

## Principles
- Readable, repeatable, and testable
- Time-bound queries
- Document assumptions and expected output

## Practices
- Use `let` statements for clarity
- Use `project` to limit columns
- Prefer `summarize` with `bin()` for trends
- Comment non-obvious logic

## Example header
Use the template in:
`01-sentinel/kql/detections/TTP-template.kql`
