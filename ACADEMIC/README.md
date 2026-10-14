# Academic Use — OPEN_POS

**Project:** OPEN_POS  
**Category:** POS_SYSTEMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f1f4d12452e5cefa7b3a96c2e3edb114edd31cf2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de943978dda82ec3516c7888891c26cdaca7a834030612e6cf86d5d82a5a2368`  
**Date:** October 2026

## Scope

OPEN_POS is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `f1f4d12452e5cefa7b3a96c2e3edb114edd31cf2`
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
