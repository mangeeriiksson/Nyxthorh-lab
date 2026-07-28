# OPNsense

## Overview

OPNsense is the core network and security platform of the Nyxthorh Lab.

It provides routing, firewall functionality, network segmentation, secure remote access, and acts as the primary control point between internal infrastructure and external networks.

Rather than being treated as a standalone appliance, OPNsense is integrated into the overall architecture and forms the foundation upon which the rest of the environment operates.

---

## Objectives

The platform is designed to support several long-term objectives:

- Secure network communication.
- Enforce network boundaries.
- Support infrastructure segmentation.
- Provide reliable remote administration.
- Improve network visibility.
- Maintain a stable and predictable environment.

Security should be built into the network rather than added afterwards.

---

## Design

The firewall is designed around layered security.

Traffic is evaluated according to clearly defined policies, while unnecessary communication is minimized wherever practical.

As additional services are introduced into the lab, the firewall architecture evolves alongside the infrastructure without compromising maintainability.

Network security is considered an ongoing engineering task rather than a finished configuration.

---

## Operational Philosophy

A firewall should remain understandable.

Configuration changes are introduced carefully, documented, and reviewed to maintain consistency over time.

Operational simplicity is preferred over unnecessary complexity.

The objective is to build an environment that remains secure while still being practical to administer.

---

## Lessons Learned

A firewall is much more than a collection of rules.

It represents the overall security philosophy of the infrastructure.

Investing time in planning, documentation, and continuous improvement has consistently proven more valuable than simply adding new functionality.