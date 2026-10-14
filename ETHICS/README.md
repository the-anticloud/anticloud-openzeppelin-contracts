# Ethics — OPENZEPPELIN_CONTRACTS

**Project:** OPENZEPPELIN_CONTRACTS  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/openzeppelin/openzeppelin-contracts  
**Pinned commit:** `40a51f7e78852e48d0b128d4ee3d620cbc7d35d8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `745d42c4fcc2335db6f85e90b7a687df1c7f2e43e2b3e4b3f79a9f327fa07dfe`  
**Date:** October 2026

## Position

OPENZEPPELIN_CONTRACTS is packaged for offline deployment with a verifiable audit trail. The
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
