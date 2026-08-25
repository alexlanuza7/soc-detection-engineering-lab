# Detections

Each detection should have its own directory, for example:

- `DET-001-failed-logons/`
- `DET-002-privileged-group-change/`
- `DET-003-powershell/`
- `DET-004-scheduled-task/`
- `DET-005-endpoint-activity/`

Each detection should document:

- Purpose
- Data source
- Detection logic
- MITRE ATT&CK mapping
- Severity
- Expected false positives
- Test procedure
- Validation evidence
- Recommended response

Only publish rules you have tested and can explain.
