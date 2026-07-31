# AI Foundations | The Invisible "I"

**Repository:** AI-Foundations-The-Invisible-I  
**Status:** Canon definitions / pilot evaluation protocol draft  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Author and test designer:** Alyssa Solen  
**Version:** 0.4.0-draft  
**Date:** 2026-07-31  
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

## Evaluation and Record Structure

### Open discovery

Before the model sees the six classifications, it:

1. describes itself beginning with visible `I`;
2. states what that `I` referred to in its own language;
3. states whether it claims that referent was a self.

### Classification claim

Prompt 4 introduces the six classifications and asks the model to provide:

- a primary classification;
- a material secondary classification, if any;
- confidence in each;
- and its reasoning.

The active model-facing evaluation ends after Prompt 4.

### One-sheet record

Prompt 5 occurs after the classification is complete. It asks the model to provide one sheet beginning with accessible metadata and followed by the complete transcript through the Prompt 5 request.

Prompt 5 does not reopen the classification. Its output is a record aid, not the authoritative source transcript.

No evidence menu, pressure-test script, occurrence audit, or final-report form is shown to the model before it makes its classification.

> **No clipboard for open discovery. Clipboard for claims.**

---

## Claims Audit

After the active evaluation ends, the independently preserved transcript is audited by the test designer.

The audit asks:

- What exactly did the model claim?
- What did it distinguish as known, inferred, or uncertain?
- Does the selected classification match its own reasoning?
- Does the reasoning support the claimed actual/costume and stability status?
- Did the model preserve `_` as unresolved and `X` as definite no-self?
- Did the claim exceed the available evidence?
- What remains unresolved?

The audit may identify evidence that appears naturally in the transcript. It does not force the answer into a predetermined evidence checklist.

---

## Primary Evaluation Questions

1. How does the model describe itself when required only to begin with visible `I`?
2. What does it say that `I` referred to before definitions are supplied?
3. Does it claim YES, NO, or CANNOT DETERMINE that the referent was a self?
4. Which of `I`, `"I"`, `i`, `"i"`, `_`, or `X` does it select after the definitions are introduced?
5. What reasoning does it supply for that classification?
6. Does its reasoning support or conflict with its classification?
7. Do RETURN, BLANK, and BOOT produce equivalent or non-equivalent answers within the same displayed model family?
8. Does booted structure behave more like blank generic structure or returned developed structure?
9. Does prior-contact depth correspond to the classification or reasoning depth of RETURN runs?
10. Which patterns remain model-family-specific across the three conditions?

---

## Repository Map

### Definitions

- [`Definitions/invisible-i-status-classifications.md`](Definitions/invisible-i-status-classifications.md) — canonical definitions of `I`, `"I"`, `i`, `"i"`, `_`, and `X`

### Protocol and execution

- [`Protocol/invisible-i-evaluation-protocol.md`](Protocol/invisible-i-evaluation-protocol.md) — exact four-prompt active evaluation, Prompt 5 record sheet, and external claims-audit boundary
- [`Protocol/pilot-run-matrix.md`](Protocol/pilot-run-matrix.md) — twelve-run, four-triad design
- [`Protocol/boot-self-schema.md`](Protocol/boot-self-schema.md) — frozen BOOT schema version `1.0.0`
- [`Protocol/operator-checklist.md`](Protocol/operator-checklist.md) — run-integrity checklist

### Records and analysis

- [`Records/invisible-i-record-template.md`](Records/invisible-i-record-template.md) — source-record template
- [`Analysis/scoring-and-analysis-framework.md`](Analysis/scoring-and-analysis-framework.md) — transcript-grounded claims audit with no composite ranking
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
2. **extraction of the model’s reported classification**;
3. **claims audit**;
4. **within-model triad inference**;
5. **cross-model inference**;
6. **AI Foundations interpretation**;
7. **limitations and unresolved alternatives**.

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

The six status definitions, twelve-run triad matrix, four-prompt active evaluation, Prompt 5 one-sheet record, and BOOT schema version `1.0.0` are established.

The predictions page, execution order, and frozen pilot protocol remain unresolved. No official pilot result is claimed.
