# Submission scaffold — Classical and Quantum Gravity

**Title:** On the Status of Local Entropy-Current Extensions of the Gravitational Entropy Escrow Framework: A Clarification Note

**Author:** Grant Lavell Whitmer III, The Windstorm Institute, Fort Ann, NY 12827, USA · grantwhitmer3@gmail.com

**Topic area:** Bekenstein bound · Horizon thermodynamics · Foundations of entropic / emergent gravity · Methodology

---

## Cover note

This is a short clarification note attached to a longer companion paper, *Gravitational Entropy Escrow* (Whitmer 2026), under separate submission to CQG.

The note documents the resolution of a candidate covariant extension proposed during AI-assisted exploration of the parent framework's open problem (§7.6 of the parent paper, *derive Λ_eff(τ) from horizon thermodynamics*). The candidate equation, designated C8, has the form `∇_μ J_S^μ = (2π k_B / ℏ) · ε_bind` and balances dimensionally. With standard energy-density conventions and light-crossing-time integration it reproduces both Bekenstein–Hawking and Gibbons–Hawking entropies exactly.

We show that this recovery is *algebraically identical* to the saturated Bekenstein bound (Bekenstein 1981); since horizons saturate the bound by construction, the result is a consistency check rather than new physics. The choice of integration time is post-hoc; other natural horizon time scales (Hawking evaporation, inverse surface gravity, free-fall) yield wildly different answers. C8 therefore is not a viable independent extension.

We submit this clarification because we believe documenting a negative result of this character — and the dimensional/convention chain that complicated reaching it — is a contribution in its own right. The methodology section (§7) documents an AI-dialogue case study in which three of four LLM systems were confidently wrong at various points; resolution required independent first-principles calculation against Planck 2018 published values, not further LLM review. We anticipate the methodology will be useful to readers operating similar adversarial-review pipelines.

The parent paper's interpretive content is unaffected. Its central open problem (the order-unity coefficient `α ≈ 1.34` in the deep-MOND interpolation) is not addressed by C8 in either direction.

---

## What's in this repo

- `paper.pdf` — full manuscript (v0.3.1)
- `paper/Paper12-v0.3.1-source.txt` — extracted-text mirror
- `paper-arxiv.tex` — arXiv submission scaffold

## Compatibility note for CQG style

Short note format: introduction, three derivation sections, methodology section, conclusion, references. No figures. One central derivation (§3 — C8 with `t = R/c` reduces to the Bekenstein bound). Intended as a comment-style submission attached to the parent CQG submission of the escrow framework.
