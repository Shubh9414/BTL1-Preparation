# MISP Threat Intelligence Lab

This project documents the complete setup and hands-on usage of [MISP](https://www.misp-project.org/) as a personal **Threat Intelligence Platform (TIP)**. The lab simulates real-world SOC analyst workflows like ingesting IOCs, creating threat events, exporting data in STIX format, and using threat intel for defensive security.

## Objective

To build and demonstrate a working Threat Intelligence lab using MISP, showcasing my understanding of:
- Threat event creation
- IOC enrichment and analysis
- STIX/TAXII export
- Threat actor profiling
- Practical Blue Team skills

## Environment & Tools

| Component           | Description                        |
|---------------------|------------------------------------|
| MISP                | Threat Intelligence Platform       |
| VirtualBox          | Virtual machine environment        |
| OVA File            | Pre-installed MISP VM from CIRCL   |
| Ubuntu (inside OVA) | Host OS for MISP platform          |
| STIX Export         | Threat data sharing format         |
| Markdown + GitHub   | Documentation and project tracking |

## Project Structure

```bash
misp-lab/
├── README.md              ← This file
├── ova-setup.md           ← Step-by-step MISP setup via OVA
├── events.md              ← Creating and documenting MISP events
├── iocs.md                ← Indicators of Compromise added and analyzed
├── export.md              ← STIX and other data export examples
├── screenshots/           ← Setup and usage screenshots
└── use-case-apt28.md      ← (Planned) Simulated APT event for showcase

