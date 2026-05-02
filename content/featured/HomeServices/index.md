---
date: '4'
title: 'On-Demand Home Services Platform'
github: 'https://github.com/GGBOY626/Home-Services-Platform'
external: 'http://124.223.111.66:8088/user/login'
tech:
  - Java 21
  - Spring Boot 3
  - Spring Security (JWT)
  - MySQL 8
  - React 18 / TypeScript
  - Docker Compose
---

A full-stack home services platform built end-to-end as a personal project — modeling a real operational system rather than a CRUD demo. The platform serves four role-specific frontends (**User**, **Admin**, **Merchant**, **Worker**) with full RBAC, a **9-state order lifecycle state machine** with timeout rollback, and a **payout ledger** that decouples settlement logic from payment channels. Every write operation is logged to an `audit_event` table with a shared `requestId`, enabling full request-chain tracing across services.

**🚀 Try it instantly — no signup, no typing.** All four login pages come pre-filled with demo credentials; just click **Sign in** to explore each role:

- 👤 [User](http://124.223.111.66:8088/user/login) — browse services, place orders, leave reviews
- 🛠️ [Admin](http://124.223.111.66:8088/admin/login) — assign merchants, manage payouts, audit logs
- 🏪 [Merchant](http://124.223.111.66:8088/merchant/login) — accept orders, dispatch workers, view earnings
- 👷 [Worker](http://124.223.111.66:8088/worker/login) — accept jobs, submit completion proof
