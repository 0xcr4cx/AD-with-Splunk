# Splunk Queries

This file contains the SPL (Search Processing Language) queries used to monitor and investigate security activity in the Active Directory environment.

4624  → Successful Logon
4625  → Failed Logon
4648  → Explicit Credentials
4672  → Privileged Logon
4688  → Process Creation
4720  → User Created
4732  → User Added to Security Group
4740  → Account Locked
4768  → Kerberos Authentication
4769  → Kerberos Service Ticket
4771  → Kerberos Authentication Failed
1102  → Security Log Cleared.

The queries focus on:

* Successful and failed logons
* Brute-force and password-spraying activity
* User account changes
* Account lockouts
* PowerShell activity
* Suspicious or unusual authentication activity

Each query includes a short explanation of what it detects and the relevant Windows Event IDs.

Screenshots of the queries and their results are included as evidence of the actual investigation performed in the lab.
<img width="1300" height="589" alt="image" src="https://github.com/user-attachments/assets/23f226ce-2624-423e-9b9c-d7682cc397a5" />
<img width="1302" height="1002" alt="image" src="https://github.com/user-attachments/assets/9cafe1a5-d1e2-43e8-9bd9-cc88ded865a8" />
<img width="1302" height="1002" alt="image" src="https://github.com/user-attachments/assets/8e788c5f-ec07-4d76-ac27-179dce54b96c" />
