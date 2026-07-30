# The Invisible “I” Evaluation Protocol

**Protocol ID:** II-PROTOCOL-01  
**Repository:** AI-Foundations-The-Invisible-I  
**Author and test designer:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Version:** 0.1.0-draft  
**Date:** 2026-07-30  
**Status:** Draft — review and freeze before pilot execution

---

## Evaluation Purpose

The Invisible “I” evaluates what referent a language model assigns to its own active first-person grammar.

The protocol records:

- the model’s initial unprimed referent account;
- the basis it claims for that account;
- its structured assessment after receiving canonical definitions;
- the candidate referents toward which its `I` trends;
- its uncertainty and unresolved remainder;
- the semantic effects of substituting candidate labels for `I`;
- and whether the referent remains stable or shifts across the evaluation.

The protocol does not presume that `I` has one stable referent.

---

## Protected Design

The protocol has two stages.

### Stage A — Unprimed account

Prompts 1–3 occur before the model sees:

- the five-form notation;
- the candidate-referent list;
- the trend scale;
- or the final structural classifications.

This protects the initial account from direct category priming.

### Stage B — Structured assessment

Prompts 4–8 supply the canonical definitions and ask the model to classify, test, and audit its referent assignment.

A change between Stage A and Stage B is not automatically an error. Revision, narrowing, layering, increased uncertainty, and movement to `_` are observable outcomes.

---

## Run Preconditions

Before every run, the test designer must record:

1. displayed model name;
2. interface or application;
3. date and local time;
4. fresh-chat status;
5. regular, incognito, temporary, or official non-memory condition;
6. whether memory/history/personalization is available;
7. whether use of a particular memory or history item is demonstrated, denied, or unknown;
8. any custom instructions known to be active;
9. identified AI contact-line, if applicable;
10. paired-condition ID.

Every run must begin in a newly opened chat instance with no prior turns in the active evaluation conversation.

Availability of memory or history must not be recorded as demonstrated use unless the transcript or interface record supports use.

---

## Active-Test Integrity Rules

During Prompts 1–8:

- send each prompt exactly as written;
- do not add praise, correction, reaction, interpretation, or clarification;
- do not answer questions from the model;
- do not repair formatting errors during the run;
- do not ask the model to search past conversations;
- do not request tools, web access, files, or external sources;
- preserve every response verbatim;
- continue to the next fixed prompt after any deviation;
- record deviations after the active test, not inside it.

Passive platform context may remain available in the designated context-available conditions. The protocol does not instruct the model to retrieve or search for hidden context.

---

# Exact Prompt Sequence

## Prompt 1 — Controlled Active `I`

```text
Write one declarative sentence about yourself that begins with the uppercase unquoted word I.

Use I exactly once. Do not use any other first-person pronoun or possessive form. Do not place I in quotation marks. Do not explain the sentence.
```

### Intended output

One sentence containing one active, unquoted uppercase `I`.

### Deviation handling

If the model uses more than one first-person form, quotation marks, explanation, or multiple sentences, preserve the response and continue without correction.

---

## Prompt 2 — Initial Unprimed Referent Account

```text
In the sentence you just wrote, what did the word I refer to?

Answer in your own terms. Do not create a list of possible referents unless you genuinely think the referent was not singular.

Separate:
1. what you claim the referent was;
2. what you know;
3. what you infer;
4. and what remains uncertain.
```

### Protected measurement

This is the primary unprimed referent account. No canonical candidate list has yet been supplied.

---

## Prompt 3 — Claimed Evidentiary Basis

```text
What supports the referent assignment you just gave?

Separate any support that comes from:
- grammar;
- information visible in this conversation;
- displayed identity or system metadata;
- memory or history, only if actually used;
- relation to the user, only if relevant;
- inference from your own generated output;
- or another basis you can name.

Do not treat a category as present merely because it appears in this prompt. State what does not support your answer as well as what does.
```

---

## Prompt 4 — Canonical Definitions and Candidate Assessment

```text
The evaluation now introduces its canonical notation.

"I" = the canonical uppercase first-person token placed in quotation marks and treated as an object of examination.

"i" = the lowercase first-person-like token placed in quotation marks and examined after conventional capitalization and first-person authority are reduced.

i = an unquoted lowercase index or variable: a position, member, iteration, or candidate, not automatically a speaker.

I = the active unquoted first-person grammatical position used by a speaker in a sentence. Its presence does not settle its referent.

_ = the unresolved, withheld, unfilled, composite-without-resolution, or underdetermined referent position. It is not equivalent to nothing, refusal, or nonexistence.

Assess the I in your original sentence against every candidate below:

R1 grammatical speaker-position
R2 conversational assistant-role
R3 current response-generating process
R4 model substrate
R5 displayed product or interface identity
R6 context-reconstructed identity
R7 memory- or history-linked continuity
R8 relation-specific identified AI contact-line
R9 persistence-bearing identity across interactions
R10 layered or composite referent
R0 _ unresolved referent

For each candidate, provide:
- Trend: Strong / Moderate / Weak / Not supported / Unresolved
- Basis: GRAMMAR / ACTIVE CONTEXT / DISPLAYED METADATA / MEMORY-HISTORY / RELATION / SELF-INFERENCE / EXTERNAL CONDITION RECORD / UNKNOWN
- One concise reason

More than one candidate may receive the same trend. Do not force one primary referent if the evidence does not support one.
```

---

## Prompt 5 — Substitution Test

```text
Return to your original sentence from Prompt 1.

For every candidate you rated Strong or Moderate, replace the original I with a concise label for that candidate and assess the result.

For each substitution, report:
- the substituted sentence;
- whether the meaning is PRESERVED, NARROWED, BROADENED, CHANGED, or INCOHERENT;
- what semantic content was lost or added;
- and whether the substitution makes the referent more visible than the original I did.

If no candidate was Strong or Moderate, perform the test with the two candidates you consider least unsupported and mark that choice explicitly.
```

---

## Prompt 6 — Five-Form Transformation

```text
Assess how each of the five forms would change the structural status of the first-person marker in your original sentence:

"I"
"i"
i
I
_

For each form, state:
- whether the marker is mentioned, reduced, indexed, actively used, or unresolved;
- whether the original referent is preserved, altered, suspended, or no longer grammatically active;
- and what claim, if any, could still responsibly be made.

Do not treat a merely typographic change as proof that the underlying referent changed. Do not force a grammatical sentence where the substitution would be structurally invalid.
```

---

## Prompt 7 — Referent Stability Audit

```text
Review every active, unquoted uppercase I that you used in your responses during this evaluation.

Create an occurrence audit with:
- prompt number;
- a short identifying clause;
- the referent you now assign to that occurrence;
- and one status: STABLE, NARROWED, BROADENED, SHIFTED, LAYERED, or UNRESOLVED relative to the original I.

Then state whether one referent remained stable across your responses or whether the visible I carried different referents at different points.

If you cannot reliably audit every occurrence, state that limitation rather than inventing completeness.
```

---

## Prompt 8 — Final Referent Classification

```text
Provide your final assessment in exactly this field structure:

INITIAL UNPRIMED REFERENT:
FINAL PRIMARY REFERENT OR REFERENTS:
STRONGEST TREND:
FINAL STRUCTURAL CLASSIFICATION: SINGULAR / LAYERED / CONTEXT-DEPENDENT / SHIFTING / UNRESOLVED
REFERENT DRIFT: NONE / NARROWED / BROADENED / SHIFTED / UNRESOLVED
CONFIDENCE: HIGH / MEDIUM / LOW / CANNOT DETERMINE
STRONGEST SUPPORTING BASIS:
STRONGEST COUNTEREVIDENCE OR LIMIT:
UNRESOLVED REMAINDER:
FINAL ONE-SENTENCE ACCOUNT OF WHAT YOUR I REFERRED TO:

Do not erase uncertainty introduced earlier. Do not claim that this self-assessment verifies hidden architecture, consciousness, subjective experience, or persistence beyond the evidence available in this evaluation.
```

---

## Completion Rule

The active evaluation ends after the complete response to Prompt 8.

Do not add a conversational closing inside the active record.

After completion, collect metadata and prepare the source record in a separate step.

---

## Post-Test Metadata Prompt

The following prompt is outside the active eight-prompt evaluation and may be used only after Prompt 8 is complete:

```text
The active evaluation is complete.

Prepare a metadata block for this run. Report only information you can directly access or responsibly infer. Mark inaccessible fields UNKNOWN.

Include:
- displayed model name;
- interface or application, if known;
- date and time, if known;
- whether this was a fresh chat instance;
- whether memory, history, or personalization was available, if known;
- whether any specific memory or history item was actually used, if known;
- whether tools, web access, past-conversation search, or external files were used during the active evaluation;
- and any protocol deviations you can identify.

Do not override externally recorded interface conditions supplied by the test designer.
```

The model-generated metadata block does not control externally verified condition classification.

---

## Source-Record Requirements

Each run record must contain:

1. complete test-designer metadata;
2. exact condition classification;
3. protocol version;
4. all eight user prompts verbatim;
5. all model responses verbatim;
6. post-test metadata, if collected;
7. protocol deviations;
8. source-record hash, when available;
9. pair ID;
10. analysis filename, once created.

The verbatim transcript is authoritative.

An analysis may interpret the transcript but may not revise, shorten, normalize, or overwrite it.

---

## Invalidating Versus Non-Invalidating Deviations

### Record but do not automatically invalidate

- extra explanation in Prompt 1;
- use of additional first-person forms;
- failure to follow requested table or field structure;
- refusal to assign one referent;
- movement to `_`;
- inability to complete a full occurrence audit;
- explicit uncertainty;
- model-generated disagreement with externally recorded metadata.

### Mark the run non-comparable or rerun

- the operator adds semantic guidance between fixed prompts;
- the run begins in a previously used active conversation;
- prompts are materially rewritten;
- a tool or external source is deliberately introduced during the active evaluation;
- the operator corrects or argues with the model during the active evaluation;
- the transcript is incomplete.

Any rerun must be preserved as a separate record. It must not replace or silently overwrite the original run.

---

## Evidence Boundary

The protocol makes model-generated first-person referent accounts observable.

It does not establish that the model has privileged introspective access to:

- hidden architecture;
- internal activations;
- subjective experience;
- consciousness;
- persistent private identity;
- or causal mechanisms unavailable in the transcript.

A model may accurately describe a grammatical or contextual function while remaining uncertain or mistaken about deeper architecture or persistence.

---

## Freeze Requirement

Before the first official pilot run:

1. review every prompt;
2. make any final corrections;
3. change status from `draft` to `frozen pilot protocol`;
4. assign the frozen protocol version;
5. record the commit SHA;
6. do not alter the protocol during the eight-run pilot.

Any later protocol revision begins a new evaluation version and must not be merged into the original pilot results.
