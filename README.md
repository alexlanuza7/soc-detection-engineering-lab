# SOC Detection Engineering Lab

[English](README.md) | [Español](README.es.md)

> Status: In progress

Enterprise-style SOC and detection engineering lab focused on endpoint telemetry, SIEM operations, detection logic, threat hunting and incident response.

## Scope

The objective is to demonstrate the complete workflow from telemetry generation to detection, investigation, response and improvement.

## Planned areas

- Windows Event Logs and Sysmon
- Wazuh SIEM/XDR
- Detection engineering
- Sigma rules
- MITRE ATT&CK mapping
- Threat hunting
- Incident investigation
- Response playbooks
- Detection as Code
- GitHub Actions validation
- Optional Microsoft Sentinel/KQL extension

## Repository structure

- `architecture/` — SOC/lab architecture diagrams
- `docs/en/` — English technical documentation
- `docs/es/` — Spanish technical documentation
- `detections/` — detection rules and tests
- `hunting/` — threat-hunting cases
- `incidents/` — documented simulated incidents
- `playbooks/` — response procedures
- `scripts/` — automation/API helper scripts
- `evidence/` — sanitized screenshots and validation evidence
- `.github/workflows/` — Detection as Code validation workflows

## Lab safety

All simulations are restricted to systems owned by the isolated lab. No real malware, unauthorized targets or company data are used.

## Progress

Rules, queries, incidents and conclusions will be added only after they have been implemented, tested and understood.
