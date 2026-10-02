# Evidence Index

Every file below is an **unmodified original screenshot** from my assigned ICDFA Ubuntu Practice Hub terminal (host `student000302`), with the browser address bar visible. Figure numbers match the report. Files were only renamed (the original file name is listed) and never edited. The SHA-256 column lets anyone confirm a file has not changed since submission.

Times are the screenshot timestamps from my device (WAT, UTC+1). The VM clock runs on UTC.

---

## Environment Evidence

| Fig | Folder / File | Original File Name | Report Section | Captured (WAT) | What It Shows | SHA-256 |
|------|------|------|------|------|------|------|
| 1 | `evidence/00_environment/Fig01_operating-system-kernel-and-sudo-check_2026-09-30_2146.png` | `Screenshot_2026-09-30_214635.png` | 2 Scope | 30 Sep 2026, 21:46 | Operating system, kernel and sudo check | `f264e76d83cf90cc…` |
| 2 | `evidence/00_environment/Fig02_identity-pid-1-and-var-log-inventory_2026-09-30_2149.png` | `Screenshot_2026-09-30_214921.png` | 2 Scope | 30 Sep 2026, 21:49 | Identity, PID 1 and /var/log inventory | `35f7993ff7928397…` |
| 3 | `evidence/00_environment/Fig03_system-clock-identity-pid-1-and-resource-error_2026-09-30_2201.png` | `Screenshot_2026-09-30_220126.png` | 3 Methodology | 30 Sep 2026, 22:01 | System clock, identity, PID 1 and resource errors | `33578270129fcd11…` |
| 4 | `evidence/00_environment/Fig04_shell-start-up-under-process-limit-errors_2026-09-30_2204.png` | `Screenshot_2026-09-30_220426.png` | 3 Methodology | 30 Sep 2026, 22:04 | Shell start-up under process-limit errors | `5bee08932d8d46e5…` |

---

## Bundle 1 – Auditd Configuration and Events

| Fig | Folder / File | Original File Name | Report Section | Captured (WAT) | What It Shows |
|------|------|------|------|------|------|
| 5 | `evidence/01_auditd/Fig05_auditd-status-check-package-refresh-and-install_2026-09-29_1317.png` | `Screenshot_2026-09-29_131751.png` | 4.1 | 29 Sep 2026, 13:17 | auditd status check, package refresh and install attempt |
| 6 | `evidence/01_auditd/Fig06_auditd-package-and-service-verification_2026-09-29_1328.png` | `Screenshot_2026-09-29_132820.png` | 4.1 | 29 Sep 2026, 13:28 | auditd package and service verification |
| 7 | `evidence/01_auditd/Fig07_auditd-process-check-and-audit-directory-inspection_2026-09-30_1150.png` | `Screenshot_2026-09-30_115007.png` | 4.1 | 30 Sep 2026, 11:50 | auditd process check and audit directory inspection |
| 8 | `evidence/01_auditd/Fig08_custom-audit-rules-restart-attempt-and-loaded_2026-09-29_1341.png` | `Screenshot_2026-09-29_134102.png` | 4.2 | 29 Sep 2026, 13:41 | Custom audit rules, restart attempt and loaded-rule query |
| 9 | `evidence/01_auditd/Fig09_benign-event-generation-activity-1-3_2026-09-30_1124.png` | `Screenshot_2026-09-30_112441.png` | 4.3 | 30 Sep 2026, 11:24 | Benign event generation |
| 10 | `evidence/01_auditd/Fig10_aureport-and-ausearch-attempts_2026-09-30_1126.png` | `Screenshot_2026-09-30_112632.png` | 4.3 | 30 Sep 2026, 11:26 | aureport and ausearch attempts |
| 11 | `evidence/01_auditd/Fig11_ausearch-for-all-three-keys-and-aureport-summaries_2026-09-29_0958.png` | `Screenshot_2026-09-29_095800.png` | 4.3 | 29 Sep 2026, 09:58 | ausearch for all three keys and aureport summaries |

---

## Bundle 2 – Linux Log Analysis

| Fig | Folder / File | Original File Name | Report Section | Captured (WAT) | What It Shows |
|------|------|------|------|------|------|
| 12 | `evidence/02_logs/Fig12_journalctl-review-activity-2-1_2026-09-30_1232.png` | `Screenshot_2026-09-30_123241.png` | 5.1 | 30 Sep 2026, 12:32 | journalctl review |
| 13 | `evidence/02_logs/Fig13_authentication-and-privilege-use-log-review_2026-09-30_1239.png` | `Screenshot_2026-09-30_123938.png` | 5.2 | 30 Sep 2026, 12:39 | Authentication and privilege-use log review |
| 14 | `evidence/02_logs/Fig14_general-system-log-review_2026-09-30_1241.png` | `Screenshot_2026-09-30_124110.png` | 5.3 | 30 Sep 2026, 12:41 | General system log review |

---

## Bundle 3 – Lynis Security Assessment

Figures 15–31 contain:

- Package list refresh
- Lynis installation
- Lynis version verification
- Lynis audit execution
- Hardening index
- Scan completion
- Warnings
- Ports and packages findings
- Networking findings
- Logging findings
- Kernel hardening review
- Suggestions and remediation opportunities

Files are stored in:

```text
evidence/03_lynis/
```

and correspond directly to Figures 15–31 referenced throughout Sections 6.1–6.4 of the report.

---

# Full Checksums

The complete SHA-256 checksum block from the original evidence file should be preserved exactly as generated.

> For repository size and readability, consider leaving the full checksum list in the original document (`Evidence Index.docx`) and storing the Word document in the repository alongside this Markdown file.

---

## Verification

To verify evidence integrity on Linux or macOS:

```bash
cd <repository-root>
shasum -a 256 -c checksums.txt
```

Save the checksum block from the original Evidence Index document into `checksums.txt` before running verification.

---

**Student:** Chioma Ameh  
**
