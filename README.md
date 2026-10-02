# GRC102 Week 4 Practical Lab: Linux Security Monitoring and Auditing

## Student Information

| Field | Details |
|---------|---------|
| Student | Chioma Ameh |
| Registration Number | C11/26/CGRCE/17567 |
| Course | GRC102 Information Security Governance (Module 4) |
| Environment | ICDFA Ubuntu Practice Hub, host student000302, Ubuntu 24.04.4 LTS |
| Lab Dates | 29-30 September 2026 |

---

## Repository Structure

```text
.
├── README.md
├── report/
│   ├── GRC102_W4_Lab_ChiomaAmeh_C11_26_CGRCE_17567.docx
│   └── GRC102_W4_Lab_ChiomaAmeh_C11_26_CGRCE_17567.pdf
└── evidence/
    ├── EVIDENCE_INDEX.md
    ├── 00_environment/
    ├── 01_auditd/
    ├── 02_logs/
    └── 03_lynis/
```

### Folder Description

| Folder | Contents |
|----------|----------|
| report | Final audit and control assurance report (DOCX and PDF) |
| evidence/00_environment | Figures 1-4 (OS, kernel, user, clock and process limits) |
| evidence/01_auditd | Figures 5-11 (Evidence Bundle 1) |
| evidence/02_logs | Figures 12-14 (Evidence Bundle 2) |
| evidence/03_lynis | Figures 15-31 (Evidence Bundle 3) |
| EVIDENCE_INDEX.md | Figure-by-figure index and SHA-256 checksums |

> Start with the report. All figures are embedded within the report and are also preserved as original screenshots within the evidence folders.

---

## Laboratory Results at a Glance

| Area | Findings |
|---------|---------|
| **auditd (Bundle 1)** | Installed (1:3.1.2-2.1ubuntu0.1) but **not running**. `custom.rules` created with five rules but not loaded. `auditctl -l` returned **Operation not permitted**. No `audit.log` was available; therefore, `ausearch` and `aureport` could not return results. |
| **Logs (Bundle 2)** | `journalctl` found no journal files. `/var/log/auth.log` and `/var/log/syslog` were not present. `wtmp`, `btmp`, `lastlog`, and `faillog` were all 0 bytes. Equivalent sources are documented in Section 3.1 of the report. |
| **Lynis 3.0.9 (Bundle 3)** | Hardening Index **62**, 232 tests performed, **3 warnings**, **43 suggestions**. Major warnings: Vulnerable Packages (PKGS-7392), Fewer Than Two Responsive Nameservers (NETW-2705), and klogd Not Running (LOGG-2138). |
| **Patching** | 91 pending package updates observed on both 29 and 30 September. |
| **Governance (Bundles 4-6)** | Completed control-monitoring table, governance escalation responses, SIEM mapping, finding records W4-F01 through W4-F07, remediation plan, and retesting plan. |

---

## Environment Notes

The assigned Ubuntu practice environment presented several limitations:

- PID 1 was `sleep` rather than `systemd`
- The audit interface refused rule queries
- Logging services were not fully operational
- Process limits affected some later testing activities

All observed errors and limitations were preserved as evidence and analysed as governance findings rather than removed or ignored.

Equivalent evidence sources and alternative methods are documented in Section 3.1 of the final report.

---

## Key Governance Findings

### W4-F01
Audit subsystem installed but not operational.

### W4-F02
Authentication and system logging evidence unavailable.

### W4-F03
Ninety-one pending security updates require remediation.

### W4-F04
System hardening weaknesses identified by Lynis.

### W4-F05
Monitoring controls operating below assurance expectations.

### W4-F06
Logging architecture requires improvement.

### W4-F07
Continuous monitoring maturity requires enhancement.

---

## Evidence Integrity

- Screenshots are original captures from the assigned lab environment.
- Browser address bars remain visible where applicable.
- No screenshots were altered, cropped, recoloured, or edited.
- File names were adjusted only to align with figure numbering.
- Original screenshot names are retained within `EVIDENCE_INDEX.md`.
- SHA-256 checksums are provided for evidence verification.
- No command output, event, timestamp, or finding was fabricated.

---

## Deliverables Included

- Evidence Bundle 1 – Auditd Configuration and Events
- Evidence Bundle 2 – Linux Log Analysis
- Evidence Bundle 3 – Lynis Security Assessment
- Evidence Bundle 4 – Control Monitoring and Governance
- Evidence Bundle 5 – SIEM and Automation Mapping
- Evidence Bundle 6 – Final Audit Report

---

## Declaration

All commands, screenshots, analysis, and findings contained within this repository are based on work completed personally within my assigned ICDFA Ubuntu Practice Hub environment.

AI-assisted tooling was used to help improve formatting, reporting structure, and written explanations. All practical activities, evidence collection, command execution, validation of results, and interpretation of findings were performed by the student.

I can explain and reproduce all commands, findings, recommendations, and governance conclusions contained within this submission.
