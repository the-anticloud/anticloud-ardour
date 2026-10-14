# Educators — ARDOUR

**Project:** ARDOUR  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/ardour/ardour  
**Pinned commit:** `bf679081bafabf1bc16ee1f8ae8d01503ffe013e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `37778fcc540e90c4579fd768350b553cb8d9cbfb6d2925b887af0abfb4786a57`  
**Date:** October 2026

## Teaching with ARDOUR

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `37778fcc540e90c4579fd768350b553cb8d9cbfb6d2925b887af0abfb4786a57` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
