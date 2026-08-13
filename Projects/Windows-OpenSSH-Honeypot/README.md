# Windows OpenSSH Honeypot

## Project Overview

This project involved configuring an OpenSSH server on a Windows virtual machine to simulate and analyze unauthorized SSH activity. The goal was to gain hands-on experience with security monitoring, log analysis, threat identification, and firewall-based mitigation.

## Objectives

- Install and configure OpenSSH Server on Windows
- Enable and verify SSH logging
- Generate SSH activity from a Kali Linux machine
- Analyze Windows logs to identify the source IP address
- Create a Windows Firewall rule to block the identified IP address
- Verify that the mitigation was successful

## Tools & Technologies

- Windows
- Kali Linux
- OpenSSH
- Windows Event Viewer
- Windows Firewall
- PowerShell
- Virtual Machines

## Project Steps

### 1. OpenSSH Configuration
Installed and configured OpenSSH Server on the Windows virtual machine and verified that the SSH service was running.

### 2. SSH Connection Testing
Used Kali Linux to generate SSH connection activity against the Windows system.

### 3. Log Analysis
Reviewed Windows security and OpenSSH logs to identify the source IP address associated with the SSH activity.

### 4. Threat Mitigation
Created a Windows Firewall rule to block traffic originating from the identified IP address.

### 5. Verification
Tested the firewall configuration to confirm that the source system could no longer establish the same connection.

## Skills Demonstrated

- Security Monitoring
- Log Analysis
- Incident Response
- Windows Security
- Network Security
- Firewall Configuration
- Threat Identification
- PowerShell
