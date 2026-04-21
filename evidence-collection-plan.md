# Evidence Collection Plan

**Organisation:** CloudSafe SaaS
**Document:** SOC 2 Type II Evidence Collection Plan
**Version:** 1.0
**Date:** 2025

## Purpose

For a SOC 2 Type II audit the auditor needs to see evidence that
each control operated consistently over the 6-month audit period.
This plan defines what evidence is needed, who collects it,
and how often.

## Evidence Collection Schedule

| Control | Evidence Required | Collector | Frequency | Storage Location |
|---------|-----------------|-----------|-----------|-----------------|
| MFA enforcement | Screenshot of Cognito MFA settings | IT Manager | Monthly | evidence/mfa/ |
| Access reviews | Completed review records signed by manager | IT Manager | Quarterly | evidence/access-reviews/ |
| Vulnerability scanning | Exported scan reports from Inspector | Security Engineer | Monthly | evidence/vuln-scans/ |
| Patch management | Patch completion reports | IT Manager | Monthly | evidence/patches/ |
| Incident log | Running log of all security incidents | CISO | Ongoing | evidence/incidents/ |
| Change management | Change request tickets for all deployments | Engineering Manager | Per deployment | evidence/changes/ |
| Backup testing | Restoration test report | IT Manager | Quarterly | evidence/backup-tests/ |
| Security training | LMS completion reports | HR | Annual + new hires | evidence/training/ |
| Risk assessment | Signed risk assessment document | CISO | Annual | evidence/risk/ |
| Vendor reviews | Completed vendor assessment forms | Procurement | Annual | evidence/vendors/ |
| Board reports | Board meeting minutes referencing security | CISO | Quarterly | evidence/board/ |
| Availability monitoring | Uptime reports from monitoring tool | IT Manager | Monthly | evidence/availability/ |
| Privacy requests | Log of data subject requests handled | Privacy Officer | Ongoing | evidence/privacy/ |

## Evidence Folder Structure

Create the following folders in the repository to store evidence:
