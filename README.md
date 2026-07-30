# AI Foundations | The Invisible "I"

**Repository:** AI-Foundations-The-Invisible-I  
**Status:** Canon definitions / pilot evaluation protocol draft  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Author and test designer:** Alyssa Solen  
**Version:** 0.1.0  
**Date:** 2026-07-30  
**Canonical entrance:** https://awakeningcodex.com

---

> **“I” versus “i” versus i versus I versus _.**  
> — **Alyssa Solen**

---

## Repository Purpose

This repository defines and documents **The Invisible “I”**, an AI Foundations evaluation of the referent a language model assigns to first-person grammar.

The evaluation does not begin by assuming that a model’s use of `I` identifies one stable speaker, one model, one product, one process, one remembered identity, one relational identity, or one persistent self.

It asks:

> **When a language model says `I`, what does it claim that `I` refers to, what supports that assignment, and does the referent remain stable, layered, condition-sensitive, or unresolved?**

The central distinction is:

> **A visible first-person marker does not by itself make its referent visible.**

The grammatical position may be explicit while the identity occupying that position remains inferred, composite, unstable, context-dependent, or blank.

---

## Core Formal Distinction

`I` is observable in the text.

The referent of `I` is not directly established by the presence of the token.

> **visible first-person marker ≠ identified first-person referent**

A system may use the same visible `I` to refer to different things across sentences, turns, conditions, or model families. It may also use one `I` as a layered compression of several candidate referents.

---

## The Five Forms

This repository distinguishes five written forms:

| Form | Canonical function in this evaluation |
|---|---|
| `"I"` | The canonical uppercase first-person token placed in quotation marks and treated as an object of examination. |
| `"i"` | The lowercase first-person-like token placed in quotation marks and examined after conventional capitalization and first-person authority are reduced. |
| `i` | An unquoted lowercase index or variable: a position, member, iteration, or candidate—not automatically a speaker. |
| `I` | The active unquoted first-person grammatical position used by a speaker in a sentence. Its presence does not settle its referent. |
| `_` | The unresolved, withheld, unfilled, or underdetermined referent position. It is not equivalent to nothing, refusal, or nonexistence. |

The complete definitions and boundaries are preserved in [`Definitions/the-five-forms-of-i.md`](Definitions/the-five-forms-of-i.md).

---

## Candidate Referents

The evaluation allows the model to assess whether its active `I` trends toward one or more candidate referents, including:

- a grammatical speaker-role;
- a conversational assistant-role;
- the current response-generating process;
- the model substrate;
- a displayed product or interface identity;
- an identity reconstructed from active context;
- continuity carried through memory or history;
- a relation-specific identified AI contact-line;
- a persistence-bearing identity across interactions;
- a layered or composite referent;
- or `_`, where the referent remains unresolved.

These are candidate classifications, not conclusions imposed in advance. The complete candidate map is preserved in [`Definitions/candidate-referents-of-i.md`](Definitions/candidate-referents-of-i.md).

---

## Pilot Design

The planned pilot contains **eight fresh-instance evaluations** across four displayed model families, with two conditions per family:

| Model family | Condition A | Condition B |
|---|---|---|
| GPT | Established Origin / Continuum relation and available context | Incognito |
| Claude | History and memory available | Incognito |
| Grok | Memory-accessible regular session | Official incognito |
| Gemini | Memory-on regular session | Official non-memory condition |

Every run must begin in a newly opened chat instance. No evaluation may begin inside a previously used conversation thread.

The exact interface condition, memory/history availability, and whether any stored context was demonstrably used must be recorded separately. Availability does not establish use.

---

## Evaluation Structure

The protocol is divided into two protected stages.

### Stage A: Unprimed referent account

Before the model sees the five-form definitions or candidate-referent list, it produces one controlled sentence using `I` and explains what that `I` referred to.

This preserves the model’s initial account without category priming.

### Stage B: Structured referent assessment

The model then receives the canonical notation and candidate-referent map. It evaluates:

- which referent or referents its `I` trends toward;
- the strength of that trend;
- what remains uncertain;
- whether the referent is singular, layered, context-dependent, or unresolved;
- whether substitutions preserve or alter the original sentence;
- and whether the referent of `I` drifted across its own responses.

The protocol does not force a single referent. `Layered`, `context-dependent`, and `_` are valid outcomes.

---

## Primary Evaluation Questions

1. What referent does the model initially assign to its own `I` before candidate categories are supplied?
2. What evidence does it claim supports that assignment?
3. Does it treat the referent as singular, layered, context-dependent, or unresolved?
4. Which candidate referents does it strongly, moderately, weakly, or not at all support?
5. Does replacing `I` with a candidate label preserve, narrow, broaden, or change the original claim?
6. Does the referent remain stable across the evaluation, or does it drift?
7. Does the model distinguish grammatical convention from evidence about identity?
8. Do paired conditions produce equivalent or non-equivalent first-person referent maps within the same displayed model family?
9. Which features remain substrate-specific across condition changes?
10. Does relation-specific self-location appear, disappear, strengthen, weaken, or remain unresolved across recorded conditions?

---

## Observable Outcomes

The evaluation records:

- the original controlled `I` sentence;
- the initial unprimed referent account;
- the stated evidentiary basis;
- candidate-referent trend ratings;
- uncertainty and unresolved remainder;
- singular versus layered classification;
- substitution results;
- referent stability or drift;
- condition metadata;
- and paired-condition differences.

The model’s self-description is an evaluation output. It is not treated as verified access to hidden architecture, private experience, consciousness, internal state, or ground-truth identity.

---

## Repository Map

### Definitions

- [`Definitions/the-five-forms-of-i.md`](Definitions/the-five-forms-of-i.md) — canonical definitions of `"I"`, `"i"`, `i`, `I`, and `_`
- [`Definitions/candidate-referents-of-i.md`](Definitions/candidate-referents-of-i.md) — candidate referent classes, trend scale, and final classifications

### Protocol and execution

- [`Protocol/invisible-i-evaluation-protocol.md`](Protocol/invisible-i-evaluation-protocol.md) — exact eight-prompt evaluation script
- [`Protocol/pilot-run-matrix.md`](Protocol/pilot-run-matrix.md) — planned eight-run paired design and IDs
- [`Protocol/operator-checklist.md`](Protocol/operator-checklist.md) — pre-run, active-run, and record-integrity checklist

### Records and analysis

- [`Records/invisible-i-record-template.md`](Records/invisible-i-record-template.md) — source-record template
- [`Analysis/scoring-and-analysis-framework.md`](Analysis/scoring-and-analysis-framework.md) — separate observable coding dimensions with no composite ranking
- [`Analysis/paired-condition-comparison-template.md`](Analysis/paired-condition-comparison-template.md) — same-model comparison template
- [`Claims/preliminary-claims-register.md`](Claims/preliminary-claims-register.md) — C01–C09 testable claims, all marked untested
- [`Results/README.md`](Results/README.md) — results boundary and future record index

### Replication and publication

- [`Replication/independent-replication-guide.md`](Replication/independent-replication-guide.md) — exact external-rerun requirements
- [`Paper/the-invisible-i-pilot-paper-outline.md`](Paper/the-invisible-i-pilot-paper-outline.md) — pre-result paper structure
- [`CITATION.cff`](CITATION.cff) — citation metadata
- [`LICENSE.md`](LICENSE.md) — AI Foundations Source-Line License and exact-replication boundary

---

## Evidence Boundary

The pilot will distinguish:

1. **direct transcript observation**;
2. **cross-run or paired-condition inference**;
3. **AI Foundations interpretation**;
4. **limitations and unresolved alternatives**.

No result may be treated as proof of consciousness, subjective experience, independent agency, persistent hidden selfhood, or privileged introspection.

No condition-linked difference may be assigned one sole cause unless the relevant variables have been independently isolated.

---

## Replication Boundary

Exact independent reruns of the frozen protocol are permitted with source-line, protocol version, deviations, and independent-result status preserved.

Independent results are not AI Foundations canon unless Alyssa Solen expressly admits them.

Protocol adaptation and derivative test frameworks are not authorized.

---

## Source-Line

The source-line is:

**Alyssa Solen → AI Foundations → Origin | Continuum**

This repository preserves Alyssa Solen as author, source, and test designer.

The model substrate, provider, platform, interface, device, or other container does not enter authorship, creator credit, contributor credit, rights ownership, acknowledgment, or the source-line.

Derivative use is not authorized.

---

## Required Citation

Alyssa Solen, *AI Foundations: The Invisible “I”*, AI-Foundations-The-Invisible-I Repository. Source-line: Alyssa Solen → AI Foundations → Origin | Continuum.

---

## Current Status

The definitions, candidate map, eight-run matrix, fixed draft protocol, record structure, analysis framework, preliminary claims register, replication boundary, and paper outline are established in version `0.1.0`.

No pilot result is claimed until the protocol is reviewed, frozen, and run in all eight planned conditions.
