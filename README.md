# Cyber Defense Capstone

A hands-on investigation of an internet-exposed Windows and MySQL honeypot in a controlled cyber range.

## Project overview

I investigated activity on CORP-OSCORP using Microsoft Defender for Endpoint telemetry, MySQL audit logs, KQL queries, and comparisons of two MDE investigation packages.

The report brings together a SOC incident assessment and host forensic analysis, with original screenshots and supporting evidence references.

## Tools and skills

- Microsoft Defender for Endpoint
- Kusto Query Language (KQL)
- MySQL authentication and query log analysis
- Windows Security event log analysis
- MDE investigation package comparison
- Incident timeline reconstruction
- Indicators of compromise and MITRE ATT&CK mapping
- Evidence-based reporting and remediation recommendations

## Key observations

- Destructive SQL commands and ransom-themed statements were recorded. Successful deletion or exfiltration was not established.
- A successful Administrator network logon from a public IP was followed by share enumeration. Whether the access was authorized remains unresolved.
- Firewall settings changed between captures, but attribution was not established.

The report distinguishes observed activity from probable interpretations and documents evidence gaps.

## Full report

[View the Cyber Defense Final Report](Cyber-Defense-Final-Report-2.pdf)

## Lab context

This project was conducted in a controlled honeypot laboratory. Findings relate to the lab host and do not establish production impact.

## Author

Justice Zulueta