# Supplementary Proofs for Sections V and VI

This folder contains the proofs of Lemmas 1–8 of the main paper, together with the general norm bounds, key-generation cutoff analysis, and finite-precision sampling arguments used by the security reductions.

## Files

- [Read the PDF](%E2%85%A4%5C%E2%85%A5.pdf).
- [View the LaTeX source](%E2%85%A4%5C%E2%85%A5.tex).

## Contents

| Local section | Main-paper lemma | Subject |
| --- | --- | --- |
| A | Lemma 1 | Key conditioning, norm rejection, invertibility, and the key-generation cutoff |
| B | Lemma 2 | Normal form of MSIS |
| C | Lemma 3 | Accepting cyclic transcripts |
| D | Lemma 4 | Signing simulation in the ROM, response-norm bounds, and finite-precision sampling |
| E | Lemma 5 | Extraction at one commitment |
| F | Lemma 6 | Forking a cyclic challenge chain |
| G | Lemma 7 | Many-time auxiliary authentication |
| H | Lemma 8 | A new tag for a registered ring |

## Where the manuscript uses this material

- **Section V, Setup; footnote 1:** the general key- and response-norm choices in Sections A and D. The tighter finite-profile alternatives are in the companion [Ⅴ\Ⅶ folder](../%E2%85%A4%5C%E2%85%A6/).
- **Section VI-B, Security Proof; footnote 2:** the complete proofs of Lemmas 1–8 in Sections A–H.
- **Section VI-B, Security Proof; footnote 3:** the sufficient norm bounds and their derivations in Sections A and D.

## Equation guide

Within this PDF, Equation (1) gives the sufficient key-norm choice, Equation (4) gives the sufficient response-norm choice, and Equation (5) gives the finite-precision error budget. These numbers belong to this PDF.

The sharper finite-profile bounds use the general norm analysis in Sections A and D. The [operation-budget document](../%E2%85%A6/%E2%85%A6.pdf) uses the sampling-error budget derived in Section D.

[Return to the repository overview](../README.md).
