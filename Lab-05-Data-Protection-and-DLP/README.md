# Lab 05 – Data Protection and Data Loss Prevention (DLP)

## Objective
Implement Zero Trust data protection controls by classifying sensitive data, enforcing Data Loss Prevention (DLP) policies, and monitoring data access and usage across the environment.

This lab ensures that **data remains protected regardless of user, device, or location**.

## Zero Trust Principles
- Verify explicitly  
- Use least privilege access  
- Assume breach  

This lab enforces protection at the **data layer**, independent of identity, device, or network trust.

## Tools and Technologies
- Microsoft Purview
- Data Loss Prevention (DLP)
- Sensitivity Labels
- Microsoft 365 workloads (Exchange, SharePoint, OneDrive, Teams)
- Microsoft Entra ID (Azure AD)

## Data Classification and Labeling

### Sensitivity Labels
- Established a baseline sensitivity labeling framework
- Prepared the environment for data classification and protection
- Ensured labels can be applied consistently across Microsoft 365 workloads

**Screenshot:**  
`01-sensitivity-labels.png`

## DLP Policy Configuration Overview

### DLP Policies Baseline
- Reviewed the DLP policy management interface
- Verified default DLP policy availability
- Confirmed readiness for policy creation and enforcement

**Screenshot:**  
`02-dlp-policies-overview.png`

### Policy Locations and Coverage
- Verified DLP policy coverage across supported locations:
  - Exchange Online
  - SharePoint Online
  - OneDrive for Business
  - Microsoft Teams
- Ensured sensitive data is protected across collaboration and communication services

**Screenshot:**  
`03-dlp-policy-locations.png`

### Policy Enforcement Mode
- Reviewed DLP enforcement configuration
- Confirmed policies can be deployed using monitoring or enforcement modes
- Validated safe rollout capability prior to full enforcement

**Screenshot:**  
`04-dlp-policy-enforcement-mode.png`

## Validation
- Confirmed visibility into sensitive data locations
- Verified DLP policy readiness and scope
- Ensured enforcement modes support staged deployment
- Validated that data protection controls operate independently of network location

## Outcome
This lab demonstrates the ability to:
- Classify and protect sensitive data
- Enforce Zero Trust controls at the data layer
- Monitor data usage and policy effectiveness
- Reduce the risk of data exfiltration and accidental data loss

## Skills Demonstrated
- Data classification and labeling
- DLP policy configuration and validation
- Microsoft Purview administration
- Zero Trust data protection strategy
- Cloud data security controls

## Related Zero Trust Pillar
**Data**


