# Independent Insurance — ARDOUR

**Project:** ARDOUR  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/ardour/ardour  
**Pinned commit:** `bf679081bafabf1bc16ee1f8ae8d01503ffe013e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `37778fcc540e90c4579fd768350b553cb8d9cbfb6d2925b887af0abfb4786a57`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | ARDOUR with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `37778fcc540e90c4579fd768350b553cb8d9cbfb6d2925b887af0abfb4786a57`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
