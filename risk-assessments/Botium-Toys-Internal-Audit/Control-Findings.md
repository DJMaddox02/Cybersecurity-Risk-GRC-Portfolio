# Control Findings

## 🔴 Urgently Inneffective Controls Identified

🔴 LEAST PRIVILAGE – Not Implemented

Status: Control Missing

Risk: High

Framework Mapping: NIST PR.AC

All employees currently have access to internally stored data including customer information, increasing breach likelihood.

RECOMMENDATION:
Implement role-based access control (RBAC) enforcing least privilege principles.

🔴 DISASTER RECOVERY PLANNING – Not Implemented

Risk Level: High
No disaster recovery plan or backup strategy exists, creating major business continuity risk.

RECOMMENDATION:
Develop tested disaster recovery and backup procedures aligned with NIST Recover function.

🔴 Encryption – Not Implemented

Risk Level: High
Sensitive payment and customer information is stored without encryption.

### Compliance Impact

- PCI-DSS violation risk

- GDPR exposure

RECOMMENDATION:
Encrypt sensitive data at rest and in transit.

## 🟡 Moderately Effective Controls Identified 

🟡 Password Governance – Weak

Risk Level: Moderate 
Password complexity requirements are minimal and no centralized password management exists.

RECOMMENDATION:
Deploy password management solution and enforce strong authentication standards.

## 🟢 Effective Controls Identified

- Firewall configured with security rules

- Antivirus actively monitored

- Physical security controls functioning
