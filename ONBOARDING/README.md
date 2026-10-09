# Onboarding — XBMC

**Project:** XBMC  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/XBMC/xbmc  
**Pinned commit:** `e99bb6a9192c26a8575fb2d16a7247bf49f8fb04`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8c33e7d380b6af41cb132fd13375271ff18230f4322cf229f21863184be6acb9`  
**Date:** October 2026

## First hour

1. Read `README.md` — what the project is and what it measures.
2. Read `ISOLATED_LAB_RESULTS/03_Result_Register.md` — the 16 checks and their
   evidence hashes.
3. Run the suite: `python tools/run_bench.py --out BENCH.json`.
4. Verify a hash: recompute SHA3-256 of a file in `04_Evidence/` and compare.

## First day

- `10_TECHNICAL_HANDOFF` — architecture and interfaces
- `11_TUTORIAL_DEVELOPERS` — build and test
- `18_COMMAND_LINE_INTERFACE` — CLI reference
- `27_DEPENDENCIES` — the offline dependency mirror

## Getting help

lois@0-1.gg · 0-1.gg
