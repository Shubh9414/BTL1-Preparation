# MISP Threat Intelligence Lab – APT28 Simulation

This project documents the creation and usage of a self-hosted MISP (Malware Information Sharing Platform) instance to simulate a real-world Threat Intelligence workflow based on the APT28 (Fancy Bear) campaign reported by the NCSC.

The goal is to demonstrate practical Blue Team skills around threat modeling, IOC enrichment, MITRE ATT&CK mapping, and sharing threat data using structured formats like STIX.

## Objective

To simulate a full Threat Intelligence lifecycle using a real threat actor profile (APT28) by:

- Setting up MISP using OVA

- Creating a detailed threat event based on NCSC data

- Populating IOCs from the report

- Mapping TTPs to MITRE ATT&CK

## Lab Environment

|Component             | Description                |
|----------------------|----------------------------|
|OS                    | Ubuntu (via CIRCL MISP OVA)|
|TIP                   | MISP (v2.4.x)              |
|Hypervisor            | VirtualBox                 |
|Interface             | MISP Web UI + Command Line |
|Threat Source         | NCSC Report on APT28       |

## Repository Structure
```bash
MISP-Threat-Intel/
├── README.md             # Overview of the lab 
├── ova-setup.md          # Step-by-step setup using OVA
├── Events.md             # MISP event creation for APT28
├── IOCs.md               # IOC enrichment based on threat report
└── Screenshots/          # Visual documentation (login, event, IOC)
```
## Key Skills Demonstrated

- MISP deployment using OVA

- Creating a structured threat event

- IOC enrichment (IPs, hashes, domains, email artifacts)

- MITRE ATT&CK technique tagging

- Exporting intelligence in STIX 2.1 format

- Documentation and security reporting

## Use Case Summary

Simulating APT28 provides a realistic view of how nation-state actors conduct spear phishing and credential harvesting campaigns. Using MISP allows for structured ingestion, tagging, sharing, and exporting of threat intel — closely mirroring how Security Operations Centers (SOCs) operate in real environments.

## Why This Matters

This project bridges the gap between threat intelligence theory and hands-on Blue Team operations. It serves as a practical, showcase-worthy portfolio piece for SOC analyst roles, internships, and advanced Blue Team certifications.

"Real cyber defense starts with real intelligence and that’s what this lab delivers."

Built by Shubham Singh as part of Threat Intel learning & BTL1 documentation.


