# Day 4 – Collecting Artifacts and Analysing them

## Overview

Today’s focus was on understanding and investigating **artifacts** left behind by different types of cyber activity — specifically from emails, containing links, and malicious files. These are critical elements in digital forensics and incident response.

## Key Learnings

### Email Artifacts
- Learned how to extract and analyze:
  - `Sender Email Address`,`Reciepient Address`, `Subject`, `Reply-To`, `Date and Time`, `X-sender IP` headers
- Identified indicators that reveal spoofing, phishing, or misconfigured mail servers
- manually collecting the artifacts using sublime learned to locate them.

### Web Artifacts
- Studied common artifacts left behind during web activity, such as:
  - Full URLs
  - Root domain
- Understood how to use tools such as URL2PNg to see the page in png without actually opening it, also wannabrowser which allowed to open website in a virtualized OS.
- Manual extraction of Web artifacts by hovering over and seeing the full link aand opening in sublime can help you to lacate anchor tags with the hyperlink.
### File Artifacts
- Covered how files leave behind forensic traces like:
  - A malicious file size and name.
  - Using developer tools to see the network stamp and how everything is working.
  - opened the Malicious File in Hybrid Analysis to see if it has been flagged.
- Learned how to detect file execution, deletion, and manipulation even if files are no longer present

## Lab Work

Completed three separate labs focused on artifact collection and analysis:

1. **Email Artifacts Lab**
   - Used Sublime to extract artifacts manually
   - Two mails were used to look for artifacts

2. **Investigating an Attachment Lab**
   - Analyzed File for details
   - used developer tool to look for network flow
   - extracted its hash to check for reputaion
   - used cybercafe to decipher the logo URL used
   - based on all this it was successfully identified as Credential Harvester spoofing as Microsoft

Each lab used different tools tailored to that artifact type, reinforcing how various artifacts serve specific investigative purposes.

