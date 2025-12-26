# Lab 06 – Zero Trust Architecture (End-to-End)

## Objective
Design and document an end-to-end Zero Trust architecture that integrates identity, device, network, application, data, and infrastructure controls into a unified security model.

## Architecture Overview
This lab represents the culmination of Labs 1–5 by tying all security pillars together through a centralized Zero Trust Policy Engine.

The architecture follows Microsoft Zero Trust principles:
- Verify explicitly
- Use least privilege access
- Assume breach

## Core Components

### Identities
- Microsoft Entra ID
- Multi-Factor Authentication (MFA)
- Authentication Strength
- Conditional Access policies

### Devices
- Microsoft Intune device management
- Device compliance policies
- Endpoint security baselines
- Microsoft Defender for Endpoint

### Network
- Network segmentation
- Azure Firewall and NSGs
- Private access controls
- Zero Trust Network Access (ZTNA)

### Applications
- App registration and access control
- OAuth / Modern authentication
- Microsoft Defender for Cloud Apps
- Least privilege app access

### Data
- Data classification
- Sensitivity labels
- Data Loss Prevention (DLP)
- Microsoft Purview

### Infrastructure
- Azure Role-Based Access Control (RBAC)
- Secure configuration management
- Microsoft Defender for Cloud

## Zero Trust Policy Engine
The Zero Trust Policy Engine continuously evaluates signals across identity, device, network, application, and data layers to make real-time access decisions.

Key functions:
- Continuous verification
- Identity, device, and risk evaluation
- Policy decision and enforcement
- Telemetry, signals, and analytics

## Outcome
This lab demonstrates an enterprise-ready Zero Trust architecture aligned with Microsoft security best practices and real-world implementation scenarios.

## Skills Demonstrated
- Zero Trust architecture design
- Identity and access management
- Endpoint and network security
- Cloud security controls
- Security documentation and diagramming
