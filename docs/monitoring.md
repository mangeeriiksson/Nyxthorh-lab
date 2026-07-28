# Monitoring

## Overview

Monitoring is one of the most important capabilities within the Nyxthorh Lab.

Infrastructure cannot be secured if its behaviour is unknown. For that reason, monitoring extends beyond resource utilization and uptime to include security events, network activity, and system health.

The objective is to create an environment where meaningful events can be detected, understood, and investigated.

---

## Objectives

The monitoring platform is designed around several core objectives:

- Maintain visibility across the infrastructure
- Detect abnormal behaviour
- Support incident investigation
- Validate security controls
- Improve operational awareness
- Reduce troubleshooting time

Monitoring is treated as an operational capability rather than a standalone service.

---

## Operational Visibility

Visibility is essential for understanding how systems interact.

Collecting logs, metrics, and security events allows infrastructure to be observed from multiple perspectives rather than relying on isolated information sources.

The more complete the picture, the faster issues can be identified and understood.

---

## Detection

Detection focuses on identifying behaviour that differs from normal operation.

Rather than assuming that systems will never fail or become compromised, the monitoring strategy assumes that unexpected events will eventually occur.

The goal is to identify those events as early as possible and provide sufficient context for investigation.

---

## Correlation

Individual events rarely tell the full story.

Meaningful monitoring combines information from multiple sources to establish relationships between network activity, authentication events, system changes, and security alerts.

Context transforms isolated events into actionable information.

---

## Continuous Improvement

Monitoring is never considered complete.

Detection logic, alert quality, and data sources are continuously reviewed as the infrastructure evolves.

Improving visibility is an ongoing process rather than a finished task.

---

## Design Philosophy

Monitoring should reduce uncertainty.

The purpose is not to generate as many alerts as possible, but to generate alerts that are meaningful, understandable, and actionable.

Good monitoring provides confidence.

Excessive monitoring creates noise.