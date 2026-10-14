# Educators — OPEN_POS

**Project:** OPEN_POS  
**Category:** POS_SYSTEMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `f1f4d12452e5cefa7b3a96c2e3edb114edd31cf2`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `de943978dda82ec3516c7888891c26cdaca7a834030612e6cf86d5d82a5a2368`  
**Date:** October 2026

## Teaching with OPEN_POS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `de943978dda82ec3516c7888891c26cdaca7a834030612e6cf86d5d82a5a2368` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
