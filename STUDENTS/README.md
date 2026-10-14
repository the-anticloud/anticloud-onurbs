# Students — ONURBS

**Project:** ONURBS  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** see BENCH.json  
**Pinned commit:** `see BENCH.json`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `21d41d164285fb97baef02d17bf9948db3dcd8092f9b23ab96f770e21739a16b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `see BENCH.json`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `21d41d164285fb97baef02d17bf9948db3dcd8092f9b23ab96f770e21739a16b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
