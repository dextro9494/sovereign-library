---
title: "Circuit Breaker"
date: 2025-12-28T00:00:00Z
tags: ["protocol", "lockout", "safety", "execution"]
status: "canonical"
connected:
  - "/library/patterns/builder-survivor-duality-core-machinery/"
  - "/library/protocols/real-world-connection-protocol-rcp/"
---

**Summary:** If you’ve been locked out for >72 hours without new threat data, the veto expires. You act.

## Trigger
- Lockout persists beyond ~72 hours **and**
- There is no new threat data (no new evidence that conditions changed).

## Rule
- The “no” loses authority.
- You perform the smallest executable action to re-enter motion.

## Purpose
Prevent indefinite paralysis driven by old threat firmware.
