# Lab 06 – Zero Trust Architecture (End-to-End)

## Objective
Design and document an end-to-end Zero Trust architecture that integrates identity, device, network, application, data, and infrastructure security controls into a centralized, policy-driven security model aligned with Microsoft Zero Trust principles.

## Architecture Overview
This lab represents the culmination of Labs 01–05 by unifying all Zero Trust security pillars through a centralized Zero Trust Policy Engine.

The architecture demonstrates how individual security controls work together to continuously verify trust, enforce least-privilege access, and minimize blast radius across the environment.

## Architecture Pillars
- **Identity:** Conditional Access, MFA, authentication strength, and identity risk evaluation
- **Devices:** Endpoint compliance, device health, and endpoint protection
- **Network:** Network segmentation and Zero Trust Network Access (ZTNA)
- **Applications:** Modern authentication and identity-based access controls
- **Data:** Data classification, sensitivity labels, and Data Loss Prevention (DLP)
- **Infrastructure:** Role-Based Access Control (RBAC) and secure configuration management

## Zero Trust Policy Engine
The Zero Trust Policy Engine continuously evaluates signals such as:
- Identity risk
- Device compliance
- Network context
- Application sensitivity
- Data classification

Access decisions are dynamically enforced based on real-time risk rather than static trust.

## How This Lab Demonstrates Zero Trust
This lab demonstrates a real-world Zero Trust architecture by integrating identity-first security, enforcing least privilege, and assuming breach across all access requests. Each security pillar contributes contextual signals that drive adaptive, policy-based access decisions.

