# -My_Botium-Toys-Internal-Security-Audit
Internal security audit for Botium Toys with recommendations and compliance checks

## Table of Contents
1. [Audit Methodology](#audit-methodology)
2. [Audit Findings](#audit-findings)
3. [Recommendations](#recommendations)
4. [Compliance Checklist](#compliance-checklist)
5. [Download the Report](#download-the-report)

---
## Audit Methodology

The audit was conducted using a structured approach with the following steps:

- **Scope Review**: Identified and reviewed all internal systems and assets that are critical to the organization.
- **Control Assessment**: Evaluated technical, administrative, and physical security controls in place.
- **Administrative/Managerial Controls**: Policies and procedures that govern user roles, data management, and system access.
- **Technical Controls**: Software solutions like firewalls, IDS/IPS, and encryption.
- **Physical/Operational Controls**: Locks, surveillance cameras, fire protection systems, etc.
- **Compliance Check**: Ensured that the company adheres to industry regulations, including PCI DSS, GDPR, and SOC.
- **Risk Assessment**: Identified areas of high risk and vulnerability that could be exploited by attackers.
## Audit Findings

Key findings from the audit:

1. **Password Policy Weakness**: Passwords were not enforced to meet industry standards, leading to potential breaches.
2. **Sensitive Data Not Encrypted**: Customer credit card information and other sensitive data were not encrypted.
3. **Lack of Intrusion Detection System (IDS)**: There was no IDS in place to detect suspicious activity in the network.
4. **Insufficient Employee Access Control**: Employees had broader access to systems and data than required for their roles, violating the principle of least privilege.
   ### Severity of Findings
- **Critical**: Encryption and password policies (must be addressed immediately)
- **High**: IDS implementation and access control (address as soon as possible)
- **Medium**: Documentation and compliance procedures (recommended for improvement)
  ## Recommendations

Based on the findings, the following actions are recommended:

### 1. **Technical Controls**
- **Implement Strong Encryption**: Ensure all sensitive data is encrypted both at rest and in transit using industry-standard encryption protocols (e.g., AES-256).
- **Deploy Intrusion Detection System (IDS)**: Set up an IDS to monitor for suspicious activity and potential intrusions in the network.
- **Update Antivirus and Firewall Settings**: Ensure that all systems are protected with updated antivirus software and properly configured firewalls.

### 2. **Administrative Controls**
- **Enhance Password Policy**: Require the use of strong, complex passwords, and implement periodic password changes.
- **Enforce Least Privilege**: Ensure that employees only have access to the data and systems they need to perform their job.

### 3. **Physical Controls**
- **Improve Physical Security**: Implement measures like badge readers, CCTV surveillance, and restricted access to sensitive areas such as server rooms and warehouses.

## Compliance Checklist

The compliance checklist includes industry best practices and regulations that the organization must follow:

- **PCI DSS**: Ensure that only authorized users have access to sensitive cardholder data and that credit card information is processed securely.
- **GDPR**: Make sure all EU customer data is protected, and implement procedures for breach notification within 72 hours.
- **SOC Compliance**: Ensure that user access policies are established and that sensitive data is protected according to industry standards.

A full checklist is available in the [Compliance Checklist](compliance_checklist/Compliance_Checklist.xlsx).
