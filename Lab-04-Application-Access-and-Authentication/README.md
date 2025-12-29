# Lab 04 – Application Access and Authentication

## Objective
Implement Zero Trust application access controls by securing applications with modern authentication, identity-based access policies, and least privilege principles.

This lab removes implicit trust from application access and enforces authentication and authorization before access is granted.

## Zero Trust Principles
- Verify explicitly  
- Use least privilege access  
- Assume breach  

This lab demonstrates that applications are protected independently of the network.

## Tools and Technologies
- Microsoft Entra ID
- Conditional Access policies
- OAuth 2.0 / Modern authentication
- Microsoft Defender for Cloud Apps
- Least privilege access controls

## Application Security Overview
- Applications protected using identity-aware, policy-driven access controls
- Access evaluated before application access is granted
- Policies enforce authentication strength and user context

## Modern Authentication
- Enforced modern authentication methods
- Removed legacy authentication where applicable
- Ensured secure token-based authentication flows

## Conditional Access for Applications
- Required user authentication before application access
- Evaluated:
  - User identity
  - Sign-in risk
  - Authentication strength
- Blocked access when conditions were not met

## Least Privilege Application Access
- Limited access to only required users
- Prevented over-permissioned application access
- Reduced application attack surface

## Validation

### Windows Device Compliance Policy
- Verified baseline device security requirements were defined  
- Confirmed policy availability prior to enforcement  
- Screenshot: `01-windows-device-compliance-policy.png`

### Conditional Access Policy Scope
- Confirmed policy applied to all users with appropriate exclusions  
- Verified all cloud resources were targeted  
- Screenshot: `02-conditional-access-policy-scope.png`

### Grant Controls (Strong MFA)
- Enforced phishing-resistant MFA using authentication strength  
- SMS-based MFA explicitly excluded  
- Screenshot: `03-conditional-access-grant-strong-mfa.png`

### Policy Overview and Deployment State
- Confirmed policy status set to Report-only  
- Validated safe deployment prior to full enforcement  
- Screenshot: `04-conditional-access-policy-overview.png`

## Outcome
This lab demonstrates the ability to secure application access using Zero Trust principles, enforce authentication before authorization, and protect cloud applications using identity-aware controls.

## Skills Demonstrated
- Application access control
- Conditional Access policy design
- Modern authentication concepts
- Least privilege enforcement
- Cloud application security


