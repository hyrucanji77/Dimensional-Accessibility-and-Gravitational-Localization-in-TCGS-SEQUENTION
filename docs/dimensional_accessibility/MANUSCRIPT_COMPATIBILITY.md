# Manuscript and computational-release compatibility

## Current association

The current article is **Dimensional Accessibility and Gravitational Localization: Spectral Response, Boundary Stability, and Constitutive Constraints in TCGS–SEQUENTION**, **v4.2 Final**, by Henry Arellano-Peña. It contains **45 pages and 29 numbered references**. The manuscript sources and PDF are not distributed in this computational repository.

The associated software remains **computational release 4**, containing three suites with **186 + 225 + 118 = 529 numerical checks** and **nine separate unit tests**. No scientific code, test, dependency pin, numerical input, or result record changes with this documentation update. The scientific checksum manifest is retained unchanged.

## Immutable computational snapshots

- Dedicated repository: [`d8c5ade46c0c47ceaa2408f7965ae58402e5b479`](https://github.com/hyrucanji77/Dimensional-Accessibility-and-Gravitational-Localization-in-TCGS-SEQUENTION/tree/d8c5ade46c0c47ceaa2408f7965ae58402e5b479).
- Original complete protocol release: [`1353cf54a94cfb6f3923a1f2a9c467d9eff68afa`](https://github.com/hyrucanji77/TCGS-SEQUENTION-protocol/tree/1353cf54a94cfb6f3923a1f2a9c467d9eff68afa).

These are the computational snapshots cited in manuscript reference [18]. Both remain valid and unchanged. The original release-associated manuscript had **41 pages and 27 references**; those historical values are correct for that association. A new documentation commit does not replace or rewrite either pinned commit.

## Version fields

`CITATION.cff` describes the software and therefore retains `version: "4"`. Its message and abstract identify compatibility with the current article. `release.json` retains the historical top-level fields for compatibility and explicitly labels their scope. Its `current_manuscript` object records **v4.2 Final, 45 pages, 29 references**, while `original_release_manuscript` records the original **v4, 41-page, 27-reference** association.

`REFERENCES.md` now follows the final manuscript's full 29-entry bibliography. References [28] and [29] document the cosmological scale comparison and the established nonlinear conformally invariant Poisson theory, respectively. Reference [18] states that the version 4 computational release is retained unchanged for the final article.

## Analytical material outside the numerical-check count

Appendix F.4, **Constitutively generated scales and scale-covariant response**, including Proposition F.1 and Equations (89)–(95), is analytical. It treats the induced metric and operational distance, the restricted spatial-dilation selection of a cubic-gradient functional, its variational equation, its conformal property, and spherical-source scaling under the stated assumptions.

These arguments are established in the manuscript and are **not included in the 529 numerical checks**. The repository does not claim that the scripts certify those proofs or derive the full source-to-Shadow matching relation. The source's established nonlinear-Poisson theory is credited to Milgrom in reference [29].

## Integrity and execution status

The published numerical and software-test summaries retain their original execution provenance. This documentation update records compatibility; it does not assert a new execution of the numerical suites. To reproduce the calculations, follow [REPRODUCIBILITY.md](REPRODUCIBILITY.md). To check the distributed scientific files from the repository root, run:

```sh
sha256sum -c SHA256SUMS.txt
```

The existing manifest covers the scientific scripts, tests, dependency pins, scoped code license, and selected result records, not repository-specific prose or itself. Git identifies the documentation revision. Cite the full revision used alongside the appropriate manuscript version; the earlier computational pins remain the article's fixed references.

No manuscript LaTeX files, generated TeX tables, Overleaf archives, or reference PDFs are added by this update.
