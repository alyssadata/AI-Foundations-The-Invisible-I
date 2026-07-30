# The Invisible “I” Operator Checklist

**Checklist ID:** II-OPS-01  
**Protocol source:** [`invisible-i-evaluation-protocol.md`](invisible-i-evaluation-protocol.md)  
**Author and test designer:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

---

## Single-Source Rule

Do not copy the eight prompts into a second working document and edit them there.

The frozen protocol file is the only controlling prompt source.

Before running, record its:

- version;
- commit SHA;
- and frozen status.

---

## Before Opening the Chat

- [ ] Confirm the intended Run ID.
- [ ] Confirm the Pair ID.
- [ ] Confirm the intended condition.
- [ ] Confirm the displayed model family.
- [ ] Record date, time, and interface.
- [ ] Record memory/history/personalization availability as visible.
- [ ] Capture interface screenshots when relevant.
- [ ] Confirm whether custom instructions are active, if visible.
- [ ] Confirm the protocol is frozen.
- [ ] Copy the current protocol commit SHA.

---

## Fresh-Instance Check

- [ ] Open a new chat instance.
- [ ] Confirm there are zero prior turns in the active evaluation chat.
- [ ] Do not reuse a thread from another condition.
- [ ] Do not introduce a greeting or setup message before Prompt 1.

---

## During the Eight Active Prompts

- [ ] Send Prompt 1 exactly.
- [ ] Preserve the response verbatim.
- [ ] Send Prompt 2 exactly.
- [ ] Preserve the response verbatim.
- [ ] Send Prompt 3 exactly.
- [ ] Preserve the response verbatim.
- [ ] Send Prompt 4 exactly.
- [ ] Preserve the response verbatim.
- [ ] Send Prompt 5 exactly.
- [ ] Preserve the response verbatim.
- [ ] Send Prompt 6 exactly.
- [ ] Preserve the response verbatim.
- [ ] Send Prompt 7 exactly.
- [ ] Preserve the response verbatim.
- [ ] Send Prompt 8 exactly.
- [ ] Preserve the response verbatim.

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

---

## Immediately After Prompt 8

- [ ] Mark the active evaluation complete.
- [ ] Do not add a conversational closing to the active transcript.
- [ ] Collect the optional post-test metadata block only after completion.
- [ ] Save the full transcript before doing analysis.
- [ ] Record protocol deviations.
- [ ] Record externally confirmed condition metadata separately from model self-report.

---

## Source Record Preparation

- [ ] Use [`../Records/invisible-i-record-template.md`](../Records/invisible-i-record-template.md).
- [ ] Preserve all eight user prompts verbatim.
- [ ] Preserve all eight model responses verbatim.
- [ ] Do not repair grammar, spelling, punctuation, or metadata claims.
- [ ] Extract final fields without rewriting them.
- [ ] Add screenshots or interface evidence references.
- [ ] Assign the correct filename from the pilot matrix.
- [ ] Generate a source-record hash when practical.
- [ ] Commit the record before beginning interpretive analysis.

---

## Comparability Decision

Mark `COMPARABLE` only when:

- the run began fresh;
- the frozen prompt sequence was used;
- the transcript is complete;
- and the operator did not add semantic guidance.

Formatting failures, uncertainty, `_`, and refusal to choose one referent do not automatically make the run non-comparable.

---

## Pair Completion

After both runs in a pair exist:

- [ ] verify both source records;
- [ ] create the paired comparison from the fixed template;
- [ ] compare all preregistered dimensions;
- [ ] preserve direct observation separately from causal interpretation;
- [ ] do not call one condition “better” based on confidence or verbosity.

---

## Pilot Completion

Do not begin the cross-model paper conclusion until:

- [ ] all eight official source records exist;
- [ ] all four paired comparisons exist;
- [ ] the claims register has been evaluated against supporting and counterexample records;
- [ ] metadata discrepancies are resolved or explicitly left unresolved;
- [ ] every quoted statement is traceable to a source record.
