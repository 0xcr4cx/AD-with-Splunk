## Active Directory SOC Lab with Splunk
### Overview

This project demonstrates the design and implementation of a Security Operations Center (SOC) lab focused on Active Directory security monitoring and threat detection using Splunk. The environment simulates a real-world enterprise network consisting of a Windows Server 2022 Domain Controller, Windows client endpoints, and a Splunk SIEM server for centralized log collection, analysis, and alerting.

The primary objective of this lab is to gain hands-on experience with Active Directory administration, Windows logging, SIEM operations, threat hunting, and detection engineering by generating and analyzing security events in a controlled environment.

## Lab Architecture
Windows Server 2022 (Domain Controller)
Active Directory Domain Services (AD DS)
DNS Server
Windows 10/11 Domain-Joined Endpoints
Splunk Enterprise
Sysmon for Enhanced Endpoint Telemetry


## Features
### Active Directory Administration
Domain creation and configuration
User and group management
Organizational Unit (OU) management
Group Policy Object (GPO) implementation
Privileged account administration


### Log Collection & Monitoring
Windows Security Event Logs
Sysmon Operational Logs
PowerShell Logging
Kerberos Authentication Events
Account Management Events
Privilege Escalation Events


### Detection Engineering

Custom Splunk searches and alerts were developed to detect:

Failed Logon Attempts (Event ID 4625)
Successful Logons (Event ID 4624)
Account Lockouts (Event ID 4740)
User Account Creation (Event ID 4720)
User Account Deletion (Event ID 4726)
Group Membership Changes (Event IDs 4728, 4732)
Privileged Account Activity
Suspicious PowerShell Execution (Event ID 4104)
Kerberos Authentication Activity (Event IDs 4768, 4769)

### Threat Hunting Use Cases
Password Spraying Detection
Brute Force Activity Detection
Unauthorized Privilege Escalation
Suspicious Administrative Actions
Lateral Movement Investigation
Service Account Monitoring
Abnormal Authentication Patterns


### Splunk Dashboards

The project includes dashboards for:

Authentication Monitoring
Account Management Activity
Privileged User Tracking
Security Event Trends
Endpoint Activity Monitoring
Threat Hunting Investigations
MITRE ATT&CK Coverage

The detection logic is mapped to relevant MITRE ATT&CK techniques, including:

T1110 – Brute Force
T1078 – Valid Accounts
T1059.001 – PowerShell
T1558 – Steal or Forge Kerberos Tickets
T1069 – Permission Groups Discovery
T1484 – Domain Policy Modification


### Skills Demonstrated
Active Directory Security
Splunk SIEM Administration
Detection Engineering
Threat Hunting
Security Monitoring
Incident Investigation
Windows Event Log Analysis
Sysmon Analysis
Active Directory Attack Detection
SOC Operations

### Learning Outcomes
This project provides practical experience in building and defending a Windows Active Directory environment while developing SOC analyst skills in monitoring, detection, investigation, and incident response using Splunk.
