Windows SIEM Lab
Overview

This project demonstrates the deployment of a Security Information and Event Management (SIEM) solution using Splunk Enterprise and a Windows 11 virtual machine.

The objective was to collect Windows Event Logs, ingest them into Splunk, and perform security event analysis.

Tools Used
Splunk Enterprise
VirtualBox
Windows 11 Enterprise
Windows Event Logs
Lab Architecture

Windows 11 VM
↓
Windows Event Logs
↓
Splunk Enterprise
↓
Security Analysis

Objectives
Build a Windows virtual machine
Install Splunk Enterprise
Configure Windows Event Log collection
Analyze authentication events
Practice SIEM investigation techniques
Log Sources
Application
Security
System
Sample Searches

Successful Logins

index=main EventCode="4624"

Failed Logins

index=main EventCode="4625"

Results
Successfully installed Splunk Enterprise
Configured Windows Event Log ingestion
Collected over 1,300 Windows events
Verified successful login activity using Event ID 4624
Demonstrated basic SIEM monitoring and log analysis
Skills Demonstrated
SIEM Administration
Log Analysis
Security Monitoring
Windows Event Investigation
Splunk Enterprise
Virtualization
Screenshots

See repository images for lab setup and search results.
