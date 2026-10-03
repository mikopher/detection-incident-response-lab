# Account Discovery Investigation

## Activity
Executed the `net user` command on `WIN-ENDPOINT` to enumerate local user accounts.

## Detection
Wazuh detected the activity as discovery behavior from the Windows endpoint.

## Evidence
- Command: `net user`
- Endpoint: `WIN-ENDPOINT`
- Wazuh rule: Discovery activity executed
- Rule ID: 92031

## MITRE ATT&CK
- T1087 — Account Discovery

## Analyst Assessment
This activity was intentionally generated for the lab. In a production environment, unexpected account enumeration may indicate reconnaissance performed after initial access.