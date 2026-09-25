# Scheduled Task Investigation

## Activity
Created a scheduled task named `WazuhLabTask` on `WIN-ENDPOINT`.

## Detection
Wazuh detected the scheduled task creation through Windows Security Event ID 4698.

## Evidence
- Event ID 4698: scheduled task created
- Task: `WazuhLabTask`
- User: `mikopher`
- Endpoint: `WIN-ENDPOINT`

## Analyst Assessment
The activity was intentionally generated for the lab. In a production environment, an unexpected scheduled task should be investigated because scheduled tasks can be used for persistence or automated execution.