## Lab 04 – Application Access and Authentication

### Objective
Implement Zero Trust application access controls by securing cloud applications using modern authentication, Conditional Access policies, and least privilege principles.

This lab demonstrates how applications are protected independently of the network by enforcing identity-aware access decisions before access is granted.

---

### Overview
Traditional security models rely on network location to implicitly trust application access. In a Zero Trust architecture, **applications are protected using identity, authentication strength, and risk signals**, regardless of where the user is connecting from.

In this lab, applications are secured using:
- Modern authentication
- Conditional Access enforcement
- Least privilege access controls

This aligns with Microsoft Zero Trust principles:
- Verify explicitly  
- Use least privilege access  
- Assume breach  

---

### Technologies Used
- Microsoft Entra ID (Azure AD)
- Conditional Access
- OAuth 2.0 / Modern Authentication
- Microsoft Defender for Cloud Apps

---

### Application Security Configuration

#### Modern Authentication
- Enforced modern authentication methods
- Removed legacy authentication where applicable
- Ensured secure token-based authentication flows

#### Conditional Access for Applications
- Required authentication before application access
- Evaluated access based on:
  - User identity
  - Sign-in risk
  - Authentication strength
- Blocked access when conditions were not met

#### Least Privilege Application Access
- Limited application access to only required users
- Prevented over-permissioned access
- Reduced overall application attack surface

---

### Policy Validation and Monitoring

To ensure Conditional Access controls were implemented safely, policies were deployed using **Report-only mode** prior to enforcement.

This allowed real sign-in activity to be evaluated without risking user lockout or service disruption.

#### Validation Steps Performed

**1. Device Compliance Baseline**
- Verified Windows device compliance requirements were defined
- Confirmed compliance policy availability prior to enforcement  
- Evidence: `01-windows-device-compliance-policy.png`

**2. Conditional Access Policy Scope**
- Confirmed policy applied to all users with appropriate exclusions
- Verified all cloud applications were targeted  
- Evidence: `02-conditional-access-policy-scope.png`

**3. Grant Controls (Strong MFA)**
- Required phishing-resistant MFA using authentication strength
- Explicitly excluded SMS-based MFA  
- Evidence: `03-conditional-access-grant-strong-mfa.png`

**4. Policy Deployment State**
- Confirmed policy status set to Report-only
- Validated safe deployment prior to full enforcement  
- Evidence: `04-conditional-access-policy-overview.png`

---

### Zero Trust Alignment
This lab reinforces Zero Trust principles by:

- Verifying access explicitly before application access is granted
- Enforcing strong, phishing-resistant authentication
- Applying identity-based access decisions
- Reducing application risk through least privilege enforcement

---

### Outcome
This lab demonstrates the ability to:

- Secure cloud applications using Zero Trust principles
- Enforce authentication before authorization
- Protect applications using identity-aware access controls
- Validate policies safely prior to enforcement

---

### Skills Demonstrated
- Application access control
- Conditional Access policy design
- Modern authentication concepts
- Least privilege enforcement
- Cloud application security

