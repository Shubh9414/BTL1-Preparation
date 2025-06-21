# DAY13 Incident Response

## Focus Area
- Final phase of the **Incident Response Lifecycle**
- Forensic Imaging, Root Cause Analysis, and Recovery
- Deep Dive into **MITRE ATT&CK Framework** and **Attack Navigator**

## Incident Response Lifecycle Phase Covered

### Containment
- Short-Term Containment
  - Isolate affected systems
  - Capture forensic evidence 
- Long-Term Containment
  - Temporary fixes to keep business running safely (e.g., redirecting services)

### Eradication
- Identify and remove
  - Malware files
  - Persistence mechanisms
  - Unauthorized user accounts

- Tools Used:
  - FTK Imager 
  - KAPE 

### Recovery
- Restore clean systems
- Validate integrity before reconnecting to production
- Monitor post-incident for signs of reinfection

## MITRE ATT&CK Framework Overview

### 14 ATT&CK Tactics Covered:
1. Initial Access  
2. Execution  
3. Persistence  
4. Privilege Escalation  
5. Defense Evasion  
6. Credential Access  
7. Discovery  
8. Lateral Movement  
9. Collection  
10. Command and Control  
11. Exfiltration  
12. Impact  
13. Reconnaissance  
14. Resource Development  

- Reviewed multiple techniques per tactic 
- Studied technique IDs, sub-techniques, and common mitigations
  
## Final Activity: MITRE ATT&CK Navigator
- Mapped sample threat activity using ATT&CK Navigator  
- Practiced layer creation, technique color-coding, and sharing  
- Identified potential visibility gaps in defense

## Summary
Today concluded the BTL1 journey with a deep understanding of the final response phases, reporting, and MITRE-based threat modeling. Using tools like KAPE and ATT&CK Navigator cemented the connection between tactical detection and strategic defense.

I now feel confident in my ability to:
- Contain and recover from incidents
- Conduct deep post-incident analysis
- Use threat modeling tools like MITRE Navigator
- Contribute to building stronger blue team playbooks

