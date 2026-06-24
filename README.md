# SIEM Home Lab — Threat Detection with Elastic Stack

## Overview
A hands-on home lab simulating real-world cyber attacks and detecting 
them using Elastic Stack (ELK). Built to develop practical SOC analyst 
skills in log analysis, alert triage, and incident response.

**Demo:** [Loom walkthrough — coming soon]

## Lab Architecture
|    Component    |      Role      |           Tool              |
|-----------------|--------------  |---------------------------- |
| Ubuntu 24.04 VM | SIEM Server    | Elasticsearch + Kibana 8.13 |
| Windows 11 VM   | Victim machine | Winlogbeat 8.13             |
| Kali Linux VM   | Attack machine | crackmapexec, nmap          |

All traffic isolated on VMware Fusion Host-only network.

## Use Cases

### Use Case 1: SMB Reconnaissance
**MITRE ATT&CK:** T1046 — Network Service Discovery

### Use Case 2: Brute Force Attack  
**MITRE ATT&CK:** T1110 — Brute Force

### Use Case 3: Suspicious Account Creation
**MITRE ATT&CK:** T1136.001 — Create Local Account
