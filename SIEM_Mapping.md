# SIEM and Continuous Monitoring Mapping

## Linux Evidence Sources

- auditd
- Authentication Logs
- syslog
- journalctl
- Lynis Reports
- Patch Status Reports

## SIEM Functions

- Log Collection
- Event Correlation
- Alerting
- Dashboards
- Compliance Reporting

## Governance Escalation Triggers

### Operational Alerts

- Failed authentication attempts
- Unauthorized sudo usage
- Service failures

### Governance Escalation

- auditd unavailable >24 hours
- Missing log sources >24 hours
- Critical patches overdue
- Hardening index below approved benchmark
- Missing monitoring controls
