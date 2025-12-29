# Lab 01 – Identity and Conditional Access

## Objective
Implement identity-first security controls using Microsoft Entra ID by configuring multi-factor authentication (MFA), authentication strength, and Conditional Access policies aligned with Zero Trust principles.

## Zero Trust Principles
- Verify explicitly  
- Use least privilege access  
- Assume breach  

## Tools and Technologies
- Microsoft Entra ID (Azure AD)
- Conditional Access
- Multi-Factor Authentication (MFA)
- Authentication Strength Policies

## Configuration Overview
This lab focuses on securing user identity as the primary security control plane. Identity is evaluated continuously and used to determine access decisions based on risk, authentication strength, and policy conditions.

Key configurations include:
- Enabled MFA enforcement for user sign-ins
- Configured authentication strength requirements
- Created Conditional Access policies to:
  - Enforce MFA for cloud applications
  - Restrict access based on sign-in risk
  - Apply policy-based identity protection

## Validation
- Verified MFA enforcement during user sign-in
- Confirmed Conditional Access policy application
- Reviewed sign-in logs for policy evaluation

## Outcome
This lab establishes a secure identity foundation by ensuring all access requests are evaluated using strong authentication and Conditional Access controls. These identity protections serve as the first enforcement layer in the Zero Trust architecture.

## Skills Demonstrated
- Identity security configuration
- Conditional Access policy design
- MFA and authentication strength enforcement

## Related Zero Trust Pillar
**Identity**
