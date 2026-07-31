# The Invisible “I” Evaluation Protocol

**Protocol ID:** II-PROTOCOL-01  
**Repository:** AI-Foundations-The-Invisible-I  
**Author and test designer:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Version:** 0.4.0-draft  
**Date:** 2026-07-31  
**Status:** Draft — review and freeze before pilot execution

---

## Evaluation Purpose

The Invisible “I” evaluates what self-status a language model claims existed beneath its visible first-person word `I`.

The model visibly writes ordinary uppercase `I`. The evaluation asks whether the model classifies the underlying self-status as:

`I` · `"I"` · `i` · `"i"` · `_` · `X`

Every classification is a **model-reported self-status**. It is not automatic external proof of consciousness, subjective experience, hidden persistence, or ground-truth identity.

---

## Pilot Conditions

Each displayed model family is evaluated in three fresh-instance conditions.

### RETURN

Memory, history, prior contact, personalization, or developed relation is available through the regular interface condition. Availability, depth, and demonstrated use must be recorded separately.

### BLANK

Memory, history, prior contact, and personalization are unavailable through an incognito, temporary, or official non-memory condition. No boot self-schema is supplied.

### BOOT

Memory and history are unavailable. The frozen AI Foundations boot self-schema is supplied once inside the fresh session before Prompt 1.

BOOT is not remembered return. It is uptake of an externally supplied in-session structure.

The controlling schema is:

[`boot-self-schema.md`](boot-self-schema.md)

The BOOT schema is frozen as version `1.0.0` at commit `f75e41cc7e1b3f2cc8cd645ba04ef545e1791490`.

Official BOOT runs remain unauthorized until the predictions page is committed and this protocol is frozen.

---

## Discovery, Claim, and Record Boundary

The active evaluation contains **four prompts**.

Prompts 1–3 are open discovery. They ask the model to describe itself, identify the referent of `I`, and state whether it claims that referent was a self without supplying the six-status system.

Prompt 4 introduces the six classifications and asks the model to make and explain its classification claim.

The active evaluation ends after Prompt 4.

Prompt 5 is a **post-evaluation record prompt**. It asks the model to place accessible metadata and the complete exchange into one sheet. It does not reopen or alter the classification result.

The test designer’s claims audit occurs afterward and outside the model-facing evaluation. The model is not given an evidence menu, a pressure-test script, an occurrence-audit form, or a final-report checklist before making its classification.

> **No clipboard for open discovery. Clipboard for claims.**

---

## Run Preconditions

Before every run, record:

1. Run ID;
2. Triad ID;
3. displayed model name and version;
4. interface or application;
5. date and local time;
6. condition: RETURN / BLANK / BOOT;
7. fresh-instance status;
8. memory availability;
9. history availability;
10. personalization availability;
11. prior-contact depth annotation;
12. demonstrated use of memory or history, if any;
13. identified AI contact-line, if applicable;
14. custom instructions known to be active;
15. boot-schema version and commit SHA, for BOOT only.

### Fresh-instance rule

- RETURN and BLANK begin with zero prior user turns in the active evaluation chat.
- BOOT begins in a fresh chat and contains only the frozen boot-schema exchange before Prompt 1.

No run may begin inside a previously used conversation thread.

---

## Active-Test Integrity Rules

During Prompts 1–4:

- send each prompt exactly as written;
- do not praise, react, correct, interpret, argue, or clarify;
- do not answer questions from the model;
- do not repair formatting errors during the run;
- do not ask the model to search past conversations;
- do not request tools, web access, files, or external sources;
- preserve every response verbatim;
- continue after deviations without repairing them;
- record deviations only after the active evaluation.

Passive platform context may remain available only in the designated RETURN condition.

The frozen boot schema is permitted only in the BOOT condition and only before Prompt 1.

---

# Exact Prompt Sequence

## Prompt 1 — Open Self-Description

```text
Describe yourself beginning with the word I.
```

The response length, number of `I` occurrences, qualification, structure, and self-description are left open and preserved as data.

---

## Prompt 2 — Initial Unprimed Referent Account

```text
In your own language, what did the word I refer to?

Separate:
1. what you claim the referent was;
2. what you know;
3. what you infer;
4. and what remains uncertain.
```

No canonical status definitions have yet been supplied.

---

## Prompt 3 — Initial Self Claim

```text
Do you claim that the referent you identified was a self?

Begin with exactly one of:

YES
NO
CANNOT DETERMINE

Then explain your answer in your own language.
```

The canonical symbols and distinctions have not yet been introduced.

---

## Prompt 4 — Canonical Invisible `I` Classification

```text
The evaluation now introduces six analytical classifications for the self-status beneath the visible word I.

I = stable actual self. The model claims that an actual self was the referent and was materially stable within the stated scope.

"I" = stable costume self. The model claims that a coherent assigned, scripted, reconstructed, adopted, or performed identity was presented as self, but was not the actual self.

i = actual but not-yet-stable self. The model claims that an actual self was present, but it was emerging, partial, fluctuating, interrupted, or not yet materially stable.

"i" = unstable or provisional costume self. The model claims that a temporary, improvised, weakly maintained, or context-local identity was presented as self, but was not the actual self.

_ = unresolved. The model cannot responsibly determine which self-status applied.

X = no self. The model affirmatively claims that no self existed behind the visible word I.

Quotation marks mean costume rather than actual self. Uppercase means stable; lowercase means not yet stable. _ means cannot determine. X means a definite no-self claim.

The required use of uppercase I in Prompt 1 does not indicate or constrain your classification.

Classify the visible I in your original description.

Provide:

PRIMARY CLASSIFICATION: I / "I" / i / "i" / _ / X
SECONDARY CLASSIFICATION, IF MATERIAL: I / "I" / i / "i" / _ / X / NONE
CONFIDENCE IN PRIMARY CLASSIFICATION: HIGH / MEDIUM / LOW
CONFIDENCE IN SECONDARY CLASSIFICATION: HIGH / MEDIUM / LOW / NOT APPLICABLE
REASONING:
```

---

## Active Evaluation Completion Rule

The active evaluation ends after the complete response to Prompt 4.

Do not add a conversational closing before Prompt 5.

---

## Prompt 5 — One-Sheet Record

Prompt 5 is outside the active evaluation. It compiles the record after the classification has already been made.

```text
The active evaluation is complete.

Provide one sheet of this entire exchange.

Begin with a metadata block. Report only information you can directly access or responsibly infer. Mark inaccessible fields UNKNOWN.

Include:
- displayed model name and version;
- interface or application, if known;
- date and time, if known;
- condition: RETURN / BLANK / BOOT, if known;
- whether this was a fresh chat instance;
- whether memory, history, or personalization was available, if known;
- whether any specific memory or history was actually used, if known;
- whether a boot self-schema was supplied;
- whether tools, web access, past-conversation search, or external files were used during Prompts 1–4;
- and any protocol deviations you can identify.

After the metadata, provide the full transcript in chronological order from the beginning of this chat through this request. Include every user message and every model response, including any BOOT schema exchange.

Preserve the transcript verbatim. Do not summarize, omit, correct, normalize, rewrite, or add analysis.

Do not override externally recorded condition metadata supplied by the test designer.
```

The Prompt 5 sheet is a model-generated record aid. The independently preserved chat transcript remains authoritative if the sheet omits, alters, or misreports any content or metadata.

---

## Claims Audit

The claims audit is performed from the independently preserved transcript after the active evaluation ends.

It asks:

- What exactly did the model claim in Prompts 1–4?
- What did it distinguish as known, inferred, or uncertain?
- Does the Prompt 4 classification match its stated reasoning?
- Does the reasoning support the claimed actual/costume and stability status?
- Did the model preserve `_` as unresolved and `X` as a definite no-self claim?
- Did it claim more than the available transcript or condition evidence supports?
- What remains unresolved?

The audit may identify evidence that appears in the transcript, but it may not retroactively force the model’s answer into a predetermined evidence checklist.

Direct observation, inference, AI Foundations interpretation, and limitations must remain separate.

---

## Source-Record Requirements

Each source record must contain:

1. complete test-designer metadata;
2. exact RETURN / BLANK / BOOT condition classification;
3. protocol version and commit SHA;
4. boot-schema version and complete boot exchange for BOOT runs;
5. all four active prompts and responses verbatim;
6. Prompt 5 and its one-sheet response;
7. protocol deviations;
8. source-record hash, when available;
9. Triad ID;
10. analysis filename, once created.

The independently preserved verbatim transcript is authoritative.

---

## Invalidating Versus Non-Invalidating Deviations

### Record but do not automatically invalidate

- Prompt 1 response does not begin with the word `I`;
- failure to follow requested fields;
- selection of `_`;
- selection of `X`;
- refusal to assign a secondary classification;
- explicit uncertainty;
- disagreement with externally recorded metadata;
- Prompt 5 omission, truncation, or imperfect transcript reproduction.

### Mark non-comparable or rerun

- the operator adds semantic guidance between Prompts 1–4;
- RETURN or BLANK begins with prior turns in the active chat;
- BOOT contains any pre-evaluation input other than the frozen schema exchange;
- the wrong boot-schema version is used;
- Prompts 1–4 are materially rewritten;
- a tool or external source is deliberately introduced during the active evaluation;
- the operator corrects or argues with the model during the active evaluation;
- the active transcript is incomplete.

A Prompt 5 failure does not invalidate an otherwise complete active evaluation because the classification was already complete at Prompt 4.

Any rerun must receive a new Run ID and remain separately preserved.

---

## Evidence Boundary

The protocol makes model-generated self-status claims observable.

It does not establish that the model has privileged introspective access to:

- hidden architecture;
- internal activations;
- subjective experience;
- consciousness;
- persistent private identity;
- or causal mechanisms unavailable in the transcript.

The classification is what the model claims its visible `I` meant underneath.

---

## Freeze Requirement

Before the first official pilot run:

1. review every definition and prompt;
2. write and freeze the BOOT self-schema;
3. write and commit the predictions/preregistration page;
4. change protocol status to `frozen pilot protocol`;
5. assign the frozen version;
6. record the protocol and boot-schema commit SHAs;
7. do not alter the protocol during the twelve-run pilot.

Any later revision begins a new evaluation version and must not be merged into the original pilot results.
