# Enterprise Identity & Modern Workplace Lab
A production-inspired Microsoft enterprise lab demonstrating Hybrid Identity, Microsoft Entra ID, Microsoft Intune, Windows Autopilot, Zero Trust principles, and phishing-resistant passwordless authentication.

Project Overview
This project was designed to simulate a modern enterprise identity and endpoint management environment using Microsoft cloud technologies.

The objective was to gain practical, hands-on experience by designing, deploying, troubleshooting, and documenting a complete Modern Workplace environment rather than simply following implementation guides.

The lab focuses on Microsoft's Zero Trust identity model, secure device management, cloud-native authentication, and enterprise provisioning.
Objectives

![Microsoft Entra](https://img.shields.io/badge/Microsoft-Entra_ID-0078D4)
![Intune](https://img.shields.io/badge/Microsoft-Intune-0078D4)
![Azure](https://img.shields.io/badge/Microsoft-Azure-0089D6)
![Windows Autopilot](https://img.shields.io/badge/Windows-Autopilot-00A4EF)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE)

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
- [x]Microsoft Entra ID
- [x]Active Directory Domain Services
- [x]Microsoft Entra Connect
- [x]Microsoft Cloud Sync

Device Management:
- [x]Microsoft Intune
- [x]Configuration Profiles
- [x]Win32 Applications
- [x]Device Enrollment
- [x]Compliance Policies

Azure:
- [x]Azure Virtual Machines
- [x]Azure Networking
- [x]Azure Bastion
- [x]Public DNS

Authentication:
- [x]Phishing resistant MFA
- [x]Passkeys
- [x]Passwordless Authentication         

Implemented Features

- [x]Hybrid Identity Deployment
- [x]Microsoft Entra Joined Devices
- [x]Windows Autopilot Deployment
- [x]Microsoft Intune Enrollment
- [x]Win32 Application Deployment
- [x]Windows Hello for Business Policy
- [x]Passkey Authentication
- [x]Microsoft Authenticator Passwordless Sign-in
- [x]Azure Bastion Testing
- [x]Device Compliance
- [x]Enterprise Configuration Profiles

# Security & Zero Trust
Implemented Zero Trust principles through:

- [x]Passwordless authentication
- [x]Phishing-resistant MFA
- [x]Enterprise policy enforcement
- [x]Identity-first security model

# Challenges & Troubleshooting

Some notable challenges encountered during the project:

- [x]Azure VM hostname not updating in Microsoft Entra ID due to DNS suffix configuration.
- [x]Windows Hello for Business provisioning limitations over RDP.
- [x]Azure Bastion authentication behavior compared to native RDP.
- [x]Windows Autopilot enrollment resulting in administrative lockout during testing.
- [x]Passkey registration and Microsoft Authenticator passwordless configuration.
- [x]Device registration and Microsoft Intune policy synchronization.

# Lessons Learned

Throughout this project I learned that successful enterprise deployments depend as much on troubleshooting and understanding platform behavior as they do on configuration.

Some of the biggest lessons included:

- [x]Identity is the foundation of the Modern Workplace.
- [x]Microsoft Intune relies heavily on Microsoft Entra ID.
- [x]Passwordless authentication significantly improves security.
- [x]Azure networking and DNS directly influence authentication.
- [x]Zero Trust is an architecture, not a single feature.

# Phase 1 Deliverables

- [x]Microsoft Intune
- [x]Azure Infrastructure
- [x]Windows Autopilot
- [x]Microsoft Entra Joined Devices
- [x]Passwordless Authentication
- [x]Passkeys

# Roadmap - Phase 2
The next phase of this project will expand the environment by implementing additional enterprise identity
and endpoint security capabilities, including:

- [x]Microsoft Graph PowerShell automation
- [x]Advanced Conditional Access policies
- [x]Identity Protection and risk-based policies
- [x]Lifecycle Workflows
- [x]Access Reviews
- [x]Entitlement Management
- [x]Microsoft Defender for Endpoint integration
- [x]Endpoint Analytics
- [x]Intune Security Baselines
- [x]Device Remediation Scripts

Documentation

Complete implementation guide:
📄 Modern Workplace Project Phase1.pdf

# Author
Hanan Tailooni
Technical Support Engineer | Microsoft Entra ID | Microsoft Intune | Identity & Access Management | Microsoft 365
