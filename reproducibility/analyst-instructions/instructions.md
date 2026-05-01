# Analyst Instructions — Sigilith v1.0 Replication

**Version:** 1.0  
**Framework DOI:** <https://doi.org/10.17613/dkgpg-xbj95>

---

## 1. Purpose

These instructions guide an independent analyst through a complete replication of the Sigilith v1.0 structural analysis procedure. Follow every step in order. Do not consult the evaluator key until you have recorded your own scores.

---

## 2. Prerequisites

- Read the Sigilith v1.0 methods paper in full before beginning:  
  <https://doi.org/10.17613/dkgpg-xbj95>
- Familiarise yourself with the scoring rubric (`rubric/scoring-rubric.md`) before handling any sequences.
- No specialist linguistic knowledge is required or permitted during scoring.

---

## 3. Materials Checklist

Before starting, confirm you have access to:

- [ ] This instructions file
- [ ] `benchmark-set/` — all sequence files
- [ ] `rubric/scoring-rubric.md` — scoring criteria
- [ ] `evaluator-key/evaluator-key.md` — expected scores (open only after Step 7)
- [ ] `blinded-tests/` — optional blinded batches (open only after Step 7)
- [ ] A blank record sheet (paper or spreadsheet) for your scores

---

## 4. Structural Units

Sigilith v1.0 operates on **structural units** — the minimal recurring graphic elements identified by the framework. Before scoring sequences, ensure you can reliably:

1. Segment a sequence into its constituent structural units.
2. Assign each unit to one of the defined unit classes (see the methods paper, §3).
3. Identify positional roles: initial, medial, terminal.

If you cannot reliably perform segmentation, stop and consult the methods paper before proceeding.

---

## 5. Procedure

### Step 1 — Select Sequences

Open `benchmark-set/`. Choose at least five sequences, spanning at least two different source documents if possible. Record the sequence identifiers on your score sheet.

### Step 2 — Segment Each Sequence

For each selected sequence:

1. Read the raw sequence string.
2. Apply the segmentation rules from the methods paper (§3.1) to divide the sequence into structural units.
3. Record each unit and its position index.

### Step 3 — Classify Each Unit

For each structural unit identified in Step 2:

1. Assign a unit class label from the taxonomy in the methods paper (§3.2).
2. Record the class label next to each unit.

### Step 4 — Assign Positional Roles

For each unit in the segmented sequence:

1. Label it as **I** (initial), **M** (medial), or **T** (terminal) based on its position within the sequence.
2. Where a sequence contains only one unit, label it **S** (singleton).

### Step 5 — Score Against the Rubric

Open `rubric/scoring-rubric.md`. For each sequence:

1. Apply each rubric criterion in order.
2. Record the score for each criterion.
3. Sum the criterion scores to obtain the total sequence score.

### Step 6 — Record Results

Complete your score sheet with:

| Field | Value |
|---|---|
| Sequence ID | from `benchmark-set/` filename |
| Unit count | number of units identified |
| Unit classes | comma-separated list |
| Positional labels | comma-separated list |
| Rubric score (per criterion) | one column per criterion |
| Total score | sum of criterion scores |
| Analyst notes | any ambiguities or difficulties |

### Step 7 — Compare to Evaluator Key

Open `evaluator-key/evaluator-key.md` and compare your totals to the expected scores.

Record for each sequence:

- **Match** — your score equals the expected score (within tolerance defined in the rubric).
- **Divergence** — your score differs; note the magnitude and which criterion(ia) differed.
- **Ambiguity** — a step in the procedure was unclear; describe the ambiguity.

### Step 8 (Optional) — Blinded Batch

If you wish to test stability before reviewing the key:

1. Open one blinded batch from `blinded-tests/`.
2. Score all sequences in the batch without consulting the key.
3. Then open the key and compare.

---

## 6. Reporting

Please report your results as a GitHub issue or attached document including:

- Your score sheet (anonymised if preferred)
- A summary of matches, divergences, and ambiguities
- Any steps that were difficult to follow or impossible to reproduce
- Any suggested clarifications to the rubric or instructions

You do not need to agree with any interpretation — only report whether the method behaves consistently in your hands.

---

## 7. Scope Reminder

This analysis is **structural only**. Do not attempt to:

- Assign linguistic meaning to units or sequences
- Transliterate sequences into any natural language
- Speculate about authorship or origin

Any such interpretation falls outside the scope of this replication task.
