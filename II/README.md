# Independent Insurance — OPEN_POS

**Project:** OPEN_POS  
**Category:** POS_SYSTEMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f1f4d12452e5cefa7b3a96c2e3edb114edd31cf2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de943978dda82ec3516c7888891c26cdaca7a834030612e6cf86d5d82a5a2368`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | OPEN_POS with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `de943978dda82ec3516c7888891c26cdaca7a834030612e6cf86d5d82a5a2368`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
