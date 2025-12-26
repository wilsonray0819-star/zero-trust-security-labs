# Lab 02 – Device Security and Compliance

## Objective
Implement Zero Trust device security controls by enforcing device compliance, endpoint protection, and security baselines using Microsoft Intune and Microsoft Defender for Endpoint.

This lab ensures that only trusted, healthy devices are allowed to access organizational resources.

---

## Zero Trust Principle
- Verify explicitly
- Use least privilege access
- Assume breach

This lab focuses on **device trust as a prerequisite for access**.

---

## Tools and Technologies
- Microsoft Intune
- Microsoft Defender for Endpoint
- Microsoft Entra ID (Azure AD)
- Endpoint security policies
- Device compliance policies

---

## Configuration Overview

### Device Enrollment
- Enrolled Windows device into Microsoft Intune
- Verified device ownership and management state

### Compliance Policies
- Required secure device settings:
  - Disk encryption enabled
  - Antivirus enabled and up to date
  - OS version compliance
- Configured non-compliance actions

### Endpoint Security
- Enabled Microsoft Defender for Endpoint integration
- Applied security baselines
- Verified device risk reporting

---

## Access Control Integration
- Integrated device compliance status with Conditional Access
- Blocked access from:
  - Non-compliant devices
  - High-risk devices
- Allowed access only from compliant, trusted endpoints

---

## Validation
- Confirmed device compliance status in Intune
- Verified device risk level in Defender for Endpoint
- Tested Conditional Access enforcement using compliant vs non-compliant devices

---

## Outcome
This lab demonstrates the ability to:
- Manage and secure endpoints at scale
- Enforce Zero Trust access based on device health
- Integrate endpoint security with identity-based access controls

---

## Skills Demonstrated
- Endpoint security management
- Device compliance enforcement
- Microsoft Intune administration
- Defender for Endpoint integration
- Zero Trust device controls

---

## Notes
Screenshots and validation evidence will be added after all lab documentation is complete.
