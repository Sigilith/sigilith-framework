# Evaluator Key — Sigilith v1.0

**Version:** 1.0  
**Framework DOI:** <https://doi.org/10.17613/dkgpg-xbj95>

> **Instructions for analysts:** Do not open this file until you have completed and recorded your own scores for all selected sequences. Consulting this key before scoring will invalidate your replication.

---

## How to Use This Key

1. Compare your score for each criterion to the expected score in the table below.
2. Record **Match**, **Divergence**, or **N/A** for each criterion.
3. Note the magnitude of any divergence (e.g., "−1 on Criterion 2").
4. Report your comparison in the replication issue or attached document.

A total score within **±1 point** of the expected total is considered a match (see rubric tolerance definition).

---

## Expected Scores by Benchmark Sequence

### BM-001 — Voynich Manuscript f1r, Line 1

| Criterion | Expected Score | Max |
|---|---|---|
| 1 — Segmentation Accuracy | 3 | 3 |
| 2 — Unit Classification Accuracy | 3 | 3 |
| 3 — Positional Role Assignment | 2 | 2 |
| 4 — Internal Consistency | 2 | 2 |
| 5 — Procedural Adherence | 2 | 2 |
| **Total** | **12** | **12** |

**Notes:** This sequence is the primary calibration sequence. All unit boundaries are unambiguous. Analysts scoring below 10 should re-read §3.1 of the methods paper before proceeding.

---

### BM-002 — Voynich Manuscript f2r, Line 3

| Criterion | Expected Score | Max |
|---|---|---|
| 1 — Segmentation Accuracy | 3 | 3 |
| 2 — Unit Classification Accuracy | 2 | 3 |
| 3 — Positional Role Assignment | 2 | 2 |
| 4 — Internal Consistency | 2 | 2 |
| 5 — Procedural Adherence | 2 | 2 |
| **Total** | **11** | **12** |

**Notes:** Unit at position 4 is a known boundary case between two adjacent classes. A score of either class is acceptable; a Criterion 2 score of 3 is also acceptable for this sequence if the analyst documents their reasoning.

---

### BM-003 — Rohonc Codex p.12, Line 2

| Criterion | Expected Score | Max |
|---|---|---|
| 1 — Segmentation Accuracy | 3 | 3 |
| 2 — Unit Classification Accuracy | 3 | 3 |
| 3 — Positional Role Assignment | 2 | 2 |
| 4 — Internal Consistency | 2 | 2 |
| 5 — Procedural Adherence | 2 | 2 |
| **Total** | **12** | **12** |

**Notes:** Cross-document calibration sequence. Tests whether analysts apply the taxonomy consistently across source documents.

---

### BM-004 — McCormick Notes, Sheet 3, Row 1

| Criterion | Expected Score | Max |
|---|---|---|
| 1 — Segmentation Accuracy | 2 | 3 |
| 2 — Unit Classification Accuracy | 3 | 3 |
| 3 — Positional Role Assignment | 2 | 2 |
| 4 — Internal Consistency | 2 | 2 |
| 5 — Procedural Adherence | 2 | 2 |
| **Total** | **11** | **12** |

**Notes:** One unit boundary is genuinely ambiguous (positions 6–7). A Criterion 1 score of 2 or 3 are both acceptable. See methods paper §3.1, Ambiguity Protocol.

---

### BM-005 — Phaistos Disc, Side A, Ring 1

| Criterion | Expected Score | Max |
|---|---|---|
| 1 — Segmentation Accuracy | 3 | 3 |
| 2 — Unit Classification Accuracy | 3 | 3 |
| 3 — Positional Role Assignment | 2 | 2 |
| 4 — Internal Consistency | 2 | 2 |
| 5 — Procedural Adherence | 2 | 2 |
| **Total** | **12** | **12** |

**Notes:** High-distinctiveness sequence; boundary cases are minimal. Useful as a positive control.

---

### BM-006 — Liber Linteus, Column 1, Line 4

| Criterion | Expected Score | Max |
|---|---|---|
| 1 — Segmentation Accuracy | 3 | 3 |
| 2 — Unit Classification Accuracy | 2 | 3 |
| 3 — Positional Role Assignment | 1 | 2 |
| 4 — Internal Consistency | 2 | 2 |
| 5 — Procedural Adherence | 2 | 2 |
| **Total** | **10** | **12** |

**Notes:** This sequence deliberately tests the positional labelling rule for medial singleton clusters (see methods paper §3.3). Analysts frequently assign T instead of M for the final cluster; a score of 1 on Criterion 3 is expected.

---

### BM-007 — Turin Papyrus, Column 2, Line 1

| Criterion | Expected Score | Max |
|---|---|---|
| 1 — Segmentation Accuracy | 3 | 3 |
| 2 — Unit Classification Accuracy | 3 | 3 |
| 3 — Positional Role Assignment | 2 | 2 |
| 4 — Internal Consistency | 2 | 2 |
| 5 — Procedural Adherence | 2 | 2 |
| **Total** | **12** | **12** |

**Notes:** Standard sequence; no known ambiguities. Used as a terminal calibration check.

---

## Summary Table

| Sequence ID | Source Document | Expected Total | Max |
|---|---|---|---|
| BM-001 | Voynich MS f1r L1 | 12 | 12 |
| BM-002 | Voynich MS f2r L3 | 11 | 12 |
| BM-003 | Rohonc Codex p.12 L2 | 12 | 12 |
| BM-004 | McCormick Notes S3 R1 | 11 | 12 |
| BM-005 | Phaistos Disc A R1 | 12 | 12 |
| BM-006 | Liber Linteus C1 L4 | 10 | 12 |
| BM-007 | Turin Papyrus C2 L1 | 12 | 12 |

---

## Divergence Reporting

If your score diverges from an expected score, please document:

- The sequence ID and criterion number
- Your score vs. the expected score
- The specific unit(s) or step(s) where you diverged
- Whether the divergence reflects ambiguity in the rubric, ambiguity in the instructions, or a difference in interpretation

All divergences — including those within the ±1 tolerance — are informative and welcome.
