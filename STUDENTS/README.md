# Students — ARDOUR

**Project:** ARDOUR  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/ardour/ardour  
**Pinned commit:** `bf679081bafabf1bc16ee1f8ae8d01503ffe013e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `37778fcc540e90c4579fd768350b553cb8d9cbfb6d2925b887af0abfb4786a57`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `bf679081bafabf1bc16ee1f8ae8d01503ffe013e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `37778fcc540e90c4579fd768350b553cb8d9cbfb6d2925b887af0abfb4786a57`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
