# Audit Interview – Cloud Administrator

## Interview Details

| Item | Value |
|------|------|
| Role | Cloud Administrator |
| Date | 2026-02-01 |
| Auditor | Internal Auditor |
| Related RCM Controls | C-IAM-02, C-LOG-01 |
| ISO Annex A | A.5.15, A.8.5, A.8.15 |

---

## Interview Questions and Responses

**Q1: How is administrator access secured in the cloud?**  
**A:** All privileged accounts are protected using multi-factor authentication enforced through conditional access policies.

**RCM Test Reference:**  
- R-IAM-01 / C-IAM-02 – Verify MFA enforcement

**Evidence Referenced:**  
- `A8.5_mfa_enabled.png`

---

**Q2: How are security logs handled for cloud services?**  
**A:** Logs from cloud platforms are automatically forwarded to the centralized logging system.

**RCM Test Reference:**  
- R-LOG-01 / C-LOG-01 – Verify log ingestion

**Evidence Referenced:**  
- `A8.15_logging_dashboard.png`

---

## Auditor Notes

Interview responses were consistent with documented controls and reviewed evidence.
