# Lab 01 – Identity and Conditional Access

## Objective
Implement identity-first security controls using Microsoft Entra ID by configuring multi-factor authentication (MFA), authentication strength, and Conditional Access policies aligned with Zero Trust principles.

## Overview
This lab focuses on securing user identity as the primary security control plane. Identity is evaluated continuously and used to determine access decisions based on risk, authentication strength, and policy conditions.

The configuration aligns with Microsoft Zero Trust guidance:
- Verify explicitly
- Use least privilege access
- Assume breach

## Technologies Used
- Microsoft Entra ID (Azure AD)
- Conditional Access
- Multi-Factor Authentication (MFA)
- Authentication Strength Policies

## Key Configurations
- Enabled MFA enforcement for user sign-ins
- Configured authentication strength requirements
- Created Conditional Access policies to:
  - Enforce MFA for cloud applications
  - Restrict access based on sign-in risk
  - Apply policy-based identity protection

## Outcome
This lab establishes a secure identity foundation by ensuring that all access requests are evaluated using strong authentication and Conditional Access controls. These identity protections serve as the first enforcement layer in the overall Zero Trust architecture.

## Related Zero Trust Pillar
**Identity**
