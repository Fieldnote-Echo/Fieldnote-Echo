# Hey, I'm Nelson.

[![OpenHands - Contributor](https://img.shields.io/badge/OpenHands-Contributor-0078D6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenHands/OpenHands/pulls?q=is%3Apr+author%3AFieldnote-Echo+is%3Amerged)
[![Software Agent SDK - Contributor](https://img.shields.io/badge/Agent_SDK-Contributor-0078D6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenHands/software-agent-sdk/pulls?q=is%3Apr+author%3AFieldnote-Echo+is%3Amerged)
[![Mathlib - Contributor](https://img.shields.io/badge/Mathlib-Contributor-50237C?style=for-the-badge&logo=lean&logoColor=white)](https://github.com/leanprover-community/mathlib4/pulls?q=is%3Apr+author%3AFieldnote-Echo+is%3Aclosed+label%3Aready-to-merge)

I map failure patterns across complex systems and build the security boundaries required to stabilize them.

I'm the founder of [Project Navi](https://github.com/Project-Navi) - an open-source AI security company focused on zero trust architecture and mathematical governance. Before that, I spent seven years in behavioral health research, coordinating peer-support programs across 500+ organizations and publishing on workforce collapse in the APA Psychiatric Rehabilitation Journal.

The same structural breakdowns I studied in human systems - drift under pressure, coherence loss at scale, collapse when governance is bolted on instead of built in - show up in AI deployments. So I started building infrastructure to prevent them.

---

## What I'm Building

### [takens-formalization](https://github.com/Project-Navi/takens-formalization)
**Takens' theorem for generic pairs, machine-checked.** On a compact smooth d-manifold, the pairs (T, h) of a C² diffeomorphism and a C² observation whose delay map with 2d+1 coordinates is a C² embedding are **open and dense** in Diff²(M) × C²(M, ℝ). Also finite-regularity Sard (via a port of Moreira's theorem), exact finite-state horizons and ordinal codes. Lean 4 + Mathlib v4.34.1; **no `sorry`, standard axioms only**.

### [fd-formalization](https://github.com/Project-Navi/fd-formalization)
**Box-counting dimension of the (u,v)-flowers, machine-checked.** For 1 < u ≤ v, the Rozenfeld–Havlin–ben-Avraham flowers have dimension log(u+v)/log u: as the limit of their recurrences, as a log-ratio of the explicit graphs, and as a box-counting dimension over minimum box covers **at every resolving scale**. Lean 4 + Mathlib v4.34.1; **no `sorry`, standard axioms only**.

### [cd-formalization](https://github.com/Project-Navi/cd-formalization)
**Existence theory for the Creative Determinant** boundary value problem −ΔΦ = a|∇Φ| + bΦ − c(Φ₊)ᵖ. On finite weighted graphs, a positive solution is **fully proved**; the continuum results are conditional on explicit, documented elliptic hypotheses. Lean 4 + Mathlib v4.34.1; standard axioms only. Theory in the [paper](https://github.com/Project-Navi/navi-creative-determinant/blob/main/paper/creative_determinant.pdf).

### [navi-sanitize](https://github.com/Project-Navi/navi-sanitize)
Deterministic **input sanitization for untrusted text** in LLM pipelines. Strips homoglyphs, invisible Unicode, null bytes, template injection, and path traversal vectors. **Zero dependencies**. Python 3.12+. Live on [PyPI](https://pypi.org/project/navi-sanitize/).

---

## Open Source Contributions

* **OpenHands:** Disclosed a CVSS 9.1 security vulnerability; wrote and merged the fix into `main`. Contributed defense-in-depth SecurityAnalyzer ensemble.
* **Mathlib:** Contributed SimpleGraph.ball (open metric ball).
* **NIST and NCCoE:** Submitted responses on AI agent identity, authorization, and adversarial prompt detection ([Zenodo](https://zenodo.org/records/18764051)).

---

## Get In Touch

- Security: [security@projectnavi.ai](mailto:security@projectnavi.ai)
- Legal: [legal@projectnavi.ai](mailto:legal@projectnavi.ai)
- PGP: [`/.well-known/pgp-key.txt`](https://www.projectnavi.ai/.well-known/pgp-key.txt) (fingerprint: `402E C296 1A72 CBFF 63B8 FEE9 A42A 76A1 C696 FF08`)
- Sponsor my work: [GitHub Sponsors](https://github.com/sponsors/Fieldnote-Echo)

---

*Machine cognition, human values.*

> *The knowledge is free, the community is open. If you wish to support our mission, [buy a t-shirt](https://projectnavi.printful.me/).* 🐘
