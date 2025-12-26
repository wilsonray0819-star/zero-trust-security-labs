# Lab 03 – Network Segmentation and Zero Trust Network Access (ZTNA)

## Objective
Implement Zero Trust network controls by segmenting network access and enforcing application-level connectivity using Zero Trust Network Access (ZTNA) principles.

This lab removes implicit trust from the network and ensures access is granted only after identity, device, and policy verification.

---

## Zero Trust Principle
- Verify explicitly
- Use least privilege access
- Assume breach

This lab focuses on **reducing lateral movement and network attack surface**.

---

## Tools and Technologies
- Azure Virtual Network (VNet)
- Network Security Groups (NSGs)
- Private endpoints
- Zero Trust Network Access (ZTNA) concepts
- Microsoft Entra ID Conditional Access

---

## Network Architecture Overview
- Created segmented network design
- Restricted east-west traffic
- Limited access paths to only required services
- Removed reliance on traditional perimeter security

---

## Network Segmentation
- Implemented subnet-level isolation
- Applied Network Security Groups (NSGs) to control traffic
- Denied unnecessary inbound and outbound access
- Allowed only explicit, policy-based traffic flows

---

## Zero Trust Network Access (ZTNA)
- Enforced identity-aware access to applications
- Eliminated broad network-level access
- Access granted only after:
  - User authentication
  - Device compliance validation
  - Conditional Access policy evaluation

---

## Validation
- Verified restricted network connectivity
- Confirmed blocked lateral movement between segments
- Tested access enforcement using identity-based controls

---

## Outcome
This lab demonstrates the ability to:
- Design secure, segmented networks
- Apply Zero Trust principles at the network layer
- Reduce attack surface and lateral movement risk

---

## Skills Demonstrated
- Network segmentation
- Azure networking fundamentals
- Zero Trust Network Access (ZTNA)
- Security group configuration
- Identity-aware networking

---

## Notes
Screenshots and validation evidence will be added after all lab documentation is complete.
