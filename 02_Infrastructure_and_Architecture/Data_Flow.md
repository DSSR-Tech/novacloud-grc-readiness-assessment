# Data Flow

## Project Information

**Project**  
NovaCloud GRC Readiness Assessment

**Client**  
NovaCloud Solutions

**Assessment Type**  
Governance, Risk and Compliance (GRC) Readiness Assessment

## Overview

This document provides an overview of how business information is collected, processed, stored and protected within the NovaCloud Solutions environment.

Understanding these information flows supports asset identification, information classification and the assessment of security controls throughout this engagement.

## Primary Data Flows

The assessment identifies the following primary information flows within the production environment:

| Source | Destination | Purpose |
|--------|-------------|---------|
| Customer | Web Application | User authentication and business operations |
| Web Application | Application Services | Request processing |
| Application Services | Azure SQL Database | Business data storage |
| Application Services | Azure Blob Storage | Document storage |
| Platform Services | Microsoft Sentinel | Security monitoring and event collection |
| Platform Services | Azure Backup | Data protection and recovery |

## Information Processing

Business information follows a defined lifecycle within the platform:

| Stage | Description |
|-------|-------------|
| Collection | Information is received through the SaaS platform. |
| Processing | Business data is validated and processed by the application services. |
| Storage | Data is stored using Azure SQL Database and Azure Blob Storage. |
| Monitoring | Security and operational events are collected for monitoring purposes. |
| Backup | Scheduled backups support data recovery and business continuity. |

## Information Categories

The assessment considers the following categories of information:

- Customer business information
- Personal data
- User identity information
- Application logs
- Audit records

Information classification is documented separately within the Information Classification phase of this engagement.

## Data Protection

The platform includes technical and administrative controls intended to protect business information throughout its lifecycle.

These controls include:

- Encryption in transit
- Encryption at rest
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Centralized monitoring
- Backup and recovery

The effectiveness of these controls is evaluated during the compliance and risk assessment activities.

## Assessment Relevance

Understanding how information moves through the environment provides the context required for asset identification, risk assessment and compliance evaluation throughout this engagement.

## Document Control

| Field | Value |
|-------|-------|
| Document | Data Flow |
| Version | 1.1 |
| Status | Draft |
| Classification | Internal |
| Last Updated | 2026-07-31 |