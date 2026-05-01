# Blinded Tests — Sigilith v1.0

**Version:** 1.0  
**Framework DOI:** <https://doi.org/10.17613/dkgpg-xbj95>

---

## Purpose

Blinded batches allow analysts to test the **stability** of their scoring under conditions where the expected output is unknown at time of scoring. This tests analyst-level reproducibility independently of any familiarity with the benchmark sequences.

Each batch contains sequences drawn from the same source documents as the benchmark set, but at different locations not included in `benchmark-set/`.

---

## Instructions

1. Complete the full benchmark set (`benchmark-set/`) and compare to the evaluator key before opening any blinded batch.
2. Choose **one** blinded batch (Batch A, B, or C). Do not score more than one batch unless you are conducting a formal multi-analyst stability study.
3. Score all sequences in the chosen batch using the same procedure and rubric as for the benchmark set.
4. Record all scores before consulting any answer.
5. Submit your blinded scores together with your benchmark scores in your replication report.

> **Note:** Blinded batch answer keys will be released by the author upon request, after receipt of a completed replication report. Contact via GitHub issue.

---

## Batch Index

| File | Batch ID | Sequences | Source Documents |
|---|---|---|---|
| `batch-A.md` | Batch A | BL-A01 – BL-A05 | Voynich MS, Rohonc Codex |
| `batch-B.md` | Batch B | BL-B01 – BL-B05 | McCormick Notes, Phaistos Disc |
| `batch-C.md` | Batch C | BL-C01 – BL-C05 | Liber Linteus, Turin Papyrus |

---

## Scope

All blinded sequences are provided for **structural analysis only**. No linguistic, semantic, or decipherment claims are made or implied.
