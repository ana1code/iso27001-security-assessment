# 🔐 ISO 27001/27002 Security Controls

## 1. Control Mapping

The identified cybersecurity risks were mapped to relevant information security control areas based on ISO 27001 and ISO 27002 principles.

The objective is to identify appropriate security measures that can reduce the likelihood or impact of each risk.

| Risk ID | Risk                      | Security Gap                                      | ISO Control Area    | Recommended Action                                                     |
| ------- | ------------------------- | ------------------------------------------------- | ------------------- | ---------------------------------------------------------------------- |
| R01     | Unauthorized Access       | Excessive or inappropriate access privileges      | Access Control      | Implement MFA, RBAC and periodic access reviews                        |
| R02     | Data Exposure             | Insufficient protection of sensitive information  | Cryptography        | Encrypt sensitive data at rest and in transit                          |
| R03     | Cloud Supplier Compromise | Third-party security risks                        | Supplier Security   | Assess suppliers and define security requirements                      |
| R04     | Malware Infection         | Insufficient preventive and detective controls    | Security Operations | Implement endpoint protection, monitoring and vulnerability management |
| R05     | Service Outage            | Insufficient resilience and recovery capabilities | Business Continuity | Implement redundancy, disaster recovery and recovery procedures        |
| R06     | Data Loss                 | Insufficient backup and recovery controls         | Security Operations | Implement regular backups and test recovery procedures                 |

---

# 2. Access Control

### Risk Addressed

**R01 — Unauthorized Access**

### Security Gap

Unauthorized users or compromised accounts could gain access to systems or information beyond their required responsibilities.

### Recommended Controls

* Multi-factor authentication (MFA)
* Role-Based Access Control (RBAC)
* Least privilege
* Periodic access reviews
* Strong authentication policies
* Privileged account management

### Expected Security Benefit

These controls reduce the probability of unauthorized access and limit the potential impact of compromised accounts.

---

# 3. Cryptography

### Risk Addressed

**R02 — Data Exposure**

### Security Gap

Sensitive business and customer information requires appropriate protection during storage and transmission.

### Recommended Controls

* Encryption at rest
* Encryption in transit
* Secure key management
* Appropriate cryptographic mechanisms

### Expected Security Benefit

Encryption helps protect information against unauthorized disclosure and supports the confidentiality and integrity of sensitive data.

---

# 4. Supplier Security

### Risk Addressed

**R03 — Cloud Supplier Compromise**

### Security Gap

CloudGest depends on external service providers for critical infrastructure and services.

A security incident affecting a supplier could therefore create indirect risks to CloudGest.

### Recommended Controls

* Supplier security assessments
* Security requirements in contracts
* Supplier access management
* Security monitoring
* Periodic supplier reviews
* Defined incident notification requirements

### Expected Security Benefit

Supplier security controls reduce third-party risk and provide greater visibility into the security posture of critical service providers.

---

# 5. Security Operations

### Risk Addressed

**R04 — Malware Infection**

### Security Gap

Malware could compromise endpoints, servers or other systems connected to the organization's environment.

### Recommended Controls

* Endpoint protection
* Security monitoring
* Vulnerability management
* Malware protection
* Security event logging
* Regular system updates

### Expected Security Benefit

These controls improve the organization's ability to prevent, detect and respond to malicious activity.

---

# 6. Business Continuity

### Risk Addressed

**R05 — Service Outage**

### Security Gap

A cyberattack, technical failure or third-party incident could make the platform unavailable.

### Recommended Controls

* Redundant infrastructure
* Disaster recovery procedures
* Recovery objectives
* Availability monitoring
* Business continuity planning
* Periodic recovery testing

### Expected Security Benefit

These measures improve the organization's ability to maintain or restore critical services following a disruptive event.

---

# 7. Backup and Recovery

### Risk Addressed

**R06 — Data Loss**

### Security Gap

Business information could be permanently lost following accidental deletion, system failure, malware or an unsuccessful recovery process.

### Recommended Controls

* Regular backups
* Backup integrity checks
* Offline or isolated backup protection where appropriate
* Recovery testing
* Defined data retention policies
* Restricted backup access

### Expected Security Benefit

A structured backup and recovery strategy reduces the potential impact of data loss and supports business recovery.

---

# 8. Control Prioritization

The controls were prioritized according to their potential impact on the organization's security posture.

| Priority  | Control Area        | Main Objective                |
| --------- | ------------------- | ----------------------------- |
| 🔴 High   | Access Control      | Prevent unauthorized access   |
| 🔴 High   | Cryptography        | Protect sensitive information |
| 🔴 High   | Security Operations | Detect and prevent threats    |
| 🔴 High   | Supplier Security   | Reduce third-party risk       |
| 🟠 Medium | Business Continuity | Maintain critical services    |
| 🟠 Medium | Backup & Recovery   | Recover from data loss        |

---

# 9. Overall Assessment

The assessment demonstrates that security controls should not be implemented independently.

Access control, encryption, monitoring, supplier management, business continuity and recovery mechanisms should operate together as part of an overall information security management approach.

For the CloudGest scenario, priority should initially be given to protecting access to sensitive information, monitoring security events and managing risks introduced by third-party providers.
