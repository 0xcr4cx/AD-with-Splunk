# Sysmon Setup

Configured Microsoft Sysmon on the Windows environment to collect detailed endpoint telemetry for security monitoring and investigation.

For the Sysmon configuration, I used the **Sysmon Modular configuration** to enable relevant security-focused telemetry and filtering.

The configuration provides visibility into activities such as:

- Process creation
- Network connections
- File creation
- Process termination
- Image/DLL loading
- Registry activity
- DNS queries
- Process access and other suspicious behavior

The Sysmon events were forwarded to Splunk and used alongside Windows Security Events during attack simulations and investigations.

## Evidence

Screenshots are included showing the Sysmon configuration and generated events from the lab environment.
<img width="1917" height="932" alt="image" src="https://github.com/user-attachments/assets/dfd04369-9887-4d62-8d77-608717cbc1c6" />
