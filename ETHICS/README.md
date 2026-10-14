# Ethics — ARDOUR

**Project:** ARDOUR  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/ardour/ardour  
**Pinned commit:** `bf679081bafabf1bc16ee1f8ae8d01503ffe013e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `37778fcc540e90c4579fd768350b553cb8d9cbfb6d2925b887af0abfb4786a57`  
**Date:** October 2026

## Position

ARDOUR is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
