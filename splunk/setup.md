# Splunk Setup

Configured Splunk as the central log monitoring and analysis platform for the Active Directory lab.

Windows security and system logs were collected using the **Splunk Universal Forwarder** and forwarded to the Splunk server for centralized analysis.

### Configuration

* Installed Splunk on the monitoring server.
* Installed Splunk Universal Forwarder on the Windows machine.
* Configured the Forwarder to collect Windows Event Logs.
* Configured the Splunk server to receive the forwarded data.
* Verified that events were successfully indexed and searchable.

### Log Sources

The main logs collected include:

* Windows Security Events
* System Events
* Application Events
* PowerShell activity
* Sysmon events

Screenshots are included as evidence of the actual Splunk and Universal Forwarder configuration.
