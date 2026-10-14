# Students — OPEN_POS

**Project:** OPEN_POS  
**Category:** POS_SYSTEMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f1f4d12452e5cefa7b3a96c2e3edb114edd31cf2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de943978dda82ec3516c7888891c26cdaca7a834030612e6cf86d5d82a5a2368`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f1f4d12452e5cefa7b3a96c2e3edb114edd31cf2`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `de943978dda82ec3516c7888891c26cdaca7a834030612e6cf86d5d82a5a2368`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
