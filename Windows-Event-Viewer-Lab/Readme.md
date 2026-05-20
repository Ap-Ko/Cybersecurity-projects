# Windows Event Viewer Lab

## About This Lab
In this lab I explored Windows Event Viewer to understand how Windows stores authentication and system logs.

I investigated successful and failed login events and learned how SOC analysts analyze Windows security logs.

## What I Did
- Opened Event Viewer
- Explored Windows log categories
- Investigated Security logs
- Analyzed Event ID 4624
- Analyzed Event ID 4625
- Filtered logs by Event ID
- Compared Event Viewer logs with Splunk

## Important Event IDs
- 4624 = Successful login
- 4625 = Failed login

## What I Learned
- Basics of Windows Event Logs
- Security log investigation
- Authentication monitoring
- Log filtering
- Difference between Event Viewer and SIEM tools

## Tools Used
- Windows Server 2022
- Event Viewer
- Splunk Enterprise
- VirtualBox

## Screenshot

## 1. Event-viewer-overview
<img width="1918" height="1111" alt="1  Event-viewer-overview" src="https://github.com/user-attachments/assets/ad75eb0a-2e75-48cc-a957-55f2e7468c3c" />

## 2. successful-login-event-4624
<img width="1915" height="1116" alt="2  successful-login-event-4624" src="https://github.com/user-attachments/assets/73b14878-2731-4665-b6cd-19a5ad2b42d1" />

## 3. failed-login-event-4625
<img width="1918" height="1117" alt="3  failed-login-event-4625" src="https://github.com/user-attachments/assets/35c832c0-96a0-4291-9c78-c9d814def561" />

## 5. Splunk-event-4625-statistics
<img width="1915" height="1115" alt="5  Splunk-event-4625-statistics" src="https://github.com/user-attachments/assets/df278f4d-9a9f-41d3-b209-d38bd92f3c86" />




