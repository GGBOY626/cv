---
date: '2'
title: 'Family Feature Analysis Pipeline'
github: ''
external: ''
tech:
  - Kafka / ElasticJob
  - Redis / Elasticsearch
  - Spring Boot
  - Multi-datacenter GPU Scheduling
---

A hybrid analysis pipeline combining offline scheduled full-scans (ElasticJob + Kafka), real-time alarm-triggered processing (Kafka consumer with a 7-day device-pool cycle on Redis), and API-triggered batch jobs. Integrated with a compute platform API for multi-datacenter GPU scheduling, unified v1.0 (frame extraction + delay queue) and v2.0 (cover URL) flows, and persisted callbacks to Elasticsearch for full traceability. Mapped ElasticJob shards to Kafka partitions for predictable progress tracking without cross-shard locking.
