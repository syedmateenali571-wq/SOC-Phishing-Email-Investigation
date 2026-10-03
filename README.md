# Phishing Email Investigation

## Overview

This project demonstrates a simulated phishing email investigation workflow in a controlled lab environment.

The investigation focuses on analyzing email headers, sender information, authentication indicators, URLs, domains, and other potential indicators of compromise (IOCs).

## Investigation Workflow

Alert → Evidence → IOC → Analysis → MITRE Technique → Severity → Recommended Response

## Objectives

- Analyze simulated phishing email headers
- Identify sender information
- Extract URLs and domains
- Check for IP addresses
- Check for attachments and file hashes
- Review SPF, DKIM, and DMARC evidence
- Analyze phishing indicators
- Map the activity to MITRE ATT&CK
- Assign an investigation severity
- Document recommended response actions

## Project Structure

```text
SOC-Phishing-Email-Investigation/
│
├── evidence/
│   └── simulated-phishing-email.eml
│
├── iocs/
│   └── extracted-iocs.md
│
├── notes/
│   └── investigation-notes.md
│
├── reports/
│   └── incident-report.md
│
├── screenshots/
│   ├── 01-email-header.png
│   └── 02-incident-report.png
│
└── README.md