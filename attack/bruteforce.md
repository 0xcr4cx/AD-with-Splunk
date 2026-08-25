# Brute Force Attack Simulation

## Overview

A controlled brute-force attack was simulated from a **Kali Linux** machine against the Active Directory lab environment.

The purpose of the simulation was to generate realistic authentication failures and observe how the activity appeared in **Windows Event Logs and Splunk**.

## Attack Flow

```text
Kali Linux
    ↓
Authentication Attempts
    ↓
Windows / Active Directory
    ↓
Failed Logon Events (4625)
    ↓
Splunk
    ↓
Detection & Investigation
```

## Investigation

The generated events were analyzed in Splunk to identify:

* Source IP address
* Target username
* Number of failed attempts
* Time of the activity
* Whether a successful login occurred after the failed attempts

The activity was then used to test the brute-force detection rule created for the lab.

## Evidence

Screenshots are included showing the attack activity from Kali Linux, the resulting Windows security events, and the corresponding Splunk investigation.
<img width="1296" height="995" alt="image" src="https://github.com/user-attachments/assets/69fac82c-2178-42de-9f0a-e05312b0885f" />
