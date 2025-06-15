# DAY 10-SIEM

## Focus: Introduction to SIEM Platforms and Windows Event Analysis

Today marked the start of a new and exciting domain — Security Information and Event Management (SIEM). Since I already had exposure to SIEM (especially Splunk), this session helped deepen my understanding by exploring other platforms and reinforcing event log analysis.

## Topics Covered

### SIEM Overview

- SIEM is used for real-time monitoring, alerting, and correlation of security events.

- Explored various SIEM platforms:Splunk, Graylog, ArcSight, QRadar, LogRhythm

### Logging Basics

- Log ingestion and data aggregation concepts

- Importance of centralized logging and parsing

### Syslog Protocol

- Used for log transmission in networked devices

- Default port: UDP 514 (insecure)

- For security and reliability, TCP or encrypted syslog (TLS) is recommended

## Windows Event Logs

### Event Viewer Categories

- Application

- System

- Security

- Directory Service

- DNS Server

- File Replication Service

## Common Security Event IDs

|Event ID        |Description                             |
|----------------|----------------------------------------|
|4625            |Failed login attempt                    |
|4647            |User initiated logoff                   |
|4648            |Logon attempt using explicit credentials|
|4659            |Handle to an object was requested       |
|4706            |A new trust was created to a domain     |
|4720            |A user account was created              |
|4726            |A user account was deleted              |
|4732            |A user was added to a privileged group  |

These are crucial for detecting suspicious activity in SOC operations.

## Lab Activity: Windows Event Viewer Investigation

- Tasked with identifying unusual logon patterns from an employee

- Used Event Viewer to analyze logon times and correlate with after-hours access

- Helped understand how internal abuse or compromise may present in logs

## Additional Tools and Concepts Introduced

- Sysmon – Provides detailed system event logging (process creation, network connections)

- Azure Monitor + KQL (Kusto Query Language) – For analyzing logs in cloud environments

- OSQuery – Query operating system information like a database (useful for DFIR and threat hunting)

- Arkime (formerly Moloch) – Full packet capture and search engine (network forensics)

## Data Types in SIEM

- Structured – JSON, key-value logs, CSV

- Unstructured – Raw text logs, multiline application logs

## Reflection

SIEM is an essential core of Blue Team operations. While I had used Splunk before, today’s session introduced me to a wider ecosystem of tools and highlighted how Windows event IDs, syslog, and advanced sources like Sysmon and OSQuery feed into a SIEM to enable real-time detection and threat hunting.
