# ISO/IEC 27001:2022 Risk & Control Matrix (RCM)

## 1. Document Information

| Field | Value |
|-----|------|
| Organization | [Organization Name] |
| Audit Type | Internal / External |
| Standard | ISO/IEC 27001:2022 |
| Audit Period | [Dates] |
| Prepared By | [Auditor Name] |
| Version | 1.0 |
| Last Updated | [Date] |

---

## 2. RCM Overview

This Risk & Control Matrix (RCM) maps identified information security risks to
ISO/IEC 27001:2022 clauses and Annex A controls.  
It defines control implementation, audit testing procedures, required evidence,
and evaluates control effectiveness.

---

## 3. Risk & Control Matrix

### 3.1 Access Control

| Process / Domain | Access Control |
|----------------|---------------|

| Risk ID | Risk Description | CIA Impact | ISO 27001 Clause | Annex A Control ID | Annex A Control Name | Control Description | Control Type | Frequency | Control Owner | Audit Test Procedure | Evidence Required | Effectiveness | Finding / Gap |
|-------|-----------------|------------|------------------|-------------------|---------------------|--------------------|-------------|-----------|---------------|---------------------|------------------|--------------|---------------|
| R-AC-01 | Unauthorized access to systems | C, I | Clause 6.1.2 | A.5.15 | Access control | Access is granted based on least privilege and management approval | Preventive | Continuous | IT Security | Review access requests and approvals | Access request forms, IAM screenshots |  |  |
| R-AC-02 | Excessive user privileges | C | Clause 6.1.2 | A.5.18 | Access rights | User access rights are reviewed quarterly | Detective | Quarterly | System Owner | Verify access review reports | Access review records |  |  |

---

### 3.2 Identity & Authentication

| Risk ID | Risk Description | CIA Impact | ISO 27001 Clause | Annex A Control ID | Annex A Control Name | Control Description | Control Type | Frequency | Control Owner | Audit Test Procedure | Evidence Required | Effectiveness | Finding / Gap |
|-------|-----------------|------------|------------------|-------------------|---------------------|--------------------|-------------|-----------|---------------|---------------------|------------------|--------------|---------------|
| R-ID-01 | Weak authentication mechanisms | C | Clause 8.2 | A.8.5 | Secure authentication | Multi-factor authentication is enforced | Preventive | Continuous | IT Security | Verify MFA configuration | System configuration screenshots |  |  |

---

### 3.3 Asset Management

| Risk ID | Risk Description | CIA Impact | ISO 27001 Clause | Annex A Control ID | Annex A Control Name | Control Description | Control Type | Frequency | Control Owner | Audit Test Procedure | Evidence Required | Effectiveness | Finding / Gap |
|-------|-----------------|------------|------------------|-------------------|---------------------|--------------------|-------------|-----------|---------------|---------------------|------------------|--------------|---------------|
| R-AM-01 | Unidentified information assets | C, I, A | Clause 8.1 | A.5.9 | Inventory of information | Information assets are inventoried and classified | Preventive | Annual | Asset Owner | Review asset inventory | Asset register |  |  |

---

### 3.4 Backup & Recovery

| Risk ID | Risk Description | CIA Impact | ISO 27001 Clause | Annex A Control ID | Annex A Control Name | Control Description | Control Type | Frequency | Control Owner | Audit Test Procedure | Evidence Required | Effectiveness | Finding / Gap |
|-------|-----------------|------------|------------------|-------------------|---------------------|--------------------|-------------|-----------|---------------|---------------------|------------------|--------------|---------------|
| R-BA-01 | Loss of critical data | A | Clause 8.13 | A.8.13 | Information backup | Daily backups stored securely offsite | Preventive | Daily | IT Operations | Review backup logs and restore test | Backup logs, restore evidence |  |  |

---

### 3.5 Logging & Monitoring

| Risk ID | Risk Description | CIA Impact | ISO 27001 Clause | Annex A Control ID | Annex A Control Name | Control Description | Control Type | Frequency | Control Owner | Audit Test Procedure | Evidence Required | Effectiveness | Finding / Gap |
|-------|-----------------|------------|------------------|-------------------|---------------------|--------------------|-------------|-----------|---------------|---------------------|------------------|--------------|---------------|
| R-LM-01 | Security incidents not detected | C, I | Clause 9.1 | A.8.15 | Logging | Security logs are collected and reviewed | Detective | Continuous | SOC Team | Review log samples | SIEM screenshots |  |  |

---

## 4. Effectiveness Rating Criteria

| Rating | Description |
|------|-------------|
| Effective | Control is implemented and operating as intended |
| Partially Effective | Control exists but has gaps |
| Not Effective | Control not implemented or not working |

---

## 5. Link to Audit Findings

All findings identified in this RCM are documented in:

06_findings_and_reporting/
├── audit_findings_register.md
├── corrective_action_plan.md



---

## 6. Approval

| Role | Name | Signature | Date |
|----|----|-----------|------|
| Lead Auditor |  |  |  |
| ISMS Owner |  |  |  |

