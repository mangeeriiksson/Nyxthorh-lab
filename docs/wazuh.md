# Wazuh

## Overview

Wazuh serves as the central security monitoring platform within the Nyxthorh Lab.

The platform provides visibility into the environment by collecting, processing, and analysing security-related events from selected systems. It supports the development of practical skills in security monitoring, detection engineering, and incident analysis while operating as part of a broader self-hosted infrastructure.

Rather than focusing on individual alerts, the project aims to improve understanding of how security telemetry can be transformed into meaningful operational insight.

---

## Objectives

The primary objectives of the Wazuh platform are to:

- Develop practical experience with Security Information and Event Management (SIEM).
- Improve understanding of host-based detection and monitoring.
- Explore detection engineering principles.
- Build experience with log analysis and event correlation.
- Strengthen incident investigation skills.
- Support continuous improvement of defensive security capabilities.

The objective is not to generate the largest possible number of alerts, but to produce meaningful visibility into system behaviour.

---

## Design

The monitoring platform is designed around the principle of centralised visibility.

Security-related events from different systems are collected into a common platform where they can be analysed, correlated, and reviewed through a consistent workflow.

The architecture prioritises modularity, allowing monitored systems to evolve independently while maintaining a unified approach to security monitoring.

Detection content, operational workflows, and infrastructure components are continuously refined as experience is gained and new requirements emerge.

---

## Operational Philosophy

Security monitoring is treated as an ongoing operational process rather than a one-time deployment.

Detection logic, alert quality, and operational procedures are reviewed regularly to improve accuracy while reducing unnecessary noise.

The environment is also used to validate architectural decisions and better understand how infrastructure changes influence monitoring and visibility.

Documentation accompanies significant improvements to ensure that design decisions and operational experience remain available for future development.

---

## Lessons Learned

Building and operating a monitoring platform has demonstrated that effective security depends on context rather than alert volume.

Collecting large amounts of telemetry provides little value unless events can be interpreted, prioritised, and investigated efficiently.

One of the most valuable lessons has been that detection engineering is an iterative process. Monitoring improves through continuous refinement, operational feedback, and a deeper understanding of normal system behaviour.

Perhaps the greatest insight has been that successful security monitoring is built on disciplined engineering practices, thoughtful architecture, and continuous learning rather than individual security tools.