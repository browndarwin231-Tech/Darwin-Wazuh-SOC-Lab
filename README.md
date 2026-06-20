# Darwin Wazuh SOC Lab

## Overview

This project documents the deployment and configuration of a complete Security Information and Event Management (SIEM) lab using Wazuh.

The environment consists of an Ubuntu Server running the Wazuh Manager, Wazuh Indexer, and Wazuh Dashboard with a Windows 11 endpoint monitored by the Wazuh Agent.

The lab demonstrates real-time log collection, endpoint monitoring, threat hunting, security configuration assessment, and security event analysis.

---

## Environment

- Ubuntu Server
- VMware Workstation
- Wazuh Manager
- Wazuh Indexer
- Wazuh Dashboard
- Windows 11 Pro
- Wazuh Agent

---

## Skills Demonstrated

- Linux Administration
- SIEM Deployment
- Endpoint Security Monitoring
- Threat Hunting
- Security Event Analysis
- Windows Log Collection
- Ubuntu Server Administration
- Security Configuration Assessment
- Incident Investigation
- Blue Team Operations

---

## Features

- Installed Wazuh Manager
- Configured Wazuh Indexer
- Configured Wazuh Dashboard
- Connected Windows 11 Agent
- Monitored Windows Security Events
- Collected Windows Event Logs
- Real-time Alert Monitoring
- Threat Hunting Dashboard
- MITRE ATT&CK Mapping
- Security Configuration Assessment
- Authentication Monitoring
- Windows Endpoint Monitoring

---

## Technologies

- Wazuh
- Ubuntu Linux
- Windows 11
- VMware Workstation
- OpenSearch
- Linux CLI
- PowerShell

---

## Screenshots

### 1. Wazuh Dashboard Overview

Overall SIEM dashboard displaying agent status, alert severity, and security monitoring summary.
![Dashboard Overview](01-dashboard-overview.png)

### 2. Active Windows Endpoint

Windows 11 endpoint successfully connected to the Wazuh Manager and actively reporting security events.
![Agent Active](02-agent-active.png)

### 3. Threat Hunting Dashboard

Threat Hunting dashboard displaying alert trends, authentication activity, and MITRE ATT&CK mappings.
![Threat Hunting Dashboard](03-Threat-hunting-dashboard.png)

### 4. Threat Hunting Events

Real-time security events collected from the monitored Windows endpoint for investigation and analysis.
![Threat Hunting Events](04-threat-hunting-events.png)

### 5. Security Configuration Assessment

CIS Microsoft Windows 11 Enterprise Benchmark assessment showing system compliance and failed security checks. 
![Configuration Assessment](05-configuration-assessment.png)

### 6. Windows Agent Installation & Verification

PowerShell commands used to install, start, and verify the Wazuh Agent service on the Windows endpoint.
![Windows Agent Setup](06-windows-agent-setup.png)

### 7. Wazuh Dashboard Service

Verification that the Wazuh Dashboard service is active and running on the Ubuntu Server.
![Wazuh Dashboard Service](07-wazuh-dashboard-service.png)

### 8. Wazuh Indexer Service

Verification that the Wazuh Indexer (OpenSearch) service is active and processing security data.
![Wazuh Indexer Service](08-wazuh-indexer-service.png)

### 9. Wazuh Manager Service

Verification that the Wazuh Manager service is active and successfully managing security events.
![Wazuh Manager Service](09-wazu-manager-service.png)

---

## Future Improvements

- Detect Failed Logins
- File Integrity Monitoring
- PowerShell Monitoring
- Malware Detection
- Brute Force Detection
- Sysmon Integration
- Active Response Rules
- Email Alerting

---

## Author

Darwin Brown
