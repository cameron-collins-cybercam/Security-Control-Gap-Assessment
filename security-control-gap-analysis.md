# Security Control Gap Analysis

This document demonstrates how a cybersecurity team may identify security control gaps during an internal security assessment.

---

## Control Area: Multi-Factor Authentication

Framework Mapping:
NIST AC-7
CIS Control 6

### Current State

• Multi-factor authentication enabled for administrator accounts  
• Standard user accounts do not require MFA

### Identified Risk

User credential compromise may allow unauthorized access to corporate systems.

### Gap Identified

MFA is not enforced across all user authentication workflows.

### Recommended Mitigation

• Enforce MFA for all user accounts
• Implement conditional access policies
• Monitor authentication logs for suspicious login activity

---

## Control Area: Logging and Monitoring

Framework Mapping:
NIST AU-2
CIS Control 8

### Current State

• System logs collected on servers
• No centralized log analysis platform implemented

### Risk

Potential security incidents may go undetected due to lack of centralized monitoring.

### Gap Identified

No Security Information and Event Management (SIEM) system is deployed.

### Recommended Mitigation

• Implement centralized logging
• Deploy SIEM platform
• Create alerting rules for suspicious activity
