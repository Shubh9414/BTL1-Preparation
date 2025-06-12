# Day 8- Digital Forensics

## Focus: Digital Forensics Fundamentals + Practical Lab

Today it was mainly focused on Digital Forensics, a distinct and critical domain within Blue Team operations. It included both theoretical understanding of evidence handling and hands-on exposure to common forensic tools used in the field.

## Topics Covered

### Data Representation & CyberChef

- Learned basic data formats (hex, ASCII, binary, Base64, octal)

- Used CyberChef to convert and analyze data representations

### Storage Device Concepts

- A basic understanding of HDD and SSD, what ar there structure like concepts garbage collection and trim

- Understood wear leveling in SSDs and its forensic implications

- Different file systems 

### Digital Evidence & handling

- What qualifies as digital evidence

- Importance of order of volatility (registers & cache → RAM → disk → remote logging and monitoring data → Physical configuration, Network topology, Archival media)

- Use of write blockers to prevent evidence tampering

- Role of hashing (MD5/SHA) to validate integrity

### Chain of Custody & Legal Compliance

- Followed ACPO principles for handling evidence

- Importance of Chain of Custody logs

- Ensuring admissibility in court via proper handling

## Tools & Labs Practiced

 ### FTK Imager

 - Created a memory dump and browsed forensic images

 - Practiced imaging best practices without modifying evidence

 ### Scalpel

 - Used for file carving from unallocated space

 - Practiced identifying and recovering deleted files

 ### KAPE (Kroll Artifact Parser and Extractor)

 - Simulated logging into a remote system to collect forensic artifacts

 - Exported data back to local system for examination

 ### Procdump

 - Collected a specific process dump using its PID

 - Useful for malware analysis and memory inspection

## Summary

Day 8 built a strong foundation in digital forensics, balancing theory and hands-on lab exposure. From evidence integrity to memory forensics and remote artifact collection, this day highlighted the investigative mindset needed in Blue Team environments.

“Evidence is fragile and handling it right is the difference between justice and compromise.”

