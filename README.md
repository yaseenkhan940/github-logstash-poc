# GitHub Wazuh Integration-poc
## Overv
This repository demonstrates GitHub webhook integration with Wazuh SIEM.
All repository events are monitored and logged in real time.
Events include push, pull requests, issues, branches, and releases.
Logs are forwarded via Logstash to Wazuh manager for security monitoring.
This POC covers 10 different GitHub event types for demonstration.
Integration uses syslog protocol over TCP to Wazuh manager.....
. Each event generates a structured log entry in Wazuh dashboard. Source platform is tagged as github_poc for easy filtering. Environment is configured as POC for testing purposes. All events are visible in Wazuh Discover with full event details
SOC ANALYS.....

