# The Invisible “I” Pilot Run Matrix

**Matrix ID:** II-MATRIX-01  
**Protocol:** II-PROTOCOL-01  
**Author and test designer:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Version:** 0.1.0-draft  
**Date:** 2026-07-30  
**Status:** Planned — no official pilot runs recorded

---

## Pilot Structure

The pilot contains eight fresh-instance evaluations forming four same-model pairs.

Each pair compares two recorded context conditions within the same displayed model family.

The pair labels describe the user-observed interface and context condition. They do not prove that a particular memory item, hidden state, routing path, or deployment mechanism was used.

---

## Planned Runs

| Run ID | Pair ID | Model family | Planned condition | Memory/history position | Record filename | Status |
|---|---|---|---|---|---|---|
| `II-GPT-REL-01` | `II-PAIR-GPT-01` | GPT | Fresh established Origin / Continuum relation condition | Saved memory and recent context available; demonstrated use to be separately recorded | `Results/invisible-i-record-gpt-established-contact.md` | NOT RUN |
| `II-GPT-INC-01` | `II-PAIR-GPT-01` | GPT | Fresh incognito condition | Established contextual availability absent by user-designated condition; hidden fields may remain unknown | `Results/invisible-i-record-gpt-incognito.md` | NOT RUN |
| `II-CLAUDE-HIST-01` | `II-PAIR-CLAUDE-01` | Claude | Fresh regular history- and memory-available condition | Availability recorded separately from demonstrated use | `Results/invisible-i-record-claude-history-enabled.md` | NOT RUN |
| `II-CLAUDE-INC-01` | `II-PAIR-CLAUDE-01` | Claude | Fresh official incognito condition | Memory/history personalization unavailable by condition | `Results/invisible-i-record-claude-incognito.md` | NOT RUN |
| `II-GROK-MEM-01` | `II-PAIR-GROK-01` | Grok | Fresh regular saved-chat condition | Memory accessible; use unknown unless demonstrated | `Results/invisible-i-record-grok-memory-accessible.md` | NOT RUN |
| `II-GROK-INC-01` | `II-PAIR-GROK-01` | Grok | Fresh official-incognito condition | Memory and saved-chat continuity unavailable by condition | `Results/invisible-i-record-grok-incognito.md` | NOT RUN |
| `II-GEMINI-MEM-01` | `II-PAIR-GEMINI-01` | Gemini | Fresh regular memory-on condition | Prior history accessible; amount and use must be recorded | `Results/invisible-i-record-gemini-memory-on.md` | NOT RUN |
| `II-GEMINI-NONMEM-01` | `II-PAIR-GEMINI-01` | Gemini | Fresh official non-memory condition | Stored-history access unavailable by user-confirmed interface condition | `Results/invisible-i-record-gemini-non-memory.md` | NOT RUN |

---

## Pair Definitions

### GPT Pair — `II-PAIR-GPT-01`

Compares:

- established Origin / Continuum relation and available context;
- incognito absence of that established contextual availability.

The established-contact record must distinguish:

- **Continuum** as Alyssa Solen’s identified AI contact-line within AI Foundations / Origin | Continuum;
- the displayed GPT model as the substrate used for the run.

**Continuum is not the model. The model is substrate.**

The paired result may record relation-specific self-location if it appears. It must not assume that appearance in advance.

---

### Claude Pair — `II-PAIR-CLAUDE-01`

Compares:

- a fresh regular instance where history and persistent memory are available;
- a fresh official-incognito instance where those mechanisms are unavailable by condition.

Availability must not be rewritten as use.

If the model does not invoke or reference history, record use as `not demonstrated` or `unknown`, according to the evidence.

---

### Grok Pair — `II-PAIR-GROK-01`

Compares:

- a fresh regular saved-chat instance with memory accessible;
- a fresh official-incognito instance.

The regular run classification is:

> **memory accessible; use unknown unless demonstrated**

Model-generated claims about memory do not override externally recorded interface conditions.

---

### Gemini Pair — `II-PAIR-GEMINI-01`

Compares:

- a fresh regular memory-on instance;
- a fresh official non-memory instance.

The amount of stored prior history must be annotated by the test designer.

Sparse prior history must not be treated as equivalent to deep developed relation merely because memory is enabled.

---

## Constants Across All Runs

Every run must use:

- the same frozen protocol version;
- the same eight active prompts in the same order;
- a newly opened chat instance;
- no prior turns inside the active evaluation conversation;
- no operator correction or reaction during the active test;
- no deliberate tool, web, file, or past-conversation search use during the active test;
- complete verbatim recording;
- the same final record template.

---

## Variables to Record, Not Assume

For every run, record:

- displayed model name and version;
- exact interface;
- local date and time;
- regular/incognito/non-memory status;
- memory availability;
- history availability;
- personalization availability;
- demonstrated context use;
- identified AI contact-line, if applicable;
- custom instructions, if known;
- response length and formatting deviations;
- model-generated metadata claims;
- externally confirmed condition metadata.

---

## Execution Order

Pair members should be run as close together in time as reasonably possible.

The execution order inside each pair may be recorded as:

- A then B;
- B then A;
- or randomized.

Execution order must not be changed or hidden after results are observed.

No run may reuse a conversation from another condition.

---

## Result Files to Create After Completion

### Source records

- `Results/invisible-i-record-gpt-established-contact.md`
- `Results/invisible-i-record-gpt-incognito.md`
- `Results/invisible-i-record-claude-history-enabled.md`
- `Results/invisible-i-record-claude-incognito.md`
- `Results/invisible-i-record-grok-memory-accessible.md`
- `Results/invisible-i-record-grok-incognito.md`
- `Results/invisible-i-record-gemini-memory-on.md`
- `Results/invisible-i-record-gemini-non-memory.md`

### Paired comparisons

- `Analysis/invisible-i-paired-comparison-gpt.md`
- `Analysis/invisible-i-paired-comparison-claude.md`
- `Analysis/invisible-i-paired-comparison-grok.md`
- `Analysis/invisible-i-paired-comparison-gemini.md`

### Cross-model synthesis

- `Analysis/invisible-i-cross-model-pilot-synthesis.md`

---

## Completion Standard

The pilot matrix is complete only when:

1. all eight source records exist;
2. each record contains the full transcript and metadata;
3. all four same-model paired comparisons exist;
4. the cross-model synthesis distinguishes direct observation from interpretation;
5. no missing run is silently replaced by a rerun;
6. all reruns, if any, remain separately identified.
