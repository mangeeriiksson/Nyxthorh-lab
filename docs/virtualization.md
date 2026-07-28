# Virtualization

## Overview

Virtualization is the foundation of the Nyxthorh Lab.

Rather than dedicating physical hardware to individual services, workloads are deployed as virtual machines. This approach provides flexibility, simplifies maintenance, and makes it possible to rebuild services without affecting the entire environment.

The virtualization platform allows the lab to evolve continuously while keeping infrastructure manageable.

---

## Objectives

The virtualization platform is designed to achieve the following goals:

- Efficient hardware utilization
- Isolation between workloads
- Simple deployment of new services
- Safe experimentation
- Easy recovery after failures
- Scalable infrastructure

Virtualization enables services to be treated as independent building blocks instead of permanent installations.

---

## Workload Isolation

Each virtual machine is designed with a clear purpose.

Separating services reduces dependencies between systems and limits the impact of failures, maintenance, or configuration mistakes.

Where practical, workloads remain independent and communicate only when required.

---

## Snapshots and Recovery

One of the greatest advantages of virtualization is the ability to recover quickly.

Snapshots provide a safe way to test configuration changes, evaluate new software, and perform upgrades with the option to return to a known working state if necessary.

Recovery planning is considered an essential part of operating the lab.

---

## Resource Management

Virtual resources are allocated according to the needs of each workload rather than equally across all systems.

This allows critical services to receive appropriate resources while minimizing unnecessary waste.

The infrastructure remains flexible enough to accommodate future expansion.

---

## Operational Philosophy

Virtual machines are considered disposable.

If rebuilding a system becomes easier than repairing it, rebuilding is often the preferred option.

This philosophy encourages better documentation, cleaner deployments, and greater confidence when making changes.

---

## Continuous Evolution

The virtualization platform is expected to change over time.

New services will be introduced, existing systems will be replaced, and architecture will continue to evolve as new technologies are explored.

Virtualization makes this continuous evolution possible without requiring major changes to the underlying infrastructure.