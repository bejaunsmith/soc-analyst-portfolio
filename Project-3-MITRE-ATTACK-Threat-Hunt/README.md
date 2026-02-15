# MITRE ATT&CK Threat Hunt – PowerShell Execution Detection

## Objective
Performed threat hunting using Splunk SIEM to identify PowerShell execution activity, which is commonly abused by attackers.

## MITRE ATT&CK Technique
T1059.001 – Command and Scripting Interpreter: PowerShell

## Detection Query
index=main EventCode=4688 powershell.exe

## Tools Used
- Splunk Enterprise
- Windows Event Logs

## Skills Demonstrated
- Threat hunting
- MITRE ATT&CK framework mapping
- SIEM log analysis
- Suspicious process detection

## Summary
PowerShell is frequently used by attackers to execute malicious commands. This project demonstrates the ability to identify PowerShell activity using SIEM and map it to MITRE ATT&CK techniques used in real-world attacks.
