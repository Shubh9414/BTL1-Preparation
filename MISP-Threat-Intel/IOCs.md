# IOC Breakdown – APT28 NCSC Report

This document outlines the Indicators of Compromise (IOCs) added to the APT28 event created from the NCSC report. These indicators reflect known TTPs (Tactics, Techniques, and Procedures) attributed to APT28's spear-phishing and credential harvesting operations.

## IOC Summary
[NCSC_APT28.pdf](https://github.com/user-attachments/files/20653739/NCSC_APT28.pdf)

## Additional Notes

- The IP and domain were marked as C2 infrastructure in the report.

- SHA256 represents the hash of the malicious executable delivered through the macro.

- The email artifacts represent common social engineering tactics.

- The mutex helps identify infected endpoints during post-compromise analysis.

## Tags & MITRE References

- APT28

- T1566.001 – Spearphishing Attachment

- T1082 – System Information Discovery

- T1059.001 – PowerShell Execution

- NCSC_report

