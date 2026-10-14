# Academic Use — XBMC

**Project:** XBMC  
**Category:** CONSUMER_ELECTRONICS  
**Upstream:** https://github.com/XBMC/xbmc  
**Pinned commit:** `e99bb6a9192c26a8575fb2d16a7247bf49f8fb04`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8c33e7d380b6af41cb132fd13375271ff18230f4322cf229f21863184be6acb9`  
**Date:** October 2026

## Scope

XBMC is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `e99bb6a9192c26a8575fb2d16a7247bf49f8fb04`
- The 16-check assurance register with per-check evidence and hashes
- The AIOSS ledger attesting the project artifacts
- Benchmark output in `BENCH.json`

## Reproducing the result

```
python tools/run_bench.py --out BENCH.json
```

Then recompute any row's SHA3-256 from `ISOLATED_LAB_RESULTS/04_Evidence/`.

## Contact

lois@0-1.gg · 0-1.gg
