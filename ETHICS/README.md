# Ethics — CORENLP

**Project:** CORENLP  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/stanfordnlp/CoreNLP  
**Pinned commit:** `e31428cdf39ac13593bb99504d5cd2f8159d342b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b9a144ce847a228516de7767ed5711396a99a6a25cc7cc7cee0dc81bdf366ff8`  
**Date:** October 2026

## Position

CORENLP is packaged for offline deployment with a verifiable audit trail. The
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
