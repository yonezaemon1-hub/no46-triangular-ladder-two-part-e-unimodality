# No.46 — Two-part e-unimodality of triangular ladders

Author: Ryutaro Yonezu — Independent Researcher  
Version: 2026-10-31 preprint v1.0  
Rights: All rights reserved  
Human peer review: not conducted  
Novelty: INCONCLUSIVE  
Scope: only two-part coefficients; no claim to full e-unimodality.

## Theorem

For every `n >= 3`, `1 <= k <= floor(n/2)`, the two-part
coefficient `[e_(n-k,k)] X_(P_n^2)(x;q)` is nonnegative,
palindromic and unimodal. Zero coefficients: `(3,1)`, `(4,2)`.

The proof **depends on** Foster Tom (2025), Proposition 5.3,
(5.3)-(5.5) and equal-parts exception, and Lemma 3.13.
The journal-style typesetting is in `source/paper.tex`; the matching
PDF is supplied separately alongside this archive.

## Reproduction

`audit_v0_4/` is the *unchanged*, previously audited v0.4 support
packet (except compiled Python caches, which are excluded).
It retains its own `SHA256SUMS.txt` and original `run_all.py`.
To verify, with Python and sympy installed:

    cd audit_v0_4
    python -I check_hashes.py
    python -I run_all.py

To check files in THIS publication archive, from its root:

    sha256sum -c SHA256SUMS.txt

Finite checks from v0.4: 124/124 algebra claims, 55/55 forests,
495/495 generating function/formulas, 15/15 direct-coloring
coefficients, symbolic transfer and extraction checks PASS. The
first three scripts share code and are not independent.
Independent colorings/basis conversion are in `check_coloring_basis.py`.
Finite checks do not prove the theorem; the general proof is given in
the manuscript and in the preserved audit draft.

## Audit and priority status

An AI-assisted independent adversarial audit by Claude dated
2026-10-31 reported mathematical PASS of the v0.4 changes,
conditional on Tom's cited results. No human peer review was performed.
The external `No46_Claude_Audit_Scripts.zip` was not provided to this
packaging environment and is not included or claimed rerun.
The typeset `source/paper.tex` has not itself received a new independent
differential audit; it follows the mathematics in v0.4.

A literature review found no identical result in checked sources.
However, full theorem-by-theorem review of the published 2019 SIAM
Cho-Huh version was not completed; novelty is INCONCLUSIVE.
The 2018 conference edition was compared directly. It would be wrong
to assert that the full conjecture was solved.
