# SIEM Dissertation: Personal Security Information and Event Management Project
This project is the outcome of my final year dissertation to demonstrate hands-on SIEM implementation and detection engineering using open-source tools. It involved deploying a Wazuh-based SIEM solution to monitor a Windows 11 host and virtual machine, with a SIEM server hosted on Ubuntu.
<br /><br />Tools used: Wazuh, Sysmon, Suricata, Oracle Virtualbox, OpenSSH
## [Architecture](https://github.com/MZaman8/SIEM_Dissertation/tree/main/1-%20Architecture)
**Outlines the system design** 
- [Ingestion pipeline](https://github.com/MZaman8/SIEM_Dissertation/blob/main/1-%20Architecture/Log%20Ingestion%20Pipeline.pdf)
- [Monitored endpoints](https://github.com/MZaman8/SIEM_Dissertation/blob/main/1-%20Architecture/Architecture.pdf)
- [Network configuration](https://github.com/MZaman8/SIEM_Dissertation/blob/main/1-%20Architecture/Architecture.pdf)

## [Usecase Implementation](https://github.com/MZaman8/SIEM_Dissertation/tree/main/2-%20Usecase%20Implementation)
**Describes rule creation and validation**
- [Honeytoken access](https://github.com/MZaman8/SIEM_Dissertation/blob/main/2-%20Usecase%20Implementation/Usecase%201-%20Honeytoken.pdf)
- [Repeated local logon failures (brute force access attempt)](https://github.com/MZaman8/SIEM_Dissertation/blob/main/2-%20Usecase%20Implementation/Usecase%202-%20Multiple%20Failed%20Physical%20Logins.pdf)
- [PowerShell execution monitoring](https://github.com/MZaman8/SIEM_Dissertation/blob/main/2-%20Usecase%20Implementation/Usecase%203-%20Powershell%20Execution.pdf)
- [Failed remote logon attempt](https://github.com/MZaman8/SIEM_Dissertation/blob/main/2-%20Usecase%20Implementation/Usecase%204-%20Failed%20Remote%20Logon%20Attempt.pdf)
- [Successful remote logon attempt](https://github.com/MZaman8/SIEM_Dissertation/blob/main/2-%20Usecase%20Implementation/Usecase%205-%20Successful%20Remote%20Logon%20Attempt.pdf)
- [Blocked application usage (via firewall rule)](https://github.com/MZaman8/SIEM_Dissertation/blob/main/2-%20Usecase%20Implementation/Usecase%206-%20Attempt%20to%20Use%20a%20Blocked%20Application.pdf)
- [Forbidden website access (via Suricata)](https://github.com/MZaman8/SIEM_Dissertation/blob/main/2-%20Usecase%20Implementation/Usecase%207-%20Attempt%20to%20Access%20a%20Blocked%20Website.pdf)

## [Event Exploration](https://github.com/MZaman8/SIEM_Dissertation/tree/main/3-%20Event%20Analysis)
**Explores events resulting from each usecase**
- [Honeytoken access](https://github.com/MZaman8/SIEM_Dissertation/blob/main/3-%20Event%20Analysis/Usecase%201-%20HoneyToken%20Access%20Analysis.pdf)
- [Repeated local logon failures (brute force access attempt)](https://github.com/MZaman8/SIEM_Dissertation/blob/main/3-%20Event%20Analysis/Usecase%202-%20Repeated%20Failed%20Physical%20Logins%20Analysis.pdf)
- [PowerShell execution monitoring](https://github.com/MZaman8/SIEM_Dissertation/blob/main/3-%20Event%20Analysis/Usecase%203-%20Powershell%20Execution%20Analysis.pdf)
- [Blocked application usage (via firewall rule)](https://github.com/MZaman8/SIEM_Dissertation/blob/main/3-%20Event%20Analysis/Usecase%206-%20Blocked%20Chrome%20Use%20Analysis.pdf)
- [Forbidden website access (via Suricata)](https://github.com/MZaman8/SIEM_Dissertation/blob/main/3-%20Event%20Analysis/Usecase%207-%20Facebook%20Access%20Attempt%20Analysis.pdf)

## [Dashboards](https://github.com/MZaman8/SIEM_Dissertation/tree/main/4-%20Dashboards)
**Dashboards for easy user usage**
- [Usecase trigger dashboard](https://github.com/MZaman8/SIEM_Dissertation/blob/main/4-%20Dashboards/Correlation%20Dashboard.png)
- [Logon ID correlation dashboard](https://github.com/MZaman8/SIEM_Dissertation/blob/main/4-%20Dashboards/Correlation%20Dashboard.png)

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
