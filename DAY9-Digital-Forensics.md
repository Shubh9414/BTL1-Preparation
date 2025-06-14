# DAY9 Digital forensics

## Focus: Windows & Linux Forensics + Memory Analysis

Today’s module was mostly focused on labs i continued the Digital Forensics journey by focusing on Windows and Linux artifacts, steganography, and memory dump analysis using popular forensic tools. This day emphasized the real-world value of system log analysis and volatile data extraction.

## Topics Covered

### Windows Artifacts

- Retrieved and analyzed metadata from files and system logs

### Linux Forensics Investigation

- Investigated:

 - /etc/passwd and /etc/shadow (user accounts and hashes)

 - /var/log/ for key forensic files: auth.log, dpkg.log, cron, secure, btmp, fail.log

 - Web server logs (/var/log/apache2/access.log)

 - .bash_history and shell command patterns

### Steganography

- Used steghide to hide and extract data from images canalso password protect using this

- Understood how attackers may embed payloads or sensitive data covertly

## Memory Forensics with Volatility

### Volatility 2 & 3

- Used volatility2 for analyzing memory dumps

- Transitioned to Volatility 3 GUI version for ease of use

- Explored core plugins: pslist, pstree, cmdline, dlllist, filescan, malfind

- searched for PID 2416  

### Volatility Workbench

- Practiced on Volatility Workbench (GUI wrapper)

- Improved speed in processing dumps for quick snapshots of process and network activity

## Final Lab: Autopsy

### Autopsy Digital Forensics Platform

- Loaded a forensic image into Autopsy

- Reviewed file timelines, web history, and user data

- Noted as a powerful, widely-used open-source forensic suite


## Summary

Today delivered practical insight into both host-based forensic investigation and memory dump analysis. From analyzing Linux logs to uncovering hidden files via steganography and mastering Volatility and Autopsy, this day helped cement essential forensic skills.
