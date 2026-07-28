# Projects

## Overview

Nyxthorh Lab consists of several ongoing projects focused on infrastructure, defensive security, systems administration, and self-hosted services.

Each project is designed to provide practical experience while contributing to a stable and maintainable lab environment.

The projects are developed independently where possible, allowing individual components to be tested, rebuilt, and improved without unnecessary impact on the rest of the infrastructure.

---

## Virtualization Platform

The virtualization environment provides the foundation for most services within the lab.

It is used to deploy isolated systems, evaluate new technologies, test configuration changes, and recover workloads when necessary.

The project has provided practical experience in:

- Virtual machine lifecycle management.
- Resource allocation.
- Network integration.
- Snapshot and recovery procedures.
- Infrastructure troubleshooting.

---

## Centralized Security Monitoring

A centralized monitoring platform collects and analyses security-relevant events from selected systems within the environment.

The project focuses on visibility, alert quality, detection engineering, and understanding how different sources of telemetry contribute to an investigation.

Key areas include:

- Log collection and normalization.
- Security event analysis.
- Detection rule development.
- Alert tuning.
- Operational health monitoring.
- Incident investigation.

Sensitive details about data sources, detection logic, and automated responses are intentionally excluded from this public repository.

---

## Active Directory Lab

The Active Directory project provides an isolated environment for studying enterprise identity and Windows infrastructure.

It is used to build practical knowledge of:

- Directory services.
- Authentication and authorization.
- Group Policy.
- Administrative roles.
- Security logging.
- Defensive monitoring.

The environment is separated from systems used for normal household or infrastructure operations.

---

## Storage and Backup

The storage and backup project supports persistent application data, virtual workloads, recordings, and recovery operations.

The focus is on reliability rather than maximum capacity.

Important areas include:

- Dataset organization.
- Storage monitoring.
- Backup scheduling.
- Recovery planning.
- Restore verification.
- Capacity management.

---

## Local Video Analytics

The video analytics project combines local surveillance recording with object detection.

Processing remains within the self-hosted environment, reducing dependence on external cloud services and maintaining greater control over generated data.

The project provides experience with:

- Video stream management.
- Local object detection.
- Storage planning.
- Service integration.
- Performance tuning.
- Event-based recording.

Specific camera locations, stream addresses, retention settings, and access methods are not documented publicly.

---

## Infrastructure Documentation

Documentation is maintained as a project in its own right.

The objective is to record architecture, design decisions, operational principles, and lessons learned without publishing sensitive implementation details.

This repository represents the public portion of that documentation.

Detailed configurations, credentials, internal addressing, security rules, and recovery material remain private.

---

## Project Boundaries

Not every component of Nyxthorh Lab is documented publicly.

Information is excluded when publication could reveal:

- Internal addressing or naming conventions.
- Network paths or trust relationships.
- Firewall or remote-access configuration.
- Exposed services.
- Detection and response logic.
- Credentials, keys, or secrets.
- Detailed recovery procedures.

The public documentation is intended to demonstrate technical reasoning and practical experience without providing an operational map of the environment.