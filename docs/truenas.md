# TrueNAS

## Overview

TrueNAS provides the primary storage platform within the Nyxthorh Lab.

It serves as the central location for persistent data, supporting virtual infrastructure, application storage, backups, and shared datasets. Rather than acting as a simple file server, it is a core component that contributes to the overall reliability and maintainability of the environment.

The storage platform is designed to provide consistency, resilience, and flexibility as the lab continues to evolve.

---

## Objectives

The primary objectives of the storage platform are:

- Provide reliable storage for infrastructure services.
- Protect important data against accidental loss.
- Support virtualized workloads.
- Simplify data management.
- Provide a scalable foundation for future growth.

Storage is considered a critical service upon which many other components depend.

---

## Design

The storage platform is designed with separation and organization in mind.

Different types of data are stored independently according to their purpose, making administration simpler while reducing operational complexity.

As new services are introduced, storage requirements are evaluated to ensure that performance, reliability, and maintainability remain balanced.

The objective is to build an environment that remains understandable as it grows.

---

## Operational Philosophy

Storage should remain predictable.

Capacity planning, monitoring, maintenance, and documentation are treated as continuous operational responsibilities rather than occasional tasks.

Changes are introduced carefully to maintain stability while allowing the infrastructure to expand over time.

---

## Lessons Learned

Reliable storage is often overlooked until something fails.

Building the storage platform with long-term reliability in mind has proven far more valuable than focusing solely on capacity or performance.

A well-organized storage environment simplifies administration, improves recovery, and provides confidence as the infrastructure continues to grow.