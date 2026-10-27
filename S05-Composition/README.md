[Lab home](../README.md) · [Practical catalogue](../README.md#practical-catalogue) · [Course session](https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S05-Composition)

# S05A — Private exploration and budget accounting

**Status: planned PaDS practical.** An upstream exercise is available; a PaDS
notebook and tested runtime have not yet been added.

## Source exercise

[Modern Data Science / SIT742 M06B — IBM Differential Privacy for Exploration](https://github.com/tulip-lab/SIT742/blob/4bc4358db937faae99e05edf2e2b3426c1e3fef1/Jupyter/M06-Advanced/M06B-IBMDP-Exploration.ipynb)
uses `diffprivlib` for private histograms and summary statistics with a privacy
budget accountant. It supports Covertype data and a labelled synthetic fallback.

The link records the public version reviewed on 27 October 2026. Follow its
online or local setup instructions; it remains a SIT742 notebook.

## Place in PaDS

- Prerequisites: Python/NumPy, basic descriptive statistics and
  [S04 — Differential Privacy](https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S04-DifferentialPrivacy).
- Main connection:
  [S05 — Composition](https://github.com/tulip-lab/privacy-aware-data-science/tree/develop/S05-Composition).
- Learning outcomes: ULO1 (understand DP principles) and ULO2 (apply DP methods).

## Planned learning activity

1. State the protected unit, adjacency assumption and public feature bounds.
2. Plan a small set of statistical queries before running them.
3. Produce private histograms and summary statistics.
4. Record cumulative spend before and after another query.
5. Explain what happens when the planned budget is exhausted.

Keep a query table, selected plots, accountant outputs and a short explanation
of the privacy/utility trade-off. Record whether real public data or the
synthetic fallback was used; synthetic results do not describe Covertype.

## PaDS teaching focus

Recreating an accountant resets its software state, not privacy loss from
already released results. Repeated releases involving the same protected data
must be accounted for together. Public or synthetic teaching data lets us
explore alternative plans without claiming a real deployment guarantee.

This practical will connect the library's accounting behaviour to S05 theory.
The PaDS adaptation and its execution checks are still to be completed.

Reference: [diffprivlib privacy budget accountant](https://diffprivlib.readthedocs.io/en/latest/modules/accountant.html).
