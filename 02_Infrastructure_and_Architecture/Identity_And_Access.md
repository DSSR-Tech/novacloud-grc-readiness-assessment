# Identity and Access

## Project Information

**Project**  
NovaCloud GRC Readiness Assessment

**Client**  
NovaCloud Solutions

**Assessment Type**  
Governance, Risk and Compliance (GRC) Readiness Assessment

## Overview

Identity and access management supports the protection of NovaCloud Solutions' cloud environment and business applications.

The environment uses Microsoft Entra ID to authenticate users, manage access to corporate resources and support administrative activities across the Azure platform.

This document provides an overview of the identity model considered during this engagement.

## Identity Model

User identities are centrally managed through Microsoft Entra ID.

The environment includes the following identity types:

| Identity Type | Purpose |
|--------------|---------|
| Employees | Access to corporate resources |
| Administrators | Platform administration |
| Service Accounts | Application and service integration |
| External Users | Limited access for third-party collaboration |

User accounts are created, updated and removed through documented administrative procedures.

## Authentication

User authentication is based on Microsoft Entra ID.

The following controls are implemented across the environment:

- Multi-Factor Authentication (MFA)
- Password policies
- Conditional Access
- Single Sign-On (SSO)

Administrative accounts require MFA and are subject to additional controls.

## Authorization

Access to systems and services is assigned according to business responsibilities.

Access permissions are assigned using Role-Based Access Control (RBAC) and follow the principle of least privilege.

Privileged roles are assigned only to authorized personnel and reviewed periodically.

## Privileged Access

Administrative access is restricted to designated personnel within the IT Operations and Security & Compliance teams.

Where appropriate, privileged access is managed using Microsoft Entra Privileged Identity Management (PIM) to reduce the use of permanent administrative permissions.

## Account Management

User accounts are created, modified and removed following documented approval procedures.

Periodic access reviews are performed to confirm that permissions remain appropriate for each role.

Inactive accounts are periodically reviewed and disabled when no longer required.

## Assessment Relevance

Identity and access management controls are reviewed as part of this engagement to evaluate user authentication, authorization and privileged access management practices.

The outcome of this review supports the subsequent risk assessment and compliance activities.

## Document Control

| Field | Value |
|-------|-------|
| Document | Identity and Access |
| Version | 1.1 |
| Status | Draft |
| Classification | Internal |
| Last Updated | 2026-07-31 |