# GRC102 Week 4 Practical Laboratory
## Linux Security Monitoring and Auditing
 
### Student Information
 
| Field | Details |
|---------|---------|
| Student Name | Chioma Ameh |
| Registration Number | C11/26/CGRCE/17567 |
| Course | GRC102 – Information Security Governance |
| Module | Module 4 – Monitoring and Auditing Security Controls |
| Role | Security Control Assurance Analyst |
 
---
 
# Laboratory Overview
 
This repository contains the evidence and final report for the GRC102 Week 4 Practical Laboratory: Linux Security Monitoring and Auditing.
 
The practical exercise focused on:
 
- Linux auditd configuration and monitoring
- Audit event analysis using ausearch and aureport
- Linux authentication and system log analysis
- Linux security assessment using Lynis
- Control monitoring and governance reporting
- SIEM and continuous monitoring mapping
- Audit reporting and remediation planning
 
All activities were conducted exclusively within the authorized ICDFA Ubuntu Practice Hub environment.
 
---
 
# Repository Structure
 
## Evidence Bundle 1
Auditd Configuration and Event Analysis
 
Location:
 
```text
Evidence/Bundle_1_Auditd/
```
 
Contains:
 
- auditd verification
- custom audit rules
- audit queries
- audit reporting
- audit interpretation
 
---
 
## Evidence Bundle 2
Linux Log Analysis
 
Location:
 
```text
Evidence/Bundle_2_Log_Analysis/
```
 
Contains:
 
- journalctl review
- authentication review
- privilege-use review
- security event findings
 
---
 
## Evidence Bundle 3
Lynis Security Assessment
 
Location:
 
```text
Evidence/Bundle_3_Lynis/
```
 
Contains:
 
- Lynis installation
- Lynis execution
- hardening assessment
- warnings and recommendations
 
---
 
## Evidence Bundle 4
Control Monitoring and Governance
 
Location:
 
```text
Evidence/Bundle_4_Control_Monitoring/
```
 
Contains:
 
- governance findings
- control monitoring records
- remediation ownership
- retesting requirements
 
---
 
## Evidence Bundle 5
SIEM and Automation Mapping
 
Location:
 
```text
Evidence/Bundle_5_SIEM_Mapping/
```
 
Contains:
 
- SIEM integration mapping
- alert escalation strategy
- continuous control monitoring model
 
---
 
## Evidence Bundle 6
Final Audit Report
 
Location:
 
```text
Final_Report/
```
 
Contains:
 
- Executive Summary
- Methodology
- Findings
- Governance Analysis
- Control Monitoring Table
- SIEM Mapping
- Remediation Plan
 
---
 
# Key Findings
 
## W4-F01
Audit subsystem (auditd) installed but not operational.
 
Priority: High
 
---
 
## W4-F02
Logging controls unavailable due to absent journal and authentication logs.
 
Priority: High
 
---
 
## W4-F03
91 security updates pending with associated Lynis vulnerability warnings.
 
Priority: High
 
---
 
## W4-F04
System hardening weaknesses identified by Lynis.
 
Priority: Moderate
 
---
 
## W4-F05
Privileged access activities could not be independently reviewed.
 
Priority: Moderate
 
---
 
# Governance Conclusion
 
The Linux host demonstrated significant deficiencies in audit and logging capability, reducing assurance over privileged activity monitoring and incident investigation.
 
Recommendations focus on:
 
- Restoring auditd functionality
- Establishing centralized log management
- Reducing patch backlog
- Improving hardening posture
- Enhancing continuous monitoring
 
---
 
# Academic Integrity Statement
 
All evidence contained in this repository was generated from activities performed within the authorized ICDFA Ubuntu Practice Hub environment.
 
No command outputs, findings, screenshots, timestamps, or security events were fabricated.
 
This repository is submitted solely for educational assessment purposes.
