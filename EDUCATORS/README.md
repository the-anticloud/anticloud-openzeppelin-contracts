# Educators — OPENZEPPELIN_CONTRACTS

**Project:** OPENZEPPELIN_CONTRACTS  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/openzeppelin/openzeppelin-contracts  
**Pinned commit:** `40a51f7e78852e48d0b128d4ee3d620cbc7d35d8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `745d42c4fcc2335db6f85e90b7a687df1c7f2e43e2b3e4b3f79a9f327fa07dfe`  
**Date:** October 2026

## Teaching with OPENZEPPELIN_CONTRACTS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `745d42c4fcc2335db6f85e90b7a687df1c7f2e43e2b3e4b3f79a9f327fa07dfe` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
