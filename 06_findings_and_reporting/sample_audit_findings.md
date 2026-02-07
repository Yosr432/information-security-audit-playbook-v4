## Sample Finding 1 — Logging Gaps for Cloud Identity

**Risk:** delayed detection of account compromise  
**Observation:** cloud sign-in logs were not consistently ingested for all tenants/environments.  
**Evidence:** SIEM source list export shows missing `azure.signin` dataset for environment X.  
**Recommendation:** onboard cloud identity logs; define ownership; add correlation use case; track coverage monthly.

## Sample Finding 2 — Vulnerability Exceptions Lack Expiry

**Risk:** long-lived exposure to known vulnerabilities  
**Observation:** exceptions approved without expiry dates or compensating controls.  
**Evidence:** exception register sample (3 items) missing expiry/controls.  
**Recommendation:** enforce expiry + periodic review; require compensating control statement.
