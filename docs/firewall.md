# Firewall

## Overview

The firewall serves as the security boundary of the Nyxthorh Lab.

Rather than simply filtering traffic, it defines how systems communicate, how network boundaries are enforced, and how access is controlled throughout the environment.

Every service deployed within the lab ultimately depends on the firewall to maintain predictable and secure communication.

---

## Purpose

The firewall has four primary responsibilities:

- Protect the infrastructure from unnecessary exposure.
- Enforce separation between different trust levels.
- Control communication between network segments.
- Provide visibility into network activity.

These responsibilities remain the same regardless of how the underlying infrastructure evolves.

---

## Security Philosophy

The firewall is configured around the principle of least privilege.

Traffic is not permitted simply because it exists.

Communication is allowed only when there is a clear operational requirement.

This approach reduces unnecessary attack surface while making traffic flows easier to understand and maintain.

---

## Segmentation

Not every device within the infrastructure should be able to communicate with every other device.

Segmentation creates clear administrative and security boundaries between workloads with different purposes.

By limiting communication paths, the overall resilience of the environment is improved while troubleshooting becomes significantly easier.

---

## Visibility

A firewall should provide more than protection.

It should also provide insight.

Logs and traffic information help explain how the infrastructure behaves during normal operation, making unusual activity easier to identify and investigate.

Security decisions are stronger when they are supported by observable data.

---

## Operational Principles

Firewall policies are expected to evolve.

As new services are introduced and infrastructure changes over time, rules should be reviewed, simplified where possible, and documented.

Maintaining a clean rule base is considered just as important as creating new rules.

---

## Lessons Learned

Building a secure firewall is not about creating the largest possible rule set.

It is about creating policies that remain understandable months later.

Simple, well-documented rules consistently outperform complicated configurations that nobody fully understands.

Security improves when complexity is reduced rather than increased.