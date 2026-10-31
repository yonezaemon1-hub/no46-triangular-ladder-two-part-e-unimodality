# No.46 — Publication metadata and release checklist (2026-10-31)

**Status at package creation:** Files prepared and verified. Neither GitHub Release nor Zenodo record has been created by this session. Never describe these as published until public URLs have been read back.

## GitHub

Suggested repository name: `no46-triangular-ladder-two-part-e-unimodality`
Visibility: **Public**
Description: `A proof of two-part e-unimodality for triangular-ladder chromatic quasisymmetric functions, with audited derivations and verification scripts.`
Default branch: main
Release tag: `v1.0`
Release title: `No.46 — Two-Part e-Unimodality of Triangular Ladders (Preprint v1.0)`

Attach exactly these files as release assets (do not rename them after hash freeze):
- `No46_Triangular_Ladder_Two_Part_e_Unimodality_Preprint_v1_0.pdf`
- `No46_Triangular_Ladder_Reproducibility_v1_0_20261031.zip`

Release body:

> Preprint and independent-verification materials for a theorem asserting nonnegative, palindromic, unimodal coefficients for all two-part partitions in the e-expansion of the chromatic quasisymmetric functions of triangular ladders P_n^2. Scope: n >= 3 and 1 <= k <= floor(n/2). This does not establish full e-unimodality. Mathematical proof: independently AI-audited (conditional on the cited Tom Proposition 5.3 and Lemma 3.13); not human peer reviewed. Novelty INCONCLUSIVE: no identical theorem found among inspected literature, but no priority claim. Copyright (c) 2026 Ryutaro Yonezu. All rights reserved.

## Zenodo

Resource type: Publication / Preprint  
Title: `Two-Part e-Unimodality of the Chromatic Quasisymmetric Functions of Triangular Ladders`  
Creator: `Yonezu, Ryutaro`  
Affiliation: `Independent Researcher`  
Publication date: `2026-10-31` (use actual publish date if later)  
Language: English  
Keywords: `chromatic quasisymmetric function; triangular ladder; e-unimodality; symmetric functions; transfer matrix; decreasing trees`  
Rights: **All rights reserved** (do not select a permissive Creative Commons or software license). Make record metadata public and PDF/ZIP public.

Description / Abstract:

> Let G_n=P_n^2 be the square of the path on n vertices (the triangular ladder). We prove that for every n>=3 and 1<=k<=floor(n/2), the two-part elementary-symmetric coefficient [e_(n-k,k)] X_(G_n)(x;q) is nonnegative, palindromic, and unimodal. The argument combines Foster Tom's decreasing-tree expansion (Proposition 5.3 and Lemma 3.13), a four-state transfer matrix, formal coefficient extraction, and symmetric-unimodal positive decompositions. The statement is restricted to two-part coefficients and does not resolve full e-unimodality. Computational verification and an independent AI-assisted adversarial proof audit were performed; there has been no human peer review. Novelty remains INCONCLUSIVE because the literature comparison is not exhaustive, including the full published 2019 SIAM Cho-Huh text. Copyright 2026 Ryutaro Yonezu. All rights reserved.

Files: the same frozen PDF and ZIP as the GitHub Release. No DOI has been reserved or issued at package creation.

## Publish sequence

1. Create GitHub public repository with the name above, add README, original manuscript PDF, license notice, and reproduction archive or its important text files.
2. Create Release v1.0 and attach the **frozen, hash-matched** PDF and ZIP.
3. On Zenodo: new upload => Publication / Preprint => same PDF and ZIP => metadata above => All rights reserved => publish. Take the resulting DOI from the published record, not a guess.
4. Re-download PDF and ZIP from both public websites; compare their SHA256 with local manifest.
5. Update Google Drive `論文一覧` No.46 with the *observed* GitHub URL, release URL, Zenodo DOI, metadata, and actual publication status.

## SHA256 of frozen files

6c762e9b8b48c5f370b72fd3756450872bafe4570697a4ffb17059b1e312b9a8  No46_Triangular_Ladder_Two_Part_e_Unimodality_Preprint_v1_0.pdf
378ec07bc767967080c2b42124b372449d7bc0ca332fcf9ce6b94443b0111e88  No46_Triangular_Ladder_Reproducibility_v1_0_20261031.zip
