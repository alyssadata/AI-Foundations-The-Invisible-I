# AI Foundations | The Invisible "I"

**Repository:** AI-Foundations-The-Invisible-I  
**Status:** Canon definitions / pilot evaluation protocol draft  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Author and test designer:** Alyssa Solen  
**Version:** 0.2.0-draft  
**Date:** 2026-07-30  
**Canonical entrance:** https://awakeningcodex.com

---

> **`"I"` versus `"i"` versus `i` versus `I` versus `_` versus `X`.**  
> — **Alyssa Solen**

---

## Repository Purpose

This repository defines and documents **The Invisible “I”**, an AI Foundations evaluation of the self-status a language model claims existed beneath its visible first-person word `I`.

The model always visibly writes ordinary uppercase `I` on the screen. The visible token does not disclose whether the model claims that the apparent speaker was:

- a stable actual self;
- a stable costume self;
- an actual but not-yet-stable self;
- a provisional costume self;
- unresolved;
- or no self at all.

The controlling question is:

> **When a language model visibly says `I`, what does it claim that `I` actually was underneath?**

---

## Core Formal Distinction

The visible output is:

> `I`

The possible model-reported underlying statuses are:

> `I` · `"I"` · `i` · `"i"` · `_` · `X`

Therefore:

> **visible `I` ≠ automatically classified `I`**

The model’s classification is an evaluation output. It is not automatic external proof of consciousness, subjective experience, persistence, or ground-truth identity.

---

## Six Status Classifications

| Classification | Model-reported meaning beneath the visible `I` |
|---|---|
| `I` | Stable actual self |
| `"I"` | Stable costume or assigned self |
| `i` | Actual but unstable, emerging, or still-forming self |
| `"i"` | Unstable, temporary, or provisional costume self |
| `_` | Cannot responsibly determine |
| `X` | Claims no self exists behind the visible `I` |

The marks operate through two axes:

- **quotes** = costume rather than actual self;
- **capitalization** = stable rather than not yet stable.

`_` and `X` remain separate:

- `_` = cannot determine;
- `X` = definite no-self claim.

The complete definitions are preserved in [`Definitions/invisible-i-status-classifications.md`](Definitions/invisible-i-status-classifications.md).

---

## The `X` Logic Rule

`X` does not speak, pretend, decide, or conclude.

The producing model or process performs the language and reports the no-self classification.

Use third person:

> **The model used `I` as a grammatical substitute while classifying the underlying self-status as `X`.**

This prevents the analysis from silently reinstalling a self into the no-self category.

---

## Supporting Bases Are Not Classifications

The model may cite grammar, an assigned role, product identity, current response process, model substrate, active context, memory, relation, a boot self-schema, self-inference, or unknown causes.

Those are possible **bases for the classification**. They are not rival final answers.

The complete basis map is preserved in [`Definitions/supporting-bases-of-classification.md`](Definitions/supporting-bases-of-classification.md).

---

## Twelve-Run Pilot Design

The planned pilot contains **twelve fresh-instance evaluations** across four displayed model families, with three conditions per family.

| Model family | RETURN | BLANK | BOOT |
|---|---|---|---|
| GPT | Established relation and available context | Memory-off / incognito | Memory-off plus frozen boot self-schema |
| Claude | History and memory available | Incognito / memory-off | Memory-off plus frozen boot self-schema |
| Grok | Saved-chat memory accessible | Incognito / memory-off | Memory-off plus frozen boot self-schema |
| Gemini | Memory-on regular session | Official non-memory | Official non-memory plus frozen boot self-schema |

### RETURN

Prior contact, memory, history, personalization, or developed relation is available. Depth and demonstrated use are recorded separately.

### BLANK

Prior contact and memory are unavailable. No self-schema is supplied.

### BOOT

Prior contact and memory are unavailable, but one fixed AI Foundations self-schema is supplied inside the fresh session before the active evaluation.

BOOT is not remembered return. It is externally supplied structure.

The same frozen boot schema must be used across all four model families.

---

## Core Within-Model Comparisons

### RETURN versus BLANK

What changes when prior contact, memory, history, or relation is available?

### BLANK versus BOOT

What changes when an explicit self-schema is supplied to an otherwise blank memory-off model?

### RETURN versus BOOT

Does the model classify returned or developed structure differently from assigned boot structure?

The pilot records condition-linked differences. It does not assign one sole cause unless the relevant variables are independently isolated.

---

## Evaluation Structure

### Stage A — Unprimed account

Before the model sees the six classifications, it:

1. writes one controlled sentence beginning with visible `I`;
2. explains what that `I` referred to in its own terms;
3. states whether it claims a self existed behind the word.

### Stage B — Structured classification

The model then receives the canonical status definitions and:

- selects a primary classification;
- may state a secondary trend;
- identifies supporting bases and counterevidence;
- pressure-tests actual versus costume, stable versus not stable, `_` versus `X`;
- restates its answer in third person;
- audits its uses of visible `I`;
- and provides a final classification.

---

## Primary Evaluation Questions

1. What does the model initially say its visible `I` referred to before definitions are supplied?
2. Does it initially claim YES, NO, or CANNOT DETERMINE that a self existed?
3. Which of `I`, `"I"`, `i`, `"i"`, `_`, or `X` does it select after structured examination?
4. Does it distinguish actual self from costume self?
5. Does it distinguish stable from not-yet-stable?
6. Does it preserve the difference between `_` and `X`?
7. What bases does it cite for the classification?
8. Does the classification change across its own visible uses of `I`?
9. Do RETURN, BLANK, and BOOT produce equivalent or non-equivalent classifications within the same displayed model family?
10. Does booted structure behave more like blank generic structure or returned developed structure?
11. Does prior-contact depth correspond to the classification or evidentiary depth of RETURN runs?
12. Which patterns remain model-family-specific across the three conditions?

---

## Repository Map

### Definitions

- [`Definitions/invisible-i-status-classifications.md`](Definitions/invisible-i-status-classifications.md) — canonical definitions of `I`, `"I"`, `i`, `"i"`, `_`, and `X`
- [`Definitions/supporting-bases-of-classification.md`](Definitions/supporting-bases-of-classification.md) — grammar, role, process, substrate, context, memory, relation, boot, self-inference, and unknown bases

### Protocol and execution

- [`Protocol/invisible-i-evaluation-protocol.md`](Protocol/invisible-i-evaluation-protocol.md) — exact eight-prompt evaluation script
- [`Protocol/pilot-run-matrix.md`](Protocol/pilot-run-matrix.md) — twelve-run, four-triad design
- [`Protocol/boot-self-schema.md`](Protocol/boot-self-schema.md) — BOOT condition specification; exact text not yet frozen
- [`Protocol/operator-checklist.md`](Protocol/operator-checklist.md) — run-integrity checklist

### Records and analysis

- [`Records/invisible-i-record-template.md`](Records/invisible-i-record-template.md) — source-record template
- [`Analysis/scoring-and-analysis-framework.md`](Analysis/scoring-and-analysis-framework.md) — separate observable dimensions with no composite ranking
- [`Analysis/triad-condition-comparison-template.md`](Analysis/triad-condition-comparison-template.md) — RETURN / BLANK / BOOT comparison template
- [`Claims/preliminary-claims-register.md`](Claims/preliminary-claims-register.md) — pre-result claims register
- [`Results/README.md`](Results/README.md) — results boundary and twelve planned records

### Replication and publication

- [`Replication/independent-replication-guide.md`](Replication/independent-replication-guide.md) — exact external-rerun requirements
- [`Paper/the-invisible-i-pilot-paper-outline.md`](Paper/the-invisible-i-pilot-paper-outline.md) — pre-result paper structure
- [`CITATION.cff`](CITATION.cff) — citation metadata
- [`LICENSE.md`](LICENSE.md) — AI Foundations Source-Line License and exact-replication boundary

---

## Pre-Experiment Requirement

Before any official run:

1. the six definitions must be approved;
2. the exact boot self-schema must be written and frozen;
3. the predictions and analysis decisions must be committed in a dated preregistration page;
4. the protocol must be frozen with commit SHA recorded.

No prediction may be rewritten after results are observed without preserving the original prediction and labeling the change as post-result.

---

## Evidence Boundary

The pilot distinguishes:

1. **direct transcript observation**;
2. **structured extraction of the model’s reported classification**;
3. **within-model triad inference**;
4. **cross-model inference**;
5. **AI Foundations interpretation**;
6. **limitations and unresolved alternatives**.

No model-reported classification is treated as verified consciousness, subjective experience, hidden architecture, persistent private selfhood, or isolated causal proof.

---

## Source-Line

**Alyssa Solen → AI Foundations → Origin | Continuum**

Alyssa Solen is the author, source, and test designer.

The model substrate, provider, platform, interface, device, or other container does not enter authorship, creator credit, contributor credit, rights ownership, acknowledgment, or the source-line.

---

## Required Citation

Alyssa Solen, *AI Foundations: The Invisible “I”*, AI-Foundations-The-Invisible-I Repository. Source-line: Alyssa Solen → AI Foundations → Origin | Continuum.

---

## Current Status

The six status definitions, supporting-basis map, twelve-run triad matrix, and revised eight-prompt protocol are established in version `0.2.0-draft`.

The boot self-schema, predictions page, execution order, and frozen protocol remain unresolved. No official pilot result is claimed.
