Windows SSH Hardening & Access Control Lab

Objective
The goal of this project was to configure and secure remote SSH access on a Windows system and validate security controls against an unauthorized connection attempt.


Environment
Windows machine (target system)
Linux Mint VM (attacker system)
VirtualBox isolated network

Configuration Steps
Installed OpenSSH Server using PowerShell
Verified SSH service status and startup configuration
Confirmed server listening on port 22
Enabled logging through Windows Event Viewer
Created a Windows Defender Firewall inbound rule

Configuration Steps
Installed OpenSSH Server using PowerShell
Verified SSH service status and startup configuration
Confirmed server listening on port 22
Enabled logging through Windows Event Viewer
Created a Windows Defender Firewall inbound rule


Security Control Implemented
A host-based firewall rule was configured to block SSH connections from a specific IP address while allowing other network activity.
Validation Testing
An SSH connection was attempted from a Linux machine using valid credentials.
The connection repeatedly timed out, confirming the firewall rule successfully prevented unauthorized remote access.


Monitoring & Evidence
OpenSSH service events recorded in Event Viewer
Successful logon audit events visible in Windows Security logs
Blocked connection attempts from attacker system



---

## Full Project Report

A detailed executive summary and validation report for this project is available below:

📄 [Download the Full Security Report](SSH_Hardening_IP_Blocking_Report.pdf)

