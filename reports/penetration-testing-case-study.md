# Penetration Testing — Vagrant Windows Server Lab (July 2023)

**Type:** Educational security assessment case study  
**Author:** Bhargav Gosai  
**Environment:** Windows Server target and Kali Linux assessment workstation

## Objective
Assess an intentionally scoped Windows Server/web application environment and document the security impact of outdated software.

## Methodology and tools
- Host discovery and reconnaissance using Netdiscover and Nmap
- Vulnerability scanning using Nessus; web assessment using Nikto and DirBuster
- OSINT and review of publicly documented vulnerabilities
- Controlled proof-of-concept validation in the assessment environment
- Post-exploitation verification and written remediation advice

## Findings and outcome
The assessment identified an outdated Tdarr web application version with a documented command-injection issue. The report records successful remote command execution and a reverse-shell proof of concept in the lab. Recommended improvements included updating vulnerable applications, restricting unnecessary services and ports, and using secure transport and monitoring.

## Skills demonstrated
Vulnerability assessment · Nmap · Nessus · Nikto · DirBuster · Kali Linux · Windows Server · Technical security reporting

**Publication note:** This is a sanitized summary, not the original confidential report. It intentionally omits target identifiers, screenshots, exploit commands and third-party information. It does not represent a live-client penetration test.
