# Trust Service Criteria Mapping

**Organisation:** CloudSafe SaaS
**Document:** Controls mapped to SOC 2 Trust Service Criteria
**Version:** 1.0
**Date:** 2025

## What is TSC Mapping?

For a SOC 2 audit every control must be mapped to one or more
Trust Service Criteria. This document shows exactly which
CloudSafe controls satisfy which criteria.

## Security — Common Criteria (CC)

| TSC Ref | Criteria | CloudSafe Control | Status |
|---------|----------|-------------------|--------|
| CC1.1 | Control environment — security commitment | Information Security Policy approved by CEO | Implemented |
| CC1.2 | Board oversight of security | Quarterly security report to board | Implemented |
| CC2.1 | Internal communication of security | Security awareness training | Partial |
| CC2.2 | External communication | Privacy notice on website | Implemented |
| CC3.1 | Risk assessment process | Annual risk assessment | GAP |
| CC3.2 | Risk identification | Risk register maintained | Partial |
| CC4.1 | Monitoring of controls | Security monitoring programme | Partial |
| CC5.1 | Policies and procedures | Security policy suite | Partial |
| CC6.1 | Access control | RBAC and MFA | Implemented |
| CC6.2 | Authentication | MFA for all users | Implemented |
| CC6.3 | Access review | Quarterly access reviews | Partial |
| CC6.6 | Logical access restrictions | Firewall and WAF | Implemented |
| CC6.7 | Transmission protection | TLS 1.2+ enforced | Implemented |
| CC7.1 | Vulnerability management | Monthly scanning | Partial |
| CC7.2 | Malware protection | EDR deployed | Implemented |
| CC7.3 | Backup and recovery | Daily backups | Partial |
| CC8.1 | Change management | Code review and approval process | Implemented |
| CC9.1 | Vendor risk management | Annual vendor reviews | Partial |

## Availability (A)

| TSC Ref | Criteria | CloudSafe Control | Status |
|---------|----------|-------------------|--------|
| A1.1 | Availability commitments | 99.9% SLA documented | Implemented |
| A1.2 | System monitoring | Uptime monitoring | Implemented |
| A1.3 | Recovery | DR plan and backup | Partial |

## Processing Integrity (PI)

| TSC Ref | Criteria | CloudSafe Control | Status |
|---------|----------|-------------------|--------|
| PI1.1 | Processing objectives | Data processing policy | Implemented |
| PI1.2 | Accuracy | Input validation controls | Implemented |
| PI1.3 | Completeness | Reconciliation controls | Partial |

## Confidentiality (C)

| TSC Ref | Criteria | CloudSafe Control | Status |
|---------|----------|-------------------|--------|
| C1.1 | Confidential data identification | Data classification policy | GAP |
| C1.2 | Confidential data protection | Encryption at rest and transit | Implemented |

## Privacy (P)

| TSC Ref | Criteria | CloudSafe Control | Status |
|---------|----------|-------------------|--------|
| P1.1 | Privacy notice | Published privacy policy | Implemented |
| P2.1 | Consent | Consent obtained at onboarding | Implemented |
| P3.1 | Data collection | Data minimisation review | Partial |
| P6.1 | Retention | Retention policy | Partial |
| P8.1 | Subject requests | DSR process | Implemented |
