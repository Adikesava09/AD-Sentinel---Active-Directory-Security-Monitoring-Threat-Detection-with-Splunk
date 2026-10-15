# AD Sentinel - Active Directory Security Monitoring

## Project Overview
AD Sentinel is a SOC Analyst project built using Splunk to monitor Windows Security Events and identify suspicious login activity.

## Tools Used
- Splunk Enterprise
- Windows Security Event Logs
- SPL (Search Processing Language)

## Features
- Successful Login Monitoring (Event ID 4624)
- Failed Login Monitoring (Event ID 4625)
- Login Activity Trend Visualization
- Failed Logins by Account
- Potential Brute-Force Detection
- Security Monitoring Dashboard

## Dashboard Screenshot
![AD Sentinel Dashboard]
(Screenshot 2026-10-15 151932.png)

## Detection Logic
The project searches Windows Security Events for failed logins and groups them into 5-minute intervals to identify accounts with 5 or more failed login events.

## Disclaimer
This is a learning project using local Windows event logs. A potential brute-force alert requires investigation and does not automatically confirm an attack.
