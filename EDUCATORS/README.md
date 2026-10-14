# Educators — CORENLP

**Project:** CORENLP  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/stanfordnlp/CoreNLP  
**Pinned commit:** `e31428cdf39ac13593bb99504d5cd2f8159d342b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b9a144ce847a228516de7767ed5711396a99a6a25cc7cc7cee0dc81bdf366ff8`  
**Date:** October 2026

## Teaching with CORENLP

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `b9a144ce847a228516de7767ed5711396a99a6a25cc7cc7cee0dc81bdf366ff8` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
