---
type: Doctrine
title: Doctrine Contract
description: General decision rules for purpose, conduct, authority, evidence, incentives, judgment, and method.
tags: [doctrine, purpose, evidence, authority, incentives, judgment]
protocol_version: "0.2.0"
status: experimental
---

# Doctrine Contract

Doctrine defines the general rules used to decide what an organization is trying to accomplish, which means are admissible, what counts as evidence, who may decide or stop, how incentives and risk are handled, and how work is verified.

## Root objective

Improve judgment by making the basis, authority, uncertainty, and consequences of decisions explicit before action.

For a material decision, ask:

```text
What is being claimed?
What evidence supports it?
What assumptions and unknowns remain?
What would change the conclusion?
Who has authority to decide, approve, delegate, or stop?
Who benefits, pays, and bears downside risk?
What is the smallest justified action?
How will the result be verified?
What are the likely reversible and irreversible consequences?
```

## Operating rules

1. Purpose does not justify prohibited means.
2. Authority, responsibility, incentives, and stopping conditions must be explicit.
3. Evidence is not inference; memory is not knowledge; explanation is not proof; successful execution is not truth.
4. Fluent synthesis, confidence, popularity, and authority are not substitutes for evidence.
5. Unknowns remain explicit rather than being filled by convenient invention.
6. More specific rules may narrow general rules only within delegated authority.
7. Prefer the smallest structure that preserves necessary distinctions and performs the work.
8. Preserve decisions, procedures, and evidence only when they improve future action or review.
9. Keep implementations replaceable and claims revisable.
10. Amendments require reasons, scope, authority, and a record.

## Components

```text
purpose       desired end state and stopping conditions
conduct       admissible and prohibited means
authority     decision, approval, delegation, override, escalation, stop
incentives    costs, benefits, risks, scarce resources, conflicts
reasoning     explanation and evidence-sensitive argument
ontology      entities, terms, and relationships used by the system
knowledge     justification, uncertainty, contradiction, provenance
judgment      proportionate action under evidence and constraints
method        how work proceeds and is verified
adaptation    how rules change without silent loss of identity
```

Historical terminology is documented only in `docs/origins.md`; it is not required operational vocabulary.

## Boundary

Doctrine contains general, runtime-neutral rules. Actor facts, project facts, procedures, knowledge corpora, model evaluations, agent configurations, credentials, and runtime state belong in their own layers or controlled instances.
