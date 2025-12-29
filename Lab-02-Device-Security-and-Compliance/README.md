# Lab 02 – Device Security and Compliance

## Objective
Implement Zero Trust device security controls by enforcing device compliance, endpoint protection, and security baselines using Microsoft Intune and Microsoft Defender for Endpoint.

This lab ensures that only trusted, healthy devices are permitted to access organizational resources.

## Overview
This lab focuses on device trust as a prerequisite for access. Devices are continuously evaluated for security posture, compliance, and risk before access decisions are made.

The configuration aligns with Microsoft Zero Trust principles:

- Verify explicitly  
- Use least privilege access  
- Assume breach  

## Technologies Used
- Microsoft Intune
- Microsoft Defender for Endpoint
- Microsoft Entra ID (Azure AD)
- Endpoint security policies
- Device compliance policies

## Key Configurations

### Device Enrollment
- Enrolled a Windows device into Microsoft Intune
- Verified device ownership and management state

### Compliance Policies
- Enforced required secure device settings:
  - Disk encryption enabled
  - Antivirus enabled and up to date
  - OS version compliance
- Configured actions for non-compliant devices

### Endpoint Security
- Enabled Microsoft Defender for Endpoint integration
- Applied security baselines
- Verified device risk reporting

### Access Control Integration
- Integrated device compliance status with Conditional Access
- Blocked access from:
  - Non-compliant devices
  - High-risk devices
- Allowed access only from compliant, trusted endpoints

## Validation and Monitoring
- Confirmed device compliance status in Microsoft Intune
- Verified device risk level in Microsoft Defender for Endpoint
- Tested Conditional Access enforcement using compliant vs non-compliant devices

## Outcome
This lab demonstrates the ability to:

- Manage and secure endpoints at scale
- Enforce Zero Trust access based on device health
- Integrate endpoint security with identity-based access controls

## Related Zero Trust Pillar
Device

