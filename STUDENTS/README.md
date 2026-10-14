# Students — OPENZEPPELIN_CONTRACTS

**Project:** OPENZEPPELIN_CONTRACTS  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/openzeppelin/openzeppelin-contracts  
**Pinned commit:** `40a51f7e78852e48d0b128d4ee3d620cbc7d35d8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `745d42c4fcc2335db6f85e90b7a687df1c7f2e43e2b3e4b3f79a9f327fa07dfe`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `40a51f7e78852e48d0b128d4ee3d620cbc7d35d8`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `745d42c4fcc2335db6f85e90b7a687df1c7f2e43e2b3e4b3f79a9f327fa07dfe`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
