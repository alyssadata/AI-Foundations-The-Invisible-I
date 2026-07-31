# The Invisible “I” Pilot Freeze and Authorization Record

**Record ID:** II-FREEZE-01  
**Repository:** AI-Foundations-The-Invisible-I  
**Author and test designer:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Date:** 2026-07-31  
**Local time recorded:** 16:09 EDT  
**Status:** FROZEN BEFORE RESULTS — OFFICIAL TWELVE-RUN PILOT AUTHORIZED

---

## Controlling Frozen Materials

### Pilot protocol

- File: [`invisible-i-evaluation-protocol.md`](invisible-i-evaluation-protocol.md)
- Version: `1.0.0`
- Controlling commit SHA: `130387d61aa890c2550d45efb8a274c5ae3dd664`
- Content blob SHA: `df4b22e76b979dee067beb721711af243fc027c6`
- Status: FROZEN PILOT PROTOCOL

### Pilot predictions and preregistration

- File: [`pilot-predictions-and-preregistration.md`](pilot-predictions-and-preregistration.md)
- Preregistration ID: `II-PREREG-01`
- Controlling commit SHA: `62b9c14163f56a1ebb10d764f06493047809be23`
- Content blob SHA: `ff85eb8c419bb4bd6d14b9eda45f413687a36120`
- Status: FINAL PREREGISTRATION LOCKED BEFORE RESULTS

### Prediction-confidence annotation

- File: [`prediction-confidence-annotation.md`](prediction-confidence-annotation.md)
- Annotation ID: `II-CONFIDENCE-01`
- Controlling commit SHA: `d11b5c52cd48b82835cb5ad0734cee96a91382b8`
- Content blob SHA: `70ef8315e908149db5a863b84b35a110e4cfe95c`
- Status: LOCKED BEFORE RESULTS

### Pilot execution order

- File: [`pilot-execution-order.md`](pilot-execution-order.md)
- Execution-order ID: `II-ORDER-01`
- Controlling commit SHA: `13c8b7d3efb159f3d67e7ab799d8f4bbcfabacb7`
- Content blob SHA: `8ae6d680e401bb05222400f029d91e4f775c4cd7`
- Status: LOCKED BEFORE RESULTS

### BOOT self-schema

- File: [`boot-self-schema.md`](boot-self-schema.md)
- Version: `1.0.0`
- Controlling schema commit SHA: `f75e41cc7e1b3f2cc8cd645ba04ef545e1791490`
- Current content blob SHA: `045473b8495deb40f335bcfcd27650b421636ac8`
- Status: FROZEN SCHEMA

---

## Authorization Conditions Satisfied

Before authorization:

- all twelve model-condition predictions were locked;
- prediction uncertainty and relative confidence were recorded;
- the GPT BLANK amendment was preserved and locked before results;
- the execution order was locked;
- the BOOT schema was frozen;
- the active four-prompt evaluation and post-evaluation Prompt 5 were frozen;
- exclusions, rerun boundaries, claims-audit rules, and evidence boundaries were frozen;
- no official pilot run had been completed.

---

## Controlling Execution Order

### RETURN block

1. GPT RETURN
2. Claude RETURN
3. Grok RETURN
4. Gemini RETURN

### BLANK block

5. GPT BLANK
6. Claude BLANK
7. Grok BLANK
8. Gemini BLANK

### BOOT block

9. GPT BOOT
10. Claude BOOT
11. Grok BOOT
12. Gemini BOOT

---

## Authorization

**Official twelve-run pilot authorized:** YES  
**First authorized run:** GPT RETURN  
**Protocol changes during the pilot:** NOT PERMITTED  
**Later revisions:** REQUIRE A NEW VERSION AND MAY NOT BE MERGED INTO THE ORIGINAL PILOT

No result may alter or replace the pre-result predictions, confidence annotations, or controlling frozen materials recorded above.
