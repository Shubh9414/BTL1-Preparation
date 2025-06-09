# MISP Setup via OVA (Virtual Machine Import)

This document outlines how I installed and launched MISP (Malware Information Sharing Platform) using a pre-configured OVA file inside VirtualBox. This setup forms the foundation of my Threat Intelligence Lab.

## Environment

- **Host OS**: Windows 11
- **Virtualization Tool**: VirtualBox
- **VM RAM Allocated**: 4 GB
- **Disk Allocated**: 40 GB
- **MISP OVA Source**: (https://www.circl.lu/services/misp-training/#misp-virtual-machine)

## Installation Steps

### 1. Installed VirtualBox
- Downloaded from: (https://www.virtualbox.org)
- Installed with default settings

### 2. Imported MISP OVA File
- Opened VirtualBox → File → Import Appliance
- Selected downloaded `.ova` file
- Assigned:
  - **RAM**: 4 GB
  - **Processors**: 2
  - **Network Adapter**: Bridged Adapter (to access from host browser)

### 3. Started the VM
- Booted into the pre-installed Ubuntu VM

### 4. Accessed MISP Web Interface
- Opened browser inside VM or from host
- URL: `http://localhost` or `http://<VM IP>`

## Why This Matters

Using a MISP OVA allows a faster lab setup, letting me focus on understanding the MISP platform's capabilities in:
- Threat event creation
- Indicator management
- STIX/TAXII data handling
- Threat actor profiling and sharing

