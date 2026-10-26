# Finite-Budget Operation Count and Error Propagation

This folder contains the supporting calculations for the **Finite-budget illustration in Section VII-B1** of the main paper. This material was originally Appendix J.

## Files

- [Read the PDF](%E2%85%A6.pdf).
- [View the LaTeX source](%E2%85%A6.tex).

## Contents

- The definition of an approximate sampling operation and its per-operation total-variation error premise.
- An upper bound on the operation count across key generation, signing attempts, oracle processing, and the comparison games used by the reductions.
- The operation budget used for the finite-profile illustration.
- Conditional propagation of sampling, collision, cutoff, simulation, and hash-guessing terms through Theorems 1–4.
- The primitive-advantage bounds required by the displayed numerical example and a comparison with a wider query envelope.

## Where the manuscript uses this material

**Section VII-B1, Finite-budget illustration; footnote 5** refers to the operation-count derivation and the propagation of comparison terms in this document.

The calculations use the query budgets, per-operation total-variation premise, and NTWE/MSIS advantage terms stated in the manuscript.

## Companion derivations

The finite-precision relation $\delta_{\rm samp}\le R2^{-b}$ is derived in Section D of the [proof document for Sections V and VI](../%E2%85%A4%5C%E2%85%A5/%E2%85%A4%5C%E2%85%A5.pdf), where it is Equation (5).

The sharper norm-tail and invertibility bounds used in the numerical propagation are supplied in the [Ⅴ\Ⅶ folder](../%E2%85%A4%5C%E2%85%A6/).

[Return to the repository overview](../README.md).
