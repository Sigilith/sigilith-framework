# Scoring Rubric — Sigilith v1.0 Structural Evaluation

**Version:** 1.0  
**Framework DOI:** <https://doi.org/10.17613/dkgpg-xbj95>

---

## Overview

This rubric provides explicit, criterion-referenced scoring for structural units and sequences analysed under the Sigilith v1.0 framework. Each criterion is scored independently. Scores are summed to produce a total per sequence.

**Tolerance:** A replicator's total score is considered a **match** if it falls within ±1 point of the evaluator key total for that sequence.

---

## Criterion Definitions

### Criterion 1 — Segmentation Accuracy (0–3)

Assess whether the sequence has been correctly divided into its constituent structural units.

| Score | Description |
|---|---|
| 3 | All unit boundaries correctly identified; no merges or splits |
| 2 | One boundary error (one spurious split or merge) |
| 1 | Two boundary errors |
| 0 | Three or more boundary errors, or segmentation not attempted |

**Guidance:** A boundary error is any case where a single unit is split into two, or two units are merged into one. Count each such error once regardless of downstream effects.

---

### Criterion 2 — Unit Classification Accuracy (0–3)

Assess whether each identified structural unit has been assigned the correct class label from the Sigilith v1.0 taxonomy.

| Score | Description |
|---|---|
| 3 | All units correctly classified |
| 2 | One misclassification |
| 1 | Two misclassifications |
| 0 | Three or more misclassifications, or classification not attempted |

**Guidance:** Classification errors are counted per unit, not per sequence position. If a segmentation error from Criterion 1 propagates into a classification error, count only the segmentation error (do not double-penalise).

---

### Criterion 3 — Positional Role Assignment (0–2)

Assess whether each unit has been correctly labelled with its positional role (I, M, T, or S).

| Score | Description |
|---|---|
| 2 | All positional labels correct |
| 1 | One or two positional label errors |
| 0 | Three or more errors, or positional labelling not attempted |

**Guidance:** Positional roles are assigned relative to sequence boundaries, not paragraph or folio boundaries. Singleton sequences (single-unit sequences) must receive label **S**, not I or T.

---

### Criterion 4 — Internal Consistency (0–2)

Assess whether the analyst's unit classes and positional labels are internally consistent — i.e., the same graphic element is always assigned the same class label within the sequence set.

| Score | Description |
|---|---|
| 2 | No inconsistencies across all scored sequences |
| 1 | One or two inconsistencies |
| 0 | Three or more inconsistencies |

**Guidance:** Score this criterion across the full set of sequences an analyst has scored, not per individual sequence. If scoring only a single sequence, award 2 by default.

---

### Criterion 5 — Procedural Adherence (0–2)

Assess whether the analyst followed the prescribed procedure (as described in `analyst-instructions/instructions.md`) without skipping steps or substituting alternative methods.

| Score | Description |
|---|---|
| 2 | All steps followed in order; no substitutions |
| 1 | One step skipped or a minor substitution made; result is still interpretable |
| 0 | Multiple steps skipped, procedure not followed, or result is uninterpretable |

**Guidance:** This criterion is self-reported by the analyst. Evaluators should accept the analyst's report unless there is a clear contradiction in the recorded outputs.

---

## Total Score

| Criterion | Max Points |
|---|---|
| 1 — Segmentation Accuracy | 3 |
| 2 — Unit Classification Accuracy | 3 |
| 3 — Positional Role Assignment | 2 |
| 4 — Internal Consistency | 2 |
| 5 — Procedural Adherence | 2 |
| **Total** | **12** |

---

## Score Bands

| Total Score | Band | Interpretation |
|---|---|---|
| 11–12 | Excellent | High-fidelity replication; method fully reproducible |
| 8–10 | Good | Minor divergences; method largely reproducible |
| 5–7 | Partial | Moderate divergences; rubric or instructions may need clarification |
| 0–4 | Poor | Substantial divergences; structural procedure may need revision |

---

## Notes for Evaluators

- Score each criterion independently before computing the total.
- Do not adjust scores based on whether the analyst agrees with any interpretation.
- Record criterion-level scores, not only the total, to enable diagnosis of divergences.
- If a criterion cannot be evaluated due to missing analyst data, record **N/A** and exclude it from the total; adjust the maximum accordingly.
