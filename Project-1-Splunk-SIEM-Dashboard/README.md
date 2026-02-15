# Splunk SIEM Dashboard and Detection Rules

## Objective
Configured Splunk Enterprise SIEM to collect and monitor Windows Security Event Logs. Created detection queries and dashboards to identify authentication events, privilege escalation, and process execution activity.

## Tools Used
- Splunk Enterprise
- Splunk Universal Forwarder
- Windows Event Logs

## Detection Queries

Successful Login Detection:
index=main EventCode=4624

Failed Login Detection:
index=main EventCode=4625

Privilege Escalation Detection:
index=main EventCode=4672

Process Execution Detection:
index=main EventCode=4688

## Screenshots
This project includes screenshots showing:

- Successful login events
- Failed login attempts
- Privilege escalation detection
- Process execution monitoring
- SIEM dashboard visualization

## Skills Demonstrated
- SIEM configuration
- Security monitoring
- Threat detection
- Log analysis
- Incident investigation
- Dashboard creation

## Summary
This project demonstrates hands-on experience configuring Splunk as a SIEM, ingesting Windows event logs, creating detection queries, and building dashboards to monitor system and authentication activity. These skills are essential for SOC Analyst roles.

