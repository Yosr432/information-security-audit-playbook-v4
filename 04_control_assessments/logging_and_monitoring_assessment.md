## Logging & Monitoring Assessment (Test Program)

### Control objectives
- Critical systems generate security logs.
- Logs are collected centrally, retained, and monitored with actionable detections.
- Alerts have clear triage, escalation, and case documentation.

### Test procedures (examples)
1) Coverage: confirm log sources onboarded (AD, endpoints, servers, cloud identity).
2) Quality: verify timestamps, host/user fields, parsing/normalization.
3) Detection: review top 10 high-risk use cases; confirm mapping to ATT&CK.
4) Operations: sample 5 alerts → verify triage notes, evidence, closure reason.
5) Metrics: review MTTD/MTTR and false-positive rate trend.

### Evidence examples
- SIEM source list export
- retention configuration
- sample alerts with case notes (redacted)
- detection catalog / runbooks
