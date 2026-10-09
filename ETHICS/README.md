# Ethics — XBMC

**Project:** XBMC  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/XBMC/xbmc  
**Pinned commit:** `e99bb6a9192c26a8575fb2d16a7247bf49f8fb04`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8c33e7d380b6af41cb132fd13375271ff18230f4322cf229f21863184be6acb9`  
**Date:** October 2026

## Position

XBMC is packaged for offline deployment with a verifiable audit trail. The
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
