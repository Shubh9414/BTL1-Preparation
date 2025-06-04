# Day 3 – Phishing Analysis & Email Forensics

## Overview

Today’s focus was on phishing analysis. The module explored not only what phishing is, but also the different forms it can take, how to break down an email’s structure, and how to identify various phishing techniques and tactics.

## Key Learnings

### Phishing Types and Definitions
- **Phishing** – Deceptive emails meant to trick recipients into clicking malicious links or sharing sensitive information.
- **Smishing** – SMS-based phishing.
- **Vishing** – Voice phishing through phone calls.

### Anatomy of an Email
- Email Header:
  - `From`
  - `To`
  - `Date`
  - `Subject`
  - `Custom x-Header`
  - `Return-Path`
  - `Reply-To`
  - `Received`
- Email Body:
- These fields are crucial to identifying spoofing or redirection techniques.

### Email Authentication Protocols
- **SPF (Sender Policy Framework)** – DNS TXT file Validates that the sending mail server is authorized for the domain if not it alerts receipient.
- **DKIM (DomainKeys Identified Mail)** – Cryptographically verifies message integrity and sender authenticity.
- **DMARC (Domain-based Message Authentication, Reporting and Conformance)** – Defines how to handle unauthenticated emails using SPF/DKIM alignment.

### Phishing Email Categories
- Spam (non-malicious bulk emails)
- Malicious attachments (macros, infected PDFs)
- Credential harvesting (fake login pages)
- Recon emails (contain tracking pixels or hidden links for target profiling)
- Whaling (CEO, COO, CFO)

### Techniques Observed
- Impersonation (pretending to be internal users or executives)
- Spear phishing (personalized and targeted attacks)
- Typosquatting (e.g., "gmaiI.com" using capital 'i')
- homoglyph attacks (e.g., "YouTube" and "YóuTube" sometimes, it may go unnoticed since they might look same but i can't be blocked by google since it has a different unicode for it)
- Sender spoofing (modifying headers to fake the sender)
- HTML Styling
- Hyperlinks
- URL Shortening
## Lab Summary

Completed a phishing detection lab where multiple sample emails had to be classified based on their nature. Correctly identified and flagged all emails based on intent and observable artifacts. This helped reinforce header analysis and pattern recognition techniques in email forensics.

