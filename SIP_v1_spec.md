# SIP v1 — Structural Integrity Protocol (Operator-Grade Spec)

## Purpose
SIP evaluates whether an artifact (human, AI, or human–AI output) is decision-grade rather than merely narrative-grade.

Designed for:
- Internal decision artifacts
- Analysis intended to guide action
- Governance, operations, strategy, risk, and audit workflows
- Evaluating AI-assisted work quality

Not designed for:
- Public thought leadership evaluation
- Writing style judgment
- Creative writing
- Marketing content

Public artifacts often score low due to institutional constraints, not weak cognition.

---

## Core Dimensions (PQC)

Each artifact is scored on three dimensions (0–2).

### P — Problem Constraint Clarity
Does the artifact specify real constraints or decision boundaries?

0: No constraints. Vague intent only.  
1: Scope defined but constraints are soft or implicit.  
2: Explicit constraints (time, cost, thresholds, resources, decision rules).

Examples of P2:
- “If CAC exceeds $120, pause this channel.”
- “Decision required by end of Q3 within $50k budget.”

---

### Q — Interrogation / Falsifiability
Does the artifact challenge its own assumptions? Does it define what would make it wrong?

0: No challenge. One-sided narrative.  
1: Mentions risks but no testable criteria.  
2: Explicit falsification logic or stress-testing criteria.

Examples of Q2:
- “If retention < 30% after 60 days, hypothesis fails.”
- “We will run A/B test; if no uplift, strategy is rejected.”

---

### C — Synthesis / Entropy Reduction
Does the artifact reduce ambiguity and improve actionability?

0: Adds noise or confusion.  
1: Rephrases coherently but does not change clarity.  
2: Produces clearer structure, decision scaffold, or path forward.

Examples of C2:
- Compresses multiple signals into a prioritized decision tree.
- Produces concrete next steps that reduce uncertainty.

---

## Scoring Interpretation
- avg(P,Q,C) < 1.0 → Not decision-grade  
- avg(P,Q,C) ≥ 1.0 → Decision-grade candidate  
- P2/Q2/C2 → Operator-grade artifact  

This gate is diagnostic, not moral.

---

## Known Limitations
SIP cannot directly measure:
- Hidden uncertainty
- Silent confusion
- Deliberate manipulation
- Political suppression of constraints

It evaluates the artifact, not the author.

---

## Intended Use
SIP supports:
- AI workflow evaluation
- Internal document review
- Governance and risk analysis
- Decision hygiene improvement
