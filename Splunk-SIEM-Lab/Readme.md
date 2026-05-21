## About This Lab
In this lab I installed Splunk Enterprise inside my Windows Server VM and explored how logs are collected and monitored in a SIEM environment.

## What I Did
- Installed Splunk Enterprise
- Added Windows event logs
- Viewed Security and System logs
- Performed basic searches
- Investigated login events

## Important Event IDs
- 4624 = Successful login
- 4625 = Failed login

## What I Learned
- Basics of SIEM
- Log monitoring
- Windows event analysis
- Searching logs using Splunk

## Tools Used
- Splunk Enterprise
- Windows Server 2022
- VirtualBox

## Screenshot

## 1. Splunk Dashboard
<img width="1917" height="1142" alt="1  Splunk Dashboard" src="https://github.com/user-attachments/assets/85056392-3ccc-48f9-9c37-2cf2a2d1fd34" />

## 2. windows-event-log-selection
<img width="1911" height="1117" alt="2  windows-event-log-selection" src="https://github.com/user-attachments/assets/4f864dfe-4f2b-4b32-9e9c-bd9276a439a9" />

## 3. splunk-search-reporting
<img width="1918" height="1117" alt="3  splunk-search-reporting" src="https://github.com/user-attachments/assets/87eda8f4-c86c-4508-b179-f6eaa49110ae" />

## 4. successful-login-events
<img width="1918" height="1111" alt="4  successful-login-events" src="https://github.com/user-attachments/assets/25a128be-0f78-45c9-80c7-5e9073ce782f" />

## 5. failed-login-events
<img width="1918" height="1141" alt="5  failed-login-events" src="https://github.com/user-attachments/assets/eafe4345-b9eb-4f30-8dd7-a43be77f6135" />

## 6 user-search-ApKo
<img width="1916" height="1117" alt="6 user-search-ApKo" src="https://github.com/user-attachments/assets/dc6096b8-8d57-4a45-8c80-f09af20ab806" />

## Detection Lab

Created a basic Splunk alert to detect failed login activity using Windows Event ID 4625.

The alert was configured to trigger when multiple failed login attempts were detected.

## Screenshot

## failed-login-alert-settings
<img width="1918" height="1116" alt="failed-login-alert-settings" src="https://github.com/user-attachments/assets/41c9b69f-b165-41ec-ba70-5e6d5f375a14" />

## failed-login-search-results
<img width="1918" height="1118" alt="failed-login-search-results" src="https://github.com/user-attachments/assets/508b3d09-bde8-47c2-8f38-38a08b2accac" />

## splunk-alert-created
<img width="1918" height="1122" alt="splunk-alert-created" src="https://github.com/user-attachments/assets/7108998c-3ac1-4ce8-bd73-dd924f591bab" />

## splunk-alert-list
<img width="1918" height="1117" alt="splunk-alert-list" src="https://github.com/user-attachments/assets/fb0e35b8-819b-4b3f-85e7-7f24681e3a31" />








