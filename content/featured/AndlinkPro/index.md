---
date: '1'
title: 'AndlinkPro — IoT Gateway & Sync Service'
github: ''
external: ''
tech:
  - Java 8 / Spring Boot
  - Kafka
  - MySQL / Redis
  - Caffeine Cache
  - Scheduled Jobs
---

A telecom-grade IoT gateway service that synchronizes device state, events, and sharing relationships between China Mobile's platform and external IoT systems. Built Kafka-based async event pipelines with retries, stale-event filtering, and batch processing. Introduced config-driven sync control (feature toggles, allowlists, device-type routing) for safe rollout, and optimized performance with Caffeine caching to reduce cross-service lookups under high event load.
