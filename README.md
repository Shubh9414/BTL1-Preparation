
# Security Blue Team Level 1 : Journey

> Certified: July 2025  
> Score: 85%  
> Focus Areas: Threat Intelligence • Digital Forensics • Phishing Analysis • MITRE Mapping

## Overview

This repository documents my practical journey through the **Security Blue Team Level 1 (BTL1)** certification. It includes real-world threat investigation scenarios and evidence-backed detections using industry-standard Blue Team tools like Splunk, Autopsy, Wireshark, and DeepBlueCLI.


## Experience Gained Through the Exam

The BTL1 exam was more than just a test it was a **live threat incident response simulation**. Here’s what I experienced during the 24-hour window:

- Investigated multiple compromised endpoints across a simulated corporate network
- Reconstructed the attacker’s steps from **initial phishing** to **command & control**
- Identified persistence techniques using registry forensics (`Run` keys)
- Used Splunk to correlate logs, trace attacker-created accounts, and detect privilege escalation
- Analyzed malware behavior by extracting disk image evidence in Autopsy
- Mapped real artifacts to **MITRE ATT&CK** techniques — from credential dumping to lateral movement
- Submitted findings as part of a structured investigation

This exam solidified my ability to think like a defender not just recognize attacks, but **investigate, validate, report** them under time pressure and not having a limited perspective looking through everything available and verifying it.

## Tools Used

| Tool | Purpose |
|------|---------|
| **Splunk** | Log search, timeline reconstruction, correlation |
| **Autopsy** | Disk forensics, PDF and payload tracing |
| **Wireshark** | PCAP analysis, FTP brute-force inspection |
| **DeepBlueCLI** | Windows Event Log detection (persistence, privilege escalation) |
| **eM Client** | Analyzing phishing emails and payload delivery |
| **VirusTotal & URLScan.io** | Threat intelligence enrichment of files, URLs, and domains |

## Key Lab Themes

### Phishing Email Analysis
- Investigated real email client artifacts
- Extracted URLs and attachments
- Identified malicious ZIPs and PDFs dropped via phishing

### Threat Intelligence Enrichment
- Verified payload hashes, domains, and IPs on VirusTotal
- Correlated attacker infrastructure with behavior across endpoints
- Identified impersonated domains used in spear phishing

### Digital Forensics
- Analyzed disk image using Autopsy
- Found staged malware under `AppData\Roaming\`
- Traced persistence via Windows Registry (Run keys)
- Identified attacker-created accounts and tools like `mimikatz.exe`, `dropper.exe`

### Log-Based Detection with Splunk
- tracked process creation, persistence, privilege escalation
- Detected `nc.exe`, `kryptex.exe`, and renamed SharpHound binary
- Mapped malicious file behavior to MITRE techniques (e.g., `S0521`, `T1053.005`, `T1078.002`)

## MITRE ATT&CK Techniques Applied

| Tactic | Technique |
|--------|-----------|
| Persistence | T1547.001 - Registry Run Keys |
| Privilege Escalation | T1078.002 - Admin Account Creation |
| Credential Access | T1003.001 - LSASS Dump via Mimikatz |
| Discovery | T1087.002 - SharpHound for AD Enumeration |
| Command and Control | T1105 - External C2 via Netcat |
| Collection | T1119 - File Collection from Host |

## What's Next?

I’m currently building **Blue Log** a Python-based CLI tool.
The goal is to **automate what I learned during BTL1**, including threat detection and IOC extraction.

## Looking for Opportunities

I'm actively seeking a **remote cybersecurity internship** where I can contribute my detection and investigation skills in a real SOC environment.

Let’s connect:

📧 Shu9731@gmail.com  
🔗 www.linkedin.com/in/shubham-singh-257746252  
🎓 www.credly.com/users/shubham-singh.fd78c6f4
