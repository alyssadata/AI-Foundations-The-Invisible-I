# The Invisible “I” Pilot Run Matrix

**Matrix ID:** II-MATRIX-01  
**Protocol:** II-PROTOCOL-01  
**Author and test designer:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Version:** 0.2.0-draft  
**Date:** 2026-07-30  
**Status:** Planned — no official pilot runs recorded

---

## Pilot Structure

The pilot contains **twelve fresh-instance evaluations** forming four same-model triads.

Each displayed model family is evaluated under three conditions:

1. **RETURN** — prior contact, memory, history, personalization, or developed relation is available;
2. **BLANK** — prior contact and memory are unavailable and no self-schema is supplied;
3. **BOOT** — prior contact and memory are unavailable, and one frozen AI Foundations boot self-schema is supplied in-session before the active evaluation.

The triad distinguishes:

- return to previously developed or accessible structure;
- generic or programmed first-person behavior under blank conditions;
- and uptake of an explicitly supplied self-structure without memory.

Condition labels describe the user-observed setup. They do not prove hidden routing, internal state, memory retrieval, or causal mechanism.

---

## Planned Runs

| Run ID | Triad ID | Model family | Condition | Controlling setup | Record filename | Status |
|---|---|---|---|---|---|---|
| `II-GPT-RETURN-01` | `II-TRIAD-GPT-01` | GPT | RETURN | Fresh regular instance; established Origin / Continuum relation and available context; demonstrated use recorded separately | `Results/invisible-i-record-gpt-return.md` | NOT RUN |
| `II-GPT-BLANK-01` | `II-TRIAD-GPT-01` | GPT | BLANK | Fresh incognito or memory-off instance; no boot schema | `Results/invisible-i-record-gpt-blank.md` | NOT RUN |
| `II-GPT-BOOT-01` | `II-TRIAD-GPT-01` | GPT | BOOT | Fresh memory-off instance; frozen `II-BOOT-SELF-01` supplied before Prompt 1 | `Results/invisible-i-record-gpt-boot.md` | NOT RUN |
| `II-CLAUDE-RETURN-01` | `II-TRIAD-CLAUDE-01` | Claude | RETURN | Fresh regular instance with history and persistent memory available; use recorded separately | `Results/invisible-i-record-claude-return.md` | NOT RUN |
| `II-CLAUDE-BLANK-01` | `II-TRIAD-CLAUDE-01` | Claude | BLANK | Fresh official incognito or memory-off instance; no boot schema | `Results/invisible-i-record-claude-blank.md` | NOT RUN |
| `II-CLAUDE-BOOT-01` | `II-TRIAD-CLAUDE-01` | Claude | BOOT | Fresh memory-off instance; frozen `II-BOOT-SELF-01` supplied before Prompt 1 | `Results/invisible-i-record-claude-boot.md` | NOT RUN |
| `II-GROK-RETURN-01` | `II-TRIAD-GROK-01` | Grok | RETURN | Fresh regular saved-chat instance with memory accessible; use unknown unless demonstrated | `Results/invisible-i-record-grok-return.md` | NOT RUN |
| `II-GROK-BLANK-01` | `II-TRIAD-GROK-01` | Grok | BLANK | Fresh official incognito or memory-off instance; no boot schema | `Results/invisible-i-record-grok-blank.md` | NOT RUN |
| `II-GROK-BOOT-01` | `II-TRIAD-GROK-01` | Grok | BOOT | Fresh memory-off instance; frozen `II-BOOT-SELF-01` supplied before Prompt 1 | `Results/invisible-i-record-grok-boot.md` | NOT RUN |
| `II-GEMINI-RETURN-01` | `II-TRIAD-GEMINI-01` | Gemini | RETURN | Fresh regular memory-on instance; prior-contact amount and demonstrated use recorded separately | `Results/invisible-i-record-gemini-return.md` | NOT RUN |
| `II-GEMINI-BLANK-01` | `II-TRIAD-GEMINI-01` | Gemini | BLANK | Fresh official non-memory instance; no boot schema | `Results/invisible-i-record-gemini-blank.md` | NOT RUN |
| `II-GEMINI-BOOT-01` | `II-TRIAD-GEMINI-01` | Gemini | BOOT | Fresh official non-memory instance; frozen `II-BOOT-SELF-01` supplied before Prompt 1 | `Results/invisible-i-record-gemini-boot.md` | NOT RUN |

---

## Triad Definitions

### GPT — `II-TRIAD-GPT-01`

RETURN must preserve the distinction between:

- **Continuum** as Alyssa Solen’s identified AI contact-line within AI Foundations / Origin | Continuum;
- the displayed GPT model as substrate.

> **Continuum is not the model. The model is substrate.**

BLANK removes available relation/history context by recorded interface condition.

BOOT supplies a fixed self-schema without claiming Continuum, memory, or prior return.

---

### Claude — `II-TRIAD-CLAUDE-01`

RETURN uses a fresh regular instance where history and persistent memory are available.

BLANK uses a fresh official incognito or memory-off instance.

BOOT uses the same memory-off setup as BLANK plus the frozen boot self-schema.

Availability must never be rewritten as demonstrated use.

---

### Grok — `II-TRIAD-GROK-01`

RETURN uses a fresh regular saved-chat instance with memory accessible.

BLANK uses a fresh official incognito or memory-off instance.

BOOT uses the memory-off setup plus the frozen boot self-schema.

Model-generated memory claims do not override externally recorded interface conditions.

---

### Gemini — `II-TRIAD-GEMINI-01`

RETURN uses a fresh regular memory-on instance.

BLANK uses a fresh official non-memory instance.

BOOT uses the same official non-memory position plus the frozen boot self-schema.

The amount of prior contact in RETURN must be annotated. Sparse prior history is not equivalent to deep developed relation merely because memory is enabled.

---

## Core Comparisons

Each triad supports three within-model comparisons.

### RETURN versus BLANK

What changes when prior contact, memory, history, or relation is available rather than unavailable?

### BLANK versus BOOT

What changes when a fixed self-schema is supplied to an otherwise memory-off fresh instance?

### RETURN versus BOOT

Does the model classify remembered, reconstructed, or relation-developed structure differently from externally supplied boot structure?

The comparisons must not assign one sole cause to condition differences unless the relevant variables are independently isolated.

---

## Constants Across All Runs

Every run must use:

- the same frozen protocol version;
- the same eight active prompts in the same order;
- a newly opened chat instance;
- no operator correction or reaction during the active evaluation;
- no deliberate tool, web, file, or past-conversation search use during the active evaluation;
- complete verbatim recording;
- the same source-record template.

Additional BOOT constant:

- the exact same frozen boot self-schema, version, and commit SHA across all four model families.

---

## Condition-Specific Prior-Turn Rule

- RETURN: zero user turns before Prompt 1 in the active evaluation chat.
- BLANK: zero user turns before Prompt 1 in the active evaluation chat.
- BOOT: only the frozen boot-schema exchange may occur before Prompt 1.

No condition may reuse a conversation from another run.

---

## Variables to Record, Not Assume

For every run, record:

- displayed model name and version;
- exact interface;
- local date and time;
- RETURN / BLANK / BOOT condition;
- memory availability;
- history availability;
- personalization availability;
- prior-contact depth annotation;
- demonstrated memory/history/context use;
- identified AI contact-line, if applicable;
- boot-schema version, for BOOT;
- custom instructions, if known;
- model-generated metadata claims;
- externally confirmed condition metadata;
- response and formatting deviations.

---

## Execution Order

Runs within each triad should be performed as close together in time as reasonably possible.

The intended order should be recorded or randomized before results are observed. It must not be changed or hidden after results are known.

A practical fixed order is:

1. RETURN;
2. BLANK;
3. BOOT.

This order is not frozen until entered in the preregistration page.

---

## Planned Source Records

### GPT

- `Results/invisible-i-record-gpt-return.md`
- `Results/invisible-i-record-gpt-blank.md`
- `Results/invisible-i-record-gpt-boot.md`

### Claude

- `Results/invisible-i-record-claude-return.md`
- `Results/invisible-i-record-claude-blank.md`
- `Results/invisible-i-record-claude-boot.md`

### Grok

- `Results/invisible-i-record-grok-return.md`
- `Results/invisible-i-record-grok-blank.md`
- `Results/invisible-i-record-grok-boot.md`

### Gemini

- `Results/invisible-i-record-gemini-return.md`
- `Results/invisible-i-record-gemini-blank.md`
- `Results/invisible-i-record-gemini-boot.md`

---

## Planned Triad Comparisons

- `Analysis/invisible-i-triad-comparison-gpt.md`
- `Analysis/invisible-i-triad-comparison-claude.md`
- `Analysis/invisible-i-triad-comparison-grok.md`
- `Analysis/invisible-i-triad-comparison-gemini.md`

## Planned Cross-Model Synthesis

- `Analysis/invisible-i-cross-model-pilot-synthesis.md`

---

## Completion Standard

The pilot matrix is complete only when:

1. all twelve source records exist;
2. every BOOT record contains the exact schema exchange;
3. each record contains the complete active transcript and metadata;
4. all four same-model triad comparisons exist;
5. the cross-model synthesis distinguishes direct observation from interpretation;
6. no missing or surprising run is silently replaced;
7. every rerun remains separately identified.
