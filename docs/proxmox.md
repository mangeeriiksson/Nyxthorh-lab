# Proxmox

## Overview

Proxmox serves as the virtualization platform of the Nyxthorh Lab.

It provides the flexibility to deploy, test, rebuild, and maintain services while keeping the underlying infrastructure stable. Virtualization allows the environment to evolve continuously without requiring dedicated hardware for every workload.

The platform enables rapid experimentation while maintaining operational consistency.

---

## Objectives

The virtualization platform supports several long-term objectives:

- Isolate services from one another
- Simplify deployment and maintenance
- Support safe experimentation
- Improve resource utilization
- Enable rapid recovery
- Provide a scalable foundation for future growth

The goal is not to run as many virtual machines as possible, but to create an infrastructure that is reliable, manageable, and easy to expand.

---

## Infrastructure Design

Each workload is deployed with a clearly defined purpose.

Keeping services separated reduces unnecessary dependencies, simplifies troubleshooting, and allows individual systems to be maintained or rebuilt without affecting unrelated services.

This modular approach supports both operational stability and continuous learning.

---

## Change Management

Virtualization makes infrastructure changes significantly less risky.

New services can be introduced, configurations tested, and upgrades evaluated before becoming permanent parts of the environment.

This encourages experimentation while minimizing operational impact.

---

## Recovery Strategy

Recovery is considered an integral part of the platform.

Virtualization enables efficient rollback, migration, and restoration when required.

Rather than relying on complex repair procedures, rebuilding or restoring a workload is often the preferred approach.

---

## Operational Philosophy

Infrastructure should remain predictable.

Every virtual machine should have a defined purpose, clear documentation, and minimal unnecessary dependencies.

Keeping the environment organized makes future growth significantly easier.

---

## Lessons Learned

Virtualization provides much more than hardware consolidation.

It creates an environment where learning becomes safer, changes become less disruptive, and infrastructure can continuously evolve without sacrificing stability.

The ability to rebuild with confidence is one of the platform's greatest strengths.