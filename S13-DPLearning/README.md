[Lab home](../README.md) · [Practical catalogue](../README.md#practical-catalogue) · [Course session](https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S13-DPLearning)

# S13A — Private Naive Bayes and utility

**Status: planned PaDS practical.** An upstream exercise is available; a PaDS
notebook and tested runtime have not yet been added.

## Source exercise

[Modern Data Science / SIT742 M06A — IBM Differential Privacy Library in 30 Seconds](https://github.com/tulip-lab/SIT742/blob/4bc4358db937faae99e05edf2e2b3426c1e3fef1/Jupyter/M06-Advanced/M06A-IBMDP-30Seconds.ipynb)
fits a differentially private Gaussian Naive Bayes classifier to the public
Iris dataset and compares accuracy at different epsilon values.

The link records the public version reviewed on 27 October 2026. Follow its
online or local setup instructions; it remains a SIT742 notebook.

## Place in PaDS

- Prerequisites: basic classification and train/test splits, S04 differential
  privacy, and S05 composition/accounting.
- Main connection:
  [S13 — DP Learning](https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S13-DPLearning).
- Learning outcomes: ULO1 (understand DP principles) and ULO2 (apply DP methods).
- Suggested earlier practical:
  [S05A — Private exploration and budget accounting](../S05-Composition/README.md).

## Planned learning activity

1. Explain the public feature bounds and what the classifier protects.
2. Fit the private classifier and compare several epsilon values.
3. Add a non-private classifier as a utility baseline.
4. Repeat the comparison to describe variability rather than relying on one run.
5. Explain how repeated fits/releases would consume budget on protected data.

Keep an experiment table, a privacy/utility plot, a baseline comparison and a
short explanation of the assumptions. The executed non-private baseline and
repeated-run summary are planned PaDS extensions to the source exercise.

## PaDS teaching focus

Iris is public teaching data. Classroom parameter sweeps are not evidence of a
single private deployment budget. Training privacy also does not automatically
protect sensitive test-set evaluation outputs.

The upstream notebook uses reproducible classroom random seeds; deployment
randomness and cumulative accounting need separate consideration. The PaDS
adaptation and its execution checks are still to be completed.

References: [diffprivlib Gaussian Naive Bayes](https://diffprivlib.readthedocs.io/en/latest/modules/models.html)
and [privacy accounting](https://diffprivlib.readthedocs.io/en/latest/modules/accountant.html).
