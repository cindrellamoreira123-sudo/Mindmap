📌 What This Project Covers (High-Level)

This work focuses on designing and operating a scalable, event-driven activity audit system with strong support for multi-tenancy, reliability, and feature-controlled behavior.

🧠 Core Responsibilities
Activity Audit & Tracing

Capture and trace user and system activities

Distinguish between system-level and tenant-level events

Ensure auditability and compliance across flows

Event-Driven Processing (Kafka)

Publish and consume activity events using Kafka

Design topic strategies for system and tenant events

Implement retries, fan-out processing, and dead-letter handling

Feature Flag–Driven Control

Enable or disable audit flows at runtime

Support company, instance, and cluster-level flags

Ensure consistent behavior across distributed services

Multi-Tenant Data Routing

Route events to the correct tenant or system schema

Support same-database and cross-database tenant setups

Maintain strict tenant isolation

Reliability & Performance

Handle Kafka outages and failure scenarios gracefully

Tune message size and broker configurations

Validate performance through targeted testing

Cross-Team Collaboration

Work closely with platform, performance, and infrastructure teams

Define clear use cases and validation criteria

Document flows for long-term maintainability

