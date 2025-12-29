# Lab 05 – Data Protection and Data Loss Prevention (DLP)

## Objective
Implement Zero Trust data protection controls by classifying sensitive data, enforcing Data Loss Prevention (DLP) policies, and validating policy enforcement across Microsoft 365 workloads.

This lab ensures that **data remains protected regardless of user, device, or location**, aligning with Zero Trust principles.

---

## Zero Trust Principles Applied
- Verify explicitly  
- Use least privilege access  
- Assume breach  

This lab focuses on **data as the security boundary**, rather than relying on network-based protections.

---

## Tools and Technologies
- Microsoft Purview
- Data Loss Prevention (DLP)
- Sensitivity Labels
- Microsoft 365 workloads (Exchange, SharePoint, OneDrive)
- Policy monitoring and reporting

---

## Data Classification and Labeling

### Sensitivity Labels
Sensitivity labels were reviewed and configured to support data classification and protection requirements.

Labels provide:
- Clear data classification
- Foundation for DLP enforcement
- Consistent protection across Microsoft 365 services

**Evidence:**  
`01-sensitivity-labels.png`

---

## Data Loss Prevention (DLP) Policy Configuration

### DLP Policies Overview
The DLP policies dashboard was reviewed to confirm:
- DLP is enabled in the tenant
- Policies are available for enforcement
- Microsoft 365 workloads are covered

This establishes a baseline for data protection enforcement.

**Evidence:**  
`02-dlp-policies-overview.png`

---

### Policy Locations and Coverage
DLP policy scope was validated to confirm coverage across supported locations, including:
- Exchange Online
- SharePoint Online
- OneDrive for Business
- Copilot interactions (where applicable)

This ensures sensitive data is protected across collaboration and productivity services.

**Evidence:**  
`03-dlp-policy-locations.png`

---

### Policy Enforcement Mode
Policy enforcement state was validated to confirm:
- DLP policy mode is set to **On**
- Policy synchronization completed successfully
- No configuration or deployment errors are present

This confirms that data protection controls are **actively enforced**, not merely configured.

**Evidence:**  
`04-dlp-policy-enforcement-mode.png`

---

## Validation and Monitoring
Validation was performed using Microsoft Purview dashboards to confirm:
- DLP policies are operational
- Policies are synchronized and enforced
- The environment is prepared for monitoring and future refinement

This aligns with Zero Trust best practices by ensuring visibility and continuous evaluation of data protection controls.

---

## Outcome
This lab demonstrates the ability to:
- Classify and protect sensitive data
- Enforce DLP policies across Microsoft 365 workloads
- Validate active policy enforcement
- Apply Zero Trust principles to data security

---

## Skills Demonstrated
- Data classification and protection
- Microsoft Purview administration
- DLP policy design and validation
- Zero Trust data security controls

---

## Zero Trust Pillar
**Data**

