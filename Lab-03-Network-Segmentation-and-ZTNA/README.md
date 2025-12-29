## Lab 03 – Policy Validation and Monitoring (Conditional Access)

### Objective
Validate Conditional Access policies safely using Microsoft Entra ID reporting tools to ensure Zero Trust controls function as intended before full enforcement.

This lab focuses on monitoring, analysis, and risk reduction prior to enabling enforcement.

---

### Overview
To prevent accidental user lockout and service disruption, Conditional Access policies should be evaluated in **Report-only mode** before being enforced.

In this lab, the policy:

**CA-Require-Compliant-Windows-Device**

was deployed in Report-only mode to observe real sign-in behavior and measure potential enforcement impact.

This approach aligns with Microsoft Zero Trust guidance:
- Verify explicitly  
- Assume breach  
- Enforce access based on risk and trust signals  

---

### Technologies Used
- Microsoft Entra ID (Azure AD)
- Conditional Access
- Entra Sign-in Logs
- Policy Impact Reporting

---

### Validation Methodology

The following Entra ID reporting views were analyzed:

- **Policy impact**
- **Sign-in logs**
- **Report-only evaluation results**

Metrics reviewed included:
- Total sign-in activity over time
- Percentage of sign-ins evaluated by the policy
- Policy result outcomes if enforcement were enabled

---

### Zero Trust Alignment

This validation process supports Zero Trust principles by:

- Verifying policy behavior before enforcement
- Reducing risk of unintended access disruption
- Ensuring access decisions are based on device compliance signals
- Providing measurable evidence of policy effectiveness

---

### Outcome
The Conditional Access policy was validated successfully in Report-only mode.  
Based on observed impact metrics, the policy can be safely transitioned to **On** to enforce access restrictions requiring compliant Windows devices.

---

### Evidence
- Conditional Access policy impact metrics
- Report-only evaluation results demonstrating enforcement readiness


