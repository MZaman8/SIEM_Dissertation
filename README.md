# SIEM Dissertation: Personal Security Information and Event Management Project
This project is the outcome of my final year dissertation to demonstrate hands-on SIEM implementation and detection engineering using open-source tools. It involved deploying a Wazuh-based SIEM solution to monitor a Windows 11 host and virtual machine, with a SIEM server hosted on Ubuntu.
<br /><br />Tools used: Wazuh, Sysmon, Suricata, Oracle Virtualbox, OpenSSH
## Architecture
**Outlines the system design** 
- Monitored endpoints
- Network configuration
- Ingestion pipeline

## Usecase Implementation
**Describes rule creation and validation**
- Honeytoken access
- Repeated local logon failures (brute force access attempt)
- PowerShell execution monitoring
- Blocked application usage (via firewall rule)
- Forbidden website access (via Suricata)

## Event Exploration
**Explores events resulting from each usecase**
- Honeytoken access
- Repeated local logon failures (brute force access attempt)
- PowerShell execution monitoring
- Blocked application usage (via firewall rule)
- Forbidden website access (via Suricata)

## Dashboards
**Dashboards for easy user usage**
- Usecase trigger dashboard
- Logon ID correlation dashboard

## Skills Learned/Applied
**System Administration**
- Configuration and usage of key tools such as Sysmon, Suricata and OpenSSH
- PowerShell/Terminal experience from direct configuration of the aforementioned tools and Wazuh in Linux and Windows

**SIEM**
- Log ingestion
- Direct Agent/Manager confguration
- Visualisation and dashboard creation
- Rule creation, implementation and verification
- Report Writing
 
**Troubleshooting**
- Virtual Machines (particularly involving network adapters)
