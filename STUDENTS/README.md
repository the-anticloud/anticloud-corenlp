# Students — CORENLP

**Project:** CORENLP  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/stanfordnlp/CoreNLP  
**Pinned commit:** `e31428cdf39ac13593bb99504d5cd2f8159d342b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b9a144ce847a228516de7767ed5711396a99a6a25cc7cc7cee0dc81bdf366ff8`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e31428cdf39ac13593bb99504d5cd2f8159d342b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b9a144ce847a228516de7767ed5711396a99a6a25cc7cc7cee0dc81bdf366ff8`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
