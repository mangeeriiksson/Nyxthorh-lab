# Frigate

## Overview

Frigate is used within the Nyxthorh Lab as a self-hosted video surveillance and analytics platform.

The project was introduced to gain practical experience with local video processing while maintaining full control over recorded data and system configuration. Running the platform locally also provides valuable insight into integrating multiple infrastructure components within a self-hosted environment.

The focus extends beyond surveillance itself, placing equal importance on reliability, performance, and operational management.

---

## Objectives

The primary objectives of the Frigate project are to:

- Gain practical experience with self-hosted video analytics.
- Understand the operational requirements of continuous video processing.
- Explore service integration within a larger infrastructure.
- Improve system reliability and performance.
- Support long-term infrastructure management.
- Build experience with maintaining production-like services.

The goal is to understand how video analytics platforms operate as part of a broader infrastructure rather than as isolated applications.

---

## Design

The Frigate environment is designed to operate as an independent service while integrating with other infrastructure components where appropriate.

The architecture prioritises stability, maintainability, and scalability over unnecessary complexity. Individual components are kept loosely coupled, making it easier to perform maintenance, upgrades, or future redesigns without disrupting unrelated services.

The design also reflects the principle that operational simplicity contributes to long-term reliability.

---

## Operational Philosophy

Frigate is treated as a continuously operating service rather than a temporary experiment.

Changes are introduced carefully, documented throughout the implementation process, and reviewed after deployment to ensure that reliability is maintained.

Operational decisions prioritise stability, observability, and maintainability over introducing unnecessary features or complexity.

As with the rest of the lab, the project evolves through continuous refinement rather than complete redesigns.

---

## Lessons Learned

Operating a self-hosted video analytics platform has demonstrated that long-term reliability depends on far more than successful installation.

Performance planning, storage management, service integration, and operational monitoring all play important roles in maintaining a dependable system.

Perhaps the most valuable lesson has been that infrastructure surrounding an application often has a greater impact on its long-term success than the application itself.

Building and maintaining the platform has provided practical experience in designing services that remain reliable while continuing to evolve over time.