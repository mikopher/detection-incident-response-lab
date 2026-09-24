# Local Account Privilege Change

## Activity
Created the local account `wazuhlab` on `WIN-ENDPOINT` and added it to the local Administrators group.

## Detection
Wazuh detected both the account creation and the Administrators group membership change.

## Evidence
- Event ID 4720: local user account created
- Event ID 4732: member added to local Administrators group
- Account: `wazuhlab`
- Endpoint: `WIN-ENDPOINT`

## Analyst Assessment
This activity was intentionally generated for the lab. In a production environment, an unexpected local account creation followed by addition to the Administrators group would require investigation because it grants elevated privileges.