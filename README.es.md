# Laboratorio SOC y Detection Engineering

[English](README.md) | [Español](README.es.md)

> Estado: En progreso

Laboratorio con enfoque empresarial centrado en telemetría de endpoints, operaciones SIEM, lógica de detección, threat hunting y respuesta a incidentes.

## Alcance

El objetivo es demostrar el flujo completo desde la generación de telemetría hasta la detección, investigación, respuesta y mejora de las reglas.

## Áreas previstas

- Windows Event Logs y Sysmon
- Wazuh SIEM/XDR
- Detection Engineering
- Reglas Sigma
- Mapeo con MITRE ATT&CK
- Threat Hunting
- Investigación de incidentes
- Playbooks de respuesta
- Detection as Code
- Validación con GitHub Actions
- Ampliación opcional a Microsoft Sentinel/KQL

## Estructura

- `architecture/` — diagramas del SOC/laboratorio
- `docs/en/` — documentación técnica en inglés
- `docs/es/` — documentación técnica en español
- `detections/` — reglas de detección y pruebas
- `hunting/` — casos de threat hunting
- `incidents/` — incidentes simulados documentados
- `playbooks/` — procedimientos de respuesta
- `scripts/` — scripts de automatización/API
- `evidence/` — capturas y evidencias sanitizadas
- `.github/workflows/` — validación de Detection as Code

## Seguridad del laboratorio

Todas las simulaciones se limitan a sistemas propios del laboratorio aislado. No se utilizará malware real, objetivos no autorizados ni información corporativa.

## Progreso

Las reglas, consultas, incidentes y conclusiones se añadirán únicamente después de haber sido implementados, probados y comprendidos.
