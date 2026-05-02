---
date: '3'
title: 'Open Platform Gateway'
github: ''
external: ''
tech:
  - Spring Boot Gateway
  - Caffeine Cache
  - Dynamic Routing
  - Multi-region Deployment
---

A pluggable gray-routing domain that extracts factors from request headers (app, province/city, device, phone), applies ratio and whitelist rules with hot-refreshable config, and supports optional Caffeine caching keyed by factors. Built dynamic URI reconstruction (scheme, host, port, path prefix) so a single route can proxy to different region backends based on gray results. The same gray engine powers both cross-region route selection and token validation service selection, keeping routing and auth rules consistent.
