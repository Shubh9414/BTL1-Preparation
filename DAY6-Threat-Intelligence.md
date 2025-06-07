# Day 6 – Introduction to Threat Intelligence

## Overview

Today’s focus was on understanding the foundations of **Threat Intelligence (TI)** its importance, lifecycle, sources, and how context changes the severity and relevance of threats. Threat intelligence helps organizations understand their threat landscape and anticipate potential attacks.

## Key Learnings

### 1. Context-Based Threat Severity

- Learned how the **severity of a threat** isn't static and can **change based on context** e.g., a malware might be low severity globally but if it has been used previously with nation state attack it changes completely makes it high priority.
- Importance of **correlating TI feeds** with internal data to identify real risk.

### 2. Threat Intelligence Lifecycle

Followed the structured TI lifecycle for actionable intelligence:

- **Direction** – Define what we want to know
- **Collection** – Gather data from various sources (internal logs, open sources, dark web)
- **Processing** – Normalize and structure collected data
- **Analysis** – Interpret and assess potential threats
- **Dissemination** – Share relevant findings with the team
- **Feedback** – Review what was useful and refine the process

### 3. Types of Intelligence

| Intelligence Type | Description                                                        |
|-------------------|--------------------------------------------------------------------|
| **SIGINT**        | Signals Intelligence (intercepted communications)                  |
| **COMINT**        | Communications Intelligence (subclass of SIGINT)                   |
| **ELINT**         | Electronic Intelligence (radar, beacons, etc.)                     |
| **OSINT**         | Open-Source Intelligence (public sources like blogs, forums, etc.) |
| **HUMINT**        | Human Intelligence (informants, interviews)                        |
| **GEOINT**        | Geospatial Intelligence (maps, satellite data)                     |

### 4. Threat Groups, APTs, and Malware

- Explored how **nation-state actors** and **hacktivists (e.g., Anonymous)** use different malware families and tactics.
- Studied how **vendors like CrowdStrike and FireEye (Mandiant)** track these groups using naming conventions and reports.
- Understood the concept of **APT (Advanced Persistent Threat)**:
  - Typically **nation-state sponsored**
  - Long-term, stealthy operations
  - Motivated typically by **espionage** and **Financial Gain** but **data theft**, or **political disruption** can also be a part of it.

Examples:
- APT28 (Russia) (Fancy Bear)
- APT41 (China) (panda)
- Lazarus Group (North Korea) and how they are divide into two parts one which focuses on securing financial funds for the main team.

### 5. Application in Defense

- Recognizing the attacker **motivation, tools, and methods** helps defenders:
  - Improve detection strategies
  - Set better alerts
  - Respond with more context-aware actions

## Reflection

Understanding threat intelligence was eye-opening it’s more than just reading indicators. It’s about understanding **who is attacking**, **why**, and **how** and using that to defend smarter. Knowing the different types of intelligence and how to systematize threat collection gives clarity in building long-term detection strategies.

