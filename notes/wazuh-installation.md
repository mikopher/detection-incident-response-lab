# Day 2 - Wazuh Server Installation

## Done
- Installed Wazuh using the official all-in-one installer.
- Installed Wazuh indexer, manager, dashboard, and Filebeat.
- Confirmed Wazuh dashboard is accessible from the Windows host browser.
- Logged in to the dashboard using the generated admin credentials.
- Verified all Wazuh services are active and running.

## Learned
- Wazuh has multiple components: indexer, manager, dashboard, and Filebeat.
- The dashboard runs over HTTPS using a local lab certificate.
- The browser warning is expected because the certificate is self-signed.
- No agents are registered yet because the Windows endpoint has not been added.

## Evidence
- screenshots/day02-wazuh-dashboard-overview.png
- screenshots/day02-wazuh-services-running.png

## Next
Create the Windows endpoint VM and prepare it for Wazuh agent and Sysmon.