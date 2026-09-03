# 🔎 Risk Assessment

## 1. Assessment Approach

The risk assessment identifies cybersecurity risks that could affect the confidentiality, integrity and availability of CloudGest systems and information.

Each risk is evaluated according to:

* **Likelihood** — the probability of the risk occurring.
* **Impact** — the potential consequence for the organization.
* **Risk Level** — the overall severity resulting from the combination of likelihood and impact.

The assessment is based on the fictional CloudGest environment defined in this project.

---

## 2. Risk Register

| ID  | Risk                      | Likelihood | Impact   | Risk Level  |
| --- | ------------------------- | ---------- | -------- | ----------- |
| R01 | Unauthorized Access       | High       | High     | 🔴 Critical |
| R02 | Data Exposure             | Medium     | Critical | 🔴 Critical |
| R03 | Cloud Supplier Compromise | Medium     | Critical | 🔴 Critical |
| R04 | Malware Infection         | Medium     | High     | 🟠 High     |
| R05 | Service Outage            | Medium     | High     | 🟠 High     |
| R06 | Data Loss                 | Low        | Critical | 🟠 High     |

---

## 3. Risk Analysis

### R01 — Unauthorized Access

**Description**

An attacker or unauthorized user could gain access to CloudGest accounts, applications or systems through compromised credentials or excessive permissions.

**Potential Impact**

* Unauthorized access to business information
* Data modification
* Account compromise
* Loss of customer trust
* Potential regulatory consequences

**Recommended Mitigations**

* Multi-factor authentication (MFA)
* Least privilege
* Role-based access control
* Periodic access reviews
* Strong authentication policies

---

### R02 — Data Exposure

**Description**

Sensitive business or customer information could be exposed through unauthorized access, insecure systems or inadequate protection mechanisms.

**Potential Impact**

* Confidentiality breach
* Exposure of customer information
* Financial and reputational damage
* Potential legal or regulatory consequences

**Recommended Mitigations**

* Encryption at rest
* Encryption in transit
* Access control
* Data classification
* Security monitoring

---

### R03 — Cloud Supplier Compromise

**Description**

A security incident affecting a critical cloud service provider could indirectly impact CloudGest systems or information.

**Potential Impact**

* Unauthorized access
* Service disruption
* Data exposure
* Dependency-related risks
* Business interruption

**Recommended Mitigations**

* Supplier security assessments
* Security requirements in contracts
* Supplier access controls
* Continuous monitoring
* Business continuity planning

---

### R04 — Malware Infection

**Description**

Malware could compromise endpoints, servers or other systems connected to the CloudGest environment.

**Potential Impact**

* System compromise
* Data loss
* Service disruption
* Unauthorized access
* Operational downtime

**Recommended Mitigations**

* Endpoint protection
* Security monitoring
* Vulnerability management
* Network controls
* Regular backups

---

### R05 — Service Outage

**Description**

A technical failure, cyberattack or third-party incident could make the CloudGest platform unavailable.

**Potential Impact**

* Loss of business operations
* Customer disruption
* Financial losses
* Reputational damage

**Recommended Mitigations**

* Redundant infrastructure
* Monitoring and alerting
* Backup systems
* Disaster recovery procedures
* Business continuity planning

---

### R06 — Data Loss

**Description**

Business information could be lost because of accidental deletion, system failure, malware or an unsuccessful recovery process.

**Potential Impact**

* Loss of critical business information
* Operational disruption
* Financial impact
* Customer impact

**Recommended Mitigations**

* Regular backups
* Backup testing
* Recovery procedures
* Access controls
* Data retention policies

---

## 4. Risk Prioritization

The highest-priority risks identified in this assessment are:

1. **Unauthorized Access**
2. **Data Exposure**
3. **Cloud Supplier Compromise**

These risks were prioritized because they could directly affect sensitive information and critical business services.

The organization should address these risks first while continuing to improve its overall security posture.

---

## 5. Risk Treatment Strategy

The recommended approach is to reduce the identified risks through a combination of preventive, detective and corrective security controls.

Examples include:

* Preventive controls — MFA, access control and encryption
* Detective controls — logging, monitoring and alerting
* Corrective controls — incident response, backups and recovery procedures

The risk assessment should be reviewed periodically as the organization's technology, threats and business requirements change.

