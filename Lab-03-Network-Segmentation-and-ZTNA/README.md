# Lab 03 – Policy Validation and Monitoring (Conditional Access)

## Objective
Validate Conditional Access policies safely using reporting and monitoring features in Microsoft Entra ID to ensure Zero Trust controls are effective prior to enforcement.

## Zero Trust Principles
- Verify explicitly  
- Assume breach  

## Tools and Technologies
- Microsoft Entra ID
- Conditional Access
- Sign-in logs and reporting

## Configuration Overview
The Conditional Access policy **CA-Require-Compliant-Windows-Device** was deployed in **Report-only mode** to evaluate enforcement impact without risking user lockout.

This approach allowed real sign-in behavior to be analyzed before enabling full enforcement.

## Validation Approach
Using the Policy impact view in Microsoft Entra, the following metrics were reviewed:
- Total sign-in activity over time
- Percentage of sign-ins evaluated by the policy
- Policy application results in Report-only mode

## Validation
This validation step aligns with Zero Trust best practices by:
- Verifying access controls before enforcement
- Reducing the risk of accidental access disruption
- Providing measurable insight into policy effectiveness

## Outcome
Once validated, this policy can be safely transitioned from Report-only to **On**, ensuring only compliant Windows devices can access protected resources.

## Skills Demonstrated
- Conditional Access policy validation
- Risk-aware access control
- Zero Trust monitoring and reporting

## Evidence
Conditional Access policy impact metrics demonstrating enforcement readiness.



