# Infrastructure Overview

## Project Information

**Project**  
NovaCloud GRC Readiness Assessment

**Client**  
NovaCloud Solutions

**Assessment Type**  
Governance, Risk and Compliance (GRC) Readiness Assessment

## Infrastructure Overview

NovaCloud Solutions delivers its SaaS platform through a cloud-native infrastructure hosted exclusively within Microsoft Azure.

The environment has been designed to support high availability, scalability and centralized security management while meeting the operational requirements of enterprise customers.

The assessment considers the production environment together with the supporting services required to operate, monitor and secure the platform.

## Infrastructure Components

The production environment consists of the following core components:

| Component | Description |
|-----------|-------------|
| Microsoft Azure | Primary cloud platform |
| Microsoft Entra ID | Identity and access management |
| Azure App Service | Application hosting |
| Azure SQL Database | Relational data storage |
| Azure Blob Storage | Document repository |
| Azure Key Vault | Secrets and certificate management |
| Azure Virtual Network | Network segmentation |
| Azure Firewall | Network traffic filtering |
| Azure Monitor | Monitoring and alerting |
| Microsoft Sentinel | Security monitoring and incident detection |
| GitHub Enterprise | Source code management and CI/CD |

## Environment Segmentation

The application lifecycle is supported through separate environments:

- Development
- Testing
- Staging
- Production

Each environment follows defined access controls and change management procedures appropriate to its operational purpose.

## Security Architecture

The infrastructure has been designed according to a defense-in-depth approach.

Security controls include:

- Centralized identity management
- Multi-factor authentication
- Role-based access control
- Network segmentation
- Encryption of data at rest and in transit
- Continuous monitoring
- Centralized logging
- Backup and disaster recovery

Detailed implementation of these controls is assessed throughout the subsequent phases of this engagement.

## Infrastructure Scope

The assessment includes the infrastructure components supporting the delivery of NovaCloud Solutions' SaaS platform.

Customer-managed environments, third-party systems outside the production platform and endpoint devices owned by customers are outside the scope of this engagement.

## Assessment Relevance

The infrastructure described in this document establishes the technical baseline for asset identification, risk assessment and compliance evaluation performed throughout this engagement.

## Document Control

| Field | Value |
|-------|-------|
| Document | Infrastructure Overview |
| Version | 1.1 |
| Status | Draft |
| Classification | Internal |
| Last Updated | 2026-07-24 |