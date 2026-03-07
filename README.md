# Hey, I'm Nelson.

I map failure patterns across complex systems and build the security boundaries required to stabilize them.

I'm the founder of [Project Navi](https://github.com/Project-Navi) - an open-source AI security company focused on zero trust architecture and mathematical governance. Before that, I spent seven years in behavioral health research, coordinating peer-support programs across 500+ organizations and publishing on workforce collapse in the APA Psychiatric Rehabilitation Journal.

The through-line is failure analysis. The same structural breakdowns I studied in human systems - drift under pressure, coherence loss at scale, collapse when governance is bolted on instead of built in - show up in AI deployments. So I started building infrastructure to prevent them.

---

## What I'm Building

### [cd-formalization](https://github.com/Project-Navi/cd-formalization)
**Machine-verified proof** that self-sustaining coherence configurations exist in nonlinear elliptic PDE systems - formalizing, for the first time, the mathematical conditions under which autopoietic closure can emerge. Lean 4 against Mathlib v4.28.0. **Fifteen theorems proved, zero sorry (no unfinished proofs), 3000+ build jobs clean.** Where Mathlib lacks infrastructure (Schauder estimates, maximum principles, sub/super-solution theory), the axiom boundary is explicit and auditable via a **single typeclass**. Algebraic core proofs were synthesized using Aristotle (Harmonic) - human architecture, machine search, **compiler as final arbiter**. The underlying theory is in the [paper](https://github.com/Project-Navi/navi-creative-determinant/blob/main/paper/creative_determinant.pdf).

### [fd-formalization](https://github.com/Project-Navi/fd-formalization)
**Machine-verified proof** that the log-ratio of vertex count to hub distance converges to log(u+v)/log(u) for the (u,v)-flower graph family - the quantity that equals box-counting fractal dimension in the physics literature (Rozenfeld, Havlin & ben-Avraham 2007). Lean 4 against Mathlib v4.28.0. **Zero sorry, zero custom axioms, 1900+ build jobs clean.** Pure arithmetic proof spine - no SimpleGraph in the critical path. Squeeze-sandwich convergence via Filter.Tendsto. This is the ground truth that [navi-fractal](https://github.com/Project-Navi/navi-fractal) calibrates against.

### [navi-sanitize](https://github.com/Project-Navi/navi-sanitize)
Deterministic **input sanitization for untrusted text** in LLM pipelines. Strips homoglyphs, invisible Unicode, null bytes, template injection, and path traversal vectors. **Zero dependencies**. Python 3.12+. Live on [PyPI](https://pypi.org/project/navi-sanitize/).

### [grippy](https://github.com/Project-Navi/grippy-code-review)
AI-powered PR review agent with a **deterministic security rule engine**. Indexes your codebase into a **knowledge graph** for context-aware analysis. Runs security rules before the model touches the diff. Structured findings, severity scores, pass/fail verdicts. Works with any model.

### [navi-bootstrap](https://github.com/Project-Navi/navi-bootstrap)
Spec-driven repo scaffolding that ships CI, security scanning, code review, and release pipelines in a single command. Jinja2 engine with 7 template packs. **Define your standards once, apply them everywhere**. Python 3.12+. Live on [PyPI](https://pypi.org/project/navi-bootstrap/).

### [navi-fractal](https://github.com/Project-Navi/navi-fractal)
Audit-grade **fractal dimension estimator** for complex networks with refusal semantics - if the evidence for power-law scaling isn't there, you get a machine-readable refusal, not a meaningless number. Sandbox method with four quality gates: R² threshold, AICc model selection, curvature guard, slope stability. **Zero dependencies**. Calibrated against networks with exact analytical dimensions from [fd-formalization](https://github.com/Project-Navi/fd-formalization). Python 3.12+.

---

## Open Source Contributions

![OpenHands Contributor](https://img.shields.io/badge/OpenHands-Contributor-blue?logo=github)
* **OpenHands (All-Hands AI):** Disclosed a CVSS 9.1 security vulnerability; wrote and merged the fix into `main`.
* **OpenSSF Scorecard:** Contributed to supply-chain security metrics (PR awaiting review).
* **NIST and NCCoE:** Submitted responses on AI agent identity, authorization, and adversarial prompt detection ([Zenodo](https://zenodo.org/records/18764051)).

---

## The Deeper Framework

The tools are the entry point. Underneath them is a mathematical governance framework built on three foundations:

**Differential Symbolic Calculus (DSC)** - Measurement framework for detecting coherence-exploration coupling in dynamical systems. Instrumentation, not simulation.

**World Model Capital (WMC)** - Trust-allocation system adapting Recovery Capital frameworks from behavioral health to AI governance. Trust capital for machine cognition.

**Relational Emergent Ontology (REO)** - Philosophical foundation where intelligence is event, identity is rhythm, ethics is resonance.

You don't need to understand any of this to use the tools. But if you're curious - I started here because the principles that help people recover help systems stay whole.

---

## Get In Touch

- Security: [security@projectnavi.ai](mailto:security@projectnavi.ai)
- Licensing: [legal@projectnavi.ai](mailto:legal@projectnavi.ai)
- PGP: [`/.well-known/pgp-key.txt`](https://www.projectnavi.ai/.well-known/pgp-key.txt) (fingerprint: `402E C296 1A72 CBFF 63B8 FEE9 A42A 76A1 C696 FF08`)
- Sponsor my work: [GitHub Sponsors](https://github.com/sponsors/Fieldnote-Echo)

---

*Machine cognition, human values.*

> *The knowledge is free, the community is open. If you wish to support our mission, [buy a t-shirt](https://projectnavi.printful.me/).* 🐘
