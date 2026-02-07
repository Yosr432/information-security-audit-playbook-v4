# Cloud Network Security Audit Program (Azure / AWS / GCP)

## Objective
Assess whether cloud network controls (NSGs, Security Groups, VPC/VNET design) are configured
to restrict unauthorized access, limit lateral movement, and support monitoring requirements.

## In Scope (Typical)
- Azure: Virtual Networks, NSGs, Azure Firewall
- AWS: VPCs, Security Groups, NACLs
- GCP: VPCs, Firewall Rules
- Internet-facing resources
- Connectivity to on‑prem environments

---

## Key Risks
- Overly permissive inbound rules (0.0.0.0/0)
- Weak east–west traffic controls
- Inconsistent rule governance across subscriptions/accounts
- Lack of logging for network traffic
- Shadow cloud networks without security oversight

---

## Control Expectations
- Least-privilege inbound and outbound rules
- Clear separation of tiers (web / app / data)
- Restricted administrative access paths
- Centralized logging of network traffic
- Periodic rule review and ownership

---

## Test Procedures

### 1. Cloud Network Architecture
- Obtain VPC/VNET diagrams
- Validate segmentation between tiers
- Confirm routing and peering controls

### 2. Inbound / Outbound Rules Review
- Export NSG / Security Group rules
- Identify:
  - Any‑Any rules
  - Public exposure of management ports (22/3389)
- Sample 10 high‑risk rules and validate:
  - Business justification
  - Owner
  - Review frequency

### 3. East–West Traffic Controls
- Review default allow rules
- Validate micro‑segmentation where applicable
- Sample traffic paths between sensitive workloads

### 4. Connectivity & Perimeter
- Review VPN / ExpressRoute / Direct Connect
- Validate firewall enforcement at boundaries
- Confirm egress filtering controls

### 5. Logging & Monitoring
- Verify flow logs enabled (NSG Flow Logs, VPC Flow Logs)
- Confirm ingestion into SIEM
- Review sample alerts for anomalous traffic

---

## Evidence Examples
- Cloud network diagrams
- NSG / Security Group exports
- Flow log configuration
- SIEM dashboards (sanitized)

---

## Typical Findings
- Publicly exposed management ports
- Excessive east–west access
- Flow logs not enabled or not monitored
- No periodic review of security group rules
