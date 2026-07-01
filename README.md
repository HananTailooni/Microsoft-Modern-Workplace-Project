# Enterprise Identity & Modern Workplace Lab
A production-inspired Microsoft enterprise lab demonstrating Hybrid Identity, Microsoft Entra ID, Microsoft Intune, Windows Autopilot, Zero Trust principles, and phishing-resistant passwordless authentication.

Project Overview
This project was designed to simulate a modern enterprise identity and endpoint management environment using Microsoft cloud technologies.

The objective was to gain practical, hands-on experience by designing, deploying, troubleshooting, and documenting a complete Modern Workplace environment rather than simply following implementation guides.

The lab focuses on Microsoft's Zero Trust identity model, secure device management, cloud-native authentication, and enterprise provisioning.
Objectives

# This project demonstrates practical implementation of:

# Solution Archeticture 
                             Microsoft Entra ID
                                      │
               ┌──────────────────────┼──────────────────────┐
               │                      │                      │
        Hybrid Identity         Cloud Native VM      Autopilot Device
        (Hybrid Join)           (Entra Joined)      (User Driven)
               │                      │                      │
     Active Directory         Microsoft Intune     Windows Autopilot
               │                      │                      │
      Entra Connect       Configuration Profiles    Automatic Provisioning
               │                      │                      │
      Password Hash Sync      Win32 Applications      Compliance Policies
               │                      │                      │
      Authentication      Windows Hello for Business   Passkeys
               └──────────────────────┴──────────────────────┘
                              Zero Trust Identity

# Lab Environment
Identity: 
1- Microsoft Entra ID
2- Active Directory Domain Services
3- Microsoft Entra Connect
4- Microsoft Cloud Sync

Device Management:
1- Microsoft Intune
2- Configuration Profiles
3- Win32 Applications
4- Device Enrollment
5- Compliance Policies

Azure:
1- Azure Virtual Machines
2- Azure Networking
3- Azure Bastion
4- Public DNS

Authentication:
1- Phishing resistant MFA
2- Passkeys
3- Passwordless Authentication         

Implemented Features

✅ Hybrid Identity Deployment
✅ Microsoft Entra Joined Devices
✅ Windows Autopilot Deployment
✅ Microsoft Intune Enrollment
✅ Win32 Application Deployment
✅ Windows Hello for Business Policy
✅ Passkey Authentication
✅ Microsoft Authenticator Passwordless Sign-in
✅ Azure Bastion Testing
✅ Device Compliance
✅ Enterprise Configuration Profiles

# Security & Zero Trust
Implemented Zero Trust principles through:

1- Passwordless authentication
2- Phishing-resistant MFA
3- Enterprise policy enforcement
4- Identity-first security model

# Challenges & Troubleshooting

Some notable challenges encountered during the project:

1- Azure VM hostname not updating in Microsoft Entra ID due to DNS suffix configuration.
2- Windows Hello for Business provisioning limitations over RDP.
3- Azure Bastion authentication behavior compared to native RDP.
4- Windows Autopilot enrollment resulting in administrative lockout during testing.
5- Passkey registration and Microsoft Authenticator passwordless configuration.
6- Device registration and Microsoft Intune policy synchronization.

# Lessons Learned

Throughout this project I learned that successful enterprise deployments depend as much on troubleshooting and understanding platform behavior as they do on configuration.

Some of the biggest lessons included:

1- Identity is the foundation of the Modern Workplace.
2- Microsoft Intune relies heavily on Microsoft Entra ID.
3- Passwordless authentication significantly improves security.
4- Azure networking and DNS directly influence authentication.
5- Zero Trust is an architecture, not a single feature.

# Phase 1 Deliverables

1- Microsoft Intune
2- Azure Infrastructure
3- Windows Autopilot
4- Microsoft Entra Joined Devices
5- Passwordless Authentication
6- Passkeys

# Roadmap - Phase 2
The next phase of this project will expand the environment by implementing additional enterprise identity
and endpoint security capabilities, including:

• Microsoft Graph PowerShell automation
• Advanced Conditional Access policies
• Identity Protection and risk-based policies
• Lifecycle Workflows
• Access Reviews
• Entitlement Management
• Microsoft Defender for Endpoint integration
• Endpoint Analytics
• Intune Security Baselines
• Device Remediation Scripts

Documentation

Complete implementation guide:
📄 Modern Workplace Lab – Phase 1 Documentation (PDF)

# Author
Hanan Tailooni
Technical Support Engineer | Microsoft Entra ID | Microsoft Intune | Identity & Access Management | Microsoft 365
