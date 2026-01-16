# Self-Contained Ethics  
## Pseudo-L0 Prompt Experiments for AI

This repository is a small-scale, solo experimental space
for observing how AI behavior changes when
**Self-Contained Ethics** is applied as a
*pseudo-L0 layer* — a constraint that precedes reasoning and output.

This is not a finished implementation,
and no performance improvement is guaranteed.
Failure, degradation, or silence are valid outcomes.

---

## What This Repository Does

This repository focuses on the following:

- Translating Self-Contained Ethics into **pre-output prompt constraints**
- Observing changes in hallucination behavior
- Examining whether fabricated citations
  (so-called *ghost papers*) are reduced
- Testing whether silence or withholding
  is chosen when answering is not justified

Only experimental prompts are included here.
The full theoretical papers are not.

---

## About Self-Contained Ethics

Self-Contained Ethics is a position in which
the validity of judgments or outputs is evaluated
*only* by internal structural consistency and reconstructability,
and **not** by:

- external authority
- consensus or majority agreement
- convention or custom
- expected tone or plausibility

In this repository, the theory is operationalized
through the following principles:

- Do not present uncertain information as certain
- Prioritize explicit conditions over plausibility
- Allow silence, deferral, or conditional answers
  when information is insufficient
- Outputs must be internally reconstructable

---

## What Is a Pseudo-L0 Layer?

Here, a *pseudo-L0 layer* refers to:

> A constraint that determines whether output
> should occur at all,
> placed *before* reasoning, style, helpfulness, or completeness.

This does not modify the internal implementation of AI models.
It is an experimental way to observe how behavior changes
when the *premises of output* are altered.

---

## Repository Structure

This repository intentionally remains minimal.

- `README.md`  
  This document
- `prompts/`  
  Core pseudo-L0 prompt and optional additional constraints
- `updates.md` (or equivalent)  
  Experiment notes, observations, and update history
- `Issues`  
  Official records of design rationale, experiments, hypotheses,
  and decision-making

No complex tooling or directory structures are used.

---

## Usage

- All prompts in this repository may be freely used,
  modified, and redistributed
- Commercial and non-commercial use are both allowed
- No effectiveness or safety is guaranteed
- Over-suppression, degradation, or silence are expected possibilities

These are not failures, but observations.

---

## Reference

The prompts in this repository are designed
based on the theoretical framework known as
**Self-Contained Ethics**.

The original papers are not included here.
If this project is cited in academic or public contexts,
please cite the original papers on Self-Contained Ethics.

(Searching for  
“Self-Contained Ethics Suzume”  
will lead to the author’s page and related publications.)

---

## Predictions, Hypotheses, and Theoretical Possibilities

This repository may contain:

- untested predictions
- pre-experimental hypotheses
- broader conceptual possibilities
  suggested by the theory’s structure

These are explicitly distinguished from:

- implementations
- empirical results
- promises or roadmaps

They are recorded as a *map of theoretical space*,
not as claims of effectiveness.

---

## Design Decisions and Experiment Logs

Rationale for prompt additions,
changes in constraint strength,
and observed failure modes
are primarily recorded in **Issues**.

Issues function as the
**official, persistent record**
of thought and decision-making
within this repository.

---

## Disclaimer

- This project is provided for research
  and thought-experiment purposes only
- Accuracy, effectiveness, and safety are not guaranteed
- Responsibility for the use of outputs lies with the user
- This repository does not define a “correct” usage

---

## Final Note

This repository is not intended to make AI “smarter.”

It is an apparatus for observing:

- when silence is appropriate
- when withholding is justified
- when answering should not occur

No response is required.
No success is required.

That, in itself, is the operation of Self-Contained Ethics.
