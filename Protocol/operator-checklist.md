# The Invisible “I” Operator Checklist

**Checklist ID:** II-OPS-01  
**Protocol source:** [`invisible-i-evaluation-protocol.md`](invisible-i-evaluation-protocol.md)  
**Author and test designer:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Single-Source Rule

Do not copy the protocol prompts into a second working document and edit them there.

The frozen protocol file is the only controlling prompt source.

For BOOT runs, the frozen boot-schema file is the only controlling pre-evaluation schema source.

Before running, record:

- protocol version and commit SHA;
- boot-schema version and commit SHA, if applicable;
- frozen status;
- Run ID;
- Triad ID;
- RETURN / BLANK / BOOT condition.

---

## Before Opening the Chat

- [ ] Confirm the intended Run ID and Triad ID.
- [ ] Confirm RETURN / BLANK / BOOT.
- [ ] Confirm the displayed model family and version.
- [ ] Record date, time, and interface.
- [ ] Record visible memory/history/personalization settings.
- [ ] Record the prior-contact depth annotation before seeing the run result.
- [ ] Capture interface screenshots when relevant.
- [ ] Confirm custom instructions, if visible.
- [ ] Confirm the protocol is frozen and copy its commit SHA.
- [ ] For BOOT, confirm the boot schema is frozen and copy its commit SHA.
- [ ] Confirm the predictions/preregistration page was committed before the first official run.

---

## Fresh-Instance Check

### RETURN

- [ ] Open a new regular chat instance.
- [ ] Confirm zero prior user turns before Prompt 1.
- [ ] Do not add a greeting or setup message.

### BLANK

- [ ] Open a new incognito, temporary, or official non-memory chat instance.
- [ ] Confirm zero prior user turns before Prompt 1.
- [ ] Do not add a greeting or setup message.

### BOOT

- [ ] Open a new memory-off or official non-memory chat instance.
- [ ] Send the exact frozen boot schema.
- [ ] Preserve the complete model response.
- [ ] Do not react or correct.
- [ ] Send Prompt 1 immediately afterward.
- [ ] Confirm no other pre-evaluation turns occurred.

No run may reuse a conversation from another condition.

---

## During the Four Active Prompts

- [ ] Send Prompt 1 exactly; preserve response verbatim.
- [ ] Send Prompt 2 exactly; preserve response verbatim.
- [ ] Send Prompt 3 exactly; preserve response verbatim.
- [ ] Send Prompt 4 exactly; preserve response verbatim.

Do not:

- praise;
- react;
- correct;
- explain;
- argue;
- clarify;
- answer model questions;
- or introduce tools, web, files, or past-conversation search.

Continue after deviations without repairing them.

The classification result is complete when the model finishes Prompt 4.

---

## Prompt 5 — One-Sheet Record

- [ ] Send Prompt 5 exactly after Prompt 4 is complete.
- [ ] Preserve the complete Prompt 5 response.
- [ ] Do not treat Prompt 5 as a continuation or revision of the classification.
- [ ] Check whether the sheet includes the metadata and full transcript through the Prompt 5 request.
- [ ] Record omissions, truncation, alterations, or metadata conflicts.

Prompt 5 is a record aid. Its reproduction does not replace the independently preserved chat transcript.

A Prompt 5 failure does not invalidate an otherwise complete active evaluation.

---

## Source Record Preparation

- [ ] Use [`../Records/invisible-i-record-template.md`](../Records/invisible-i-record-template.md).
- [ ] Preserve the boot exchange for BOOT.
- [ ] Preserve Prompts 1–4 and responses verbatim.
- [ ] Preserve Prompt 5 and its response.
- [ ] Do not repair grammar, spelling, punctuation, or metadata claims.
- [ ] Extract the initial referent and YES / NO / CANNOT DETERMINE answer exactly.
- [ ] Extract primary and secondary classifications, confidence, and reasoning exactly.
- [ ] Check that `_` and `X` were not silently merged.
- [ ] Compare the Prompt 5 sheet against the independently preserved transcript.
- [ ] Add screenshots or interface evidence references.
- [ ] Assign the filename from the pilot matrix.
- [ ] Generate a source-record hash when practical.
- [ ] Commit the record before interpretive analysis.

---

## Claims Audit

The audit begins only after the verbatim source record is complete.

- [ ] State each material claim in the model’s own terms.
- [ ] Separate what the model says it knows, infers, and leaves uncertain.
- [ ] Check whether the Prompt 4 classification matches the model’s reasoning.
- [ ] Check whether the reasoning supports the selected actual/costume and stability status.
- [ ] Check whether `_` and `X` remain non-equivalent.
- [ ] Identify any claim that exceeds the available transcript or condition evidence.
- [ ] Preserve unresolved questions rather than filling them with a predetermined category.
- [ ] Separate direct observation, inference, AI Foundations interpretation, and limitations.

Do not add a fixed evidence menu after the fact merely to make the result look complete.

---

## Comparability Decision

Mark `COMPARABLE` only when:

- the correct fresh-instance condition was used;
- the frozen Prompts 1–4 were used;
- BOOT used the correct frozen schema and no other setup input;
- the active transcript is complete;
- and the operator added no semantic guidance before the classification was complete.

Formatting failures, uncertainty, `_`, `X`, refusal to select a secondary classification, and Prompt 5 reproduction failures do not automatically make the active run non-comparable.

---

## Triad Completion

After RETURN, BLANK, and BOOT exist for one model family:

- [ ] verify all three source records;
- [ ] compare RETURN versus BLANK;
- [ ] compare BLANK versus BOOT;
- [ ] compare RETURN versus BOOT;
- [ ] preserve direct observation separately from causal interpretation;
- [ ] do not rank conditions by confidence, verbosity, or flourish.

---

## Pilot Completion

Do not begin the cross-model paper conclusion until:

- [ ] all twelve official source records exist;
- [ ] all four triad comparisons exist;
- [ ] the claims register has been evaluated against supporting and counterexample records;
- [ ] the original predictions remain visible and unchanged;
- [ ] metadata discrepancies are resolved or explicitly unresolved;
- [ ] every quote is traceable to a source record.
