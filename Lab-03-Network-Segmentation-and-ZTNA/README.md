## 🔐 Policy Validation and Monitoring (Conditional Access)

To ensure Zero Trust controls were implemented safely and effectively, this lab includes **Conditional Access policy validation** using Microsoft Entra ID reporting.

The Conditional Access policy **CA-Require-Compliant-Windows-Device** was deployed in **Report-only** mode to evaluate enforcement impact without risking user lockout. This allowed real sign-in behavior to be analyzed prior to full enforcement.

### Validation Approach

Using the **Policy impact** view in Microsoft Entra, the following metrics were reviewed:

- Total sign-in activity over time  
- Percentage of sign-ins evaluated by the policy  
- Policy application results in Report-only mode  

This validation step aligns with Zero Trust best practices by:

- Verifying access controls before enforcement  
- Reducing the risk of accidental access disruption  
- Providing measurable insight into policy effectiveness  

Once validated, this policy can be safely transitioned from **Report-only** to **On**, ensuring only compliant Windows devices can access protected resources.

**Evidence:**  
Conditional Access policy impact metrics demonstrating enforcement readiness.

