# Firewall

## Overview

The firewall is the central security component of the Nyxthorh Lab.

Every connection entering, leaving, or moving between network segments is evaluated according to defined security policies. Rather than simply forwarding traffic, the firewall acts as the primary control point for segmentation, monitoring, and access management.

Its purpose is to provide visibility, enforce boundaries, and reduce unnecessary exposure.

---

## Objectives

The firewall is designed to support several long-term goals:

- Protect internal services
- Control communication between network segments
- Minimize exposed attack surfaces
- Support secure remote administration
- Provide detailed logging
- Serve as the foundation for network security

Security decisions are implemented as policy rather than relying on assumptions.

---

## Network Segmentation

Network segmentation is one of the most important security mechanisms within the lab.

Systems are separated according to their purpose, allowing communication only where it is explicitly required.

This reduces the potential impact of compromised systems and makes traffic flows easier to understand and audit.

---

## Traffic Control

Traffic is evaluated using explicit security policies.

Rather than allowing unrestricted communication, access is granted according to operational requirements.

This approach simplifies troubleshooting while maintaining predictable network behaviour.

---

## Monitoring and Visibility

A firewall provides value beyond packet filtering.

Logs, traffic analysis, and security events provide insight into how the environment behaves during both normal operation and unusual situations.

This visibility supports both troubleshooting and security investigations.

---

## Operational Philosophy

Firewall rules should remain understandable.

As environments grow, rule sets naturally become larger.

Regular review and documentation help maintain consistency and reduce unnecessary complexity.

Security policies should evolve together with the infrastructure they protect.

---

## Continuous Improvement

The firewall configuration is expected to evolve continuously.

As new services are introduced and the infrastructure changes, policies are reviewed and adjusted to maintain an appropriate balance between security, usability, and operational simplicity.