---
type: Entry Point
title: doctrine
description: Runtime-neutral principles for purpose, ethics, ontology, epistemology, governance, incentives, method, and adaptive change.
tags: [doctrine, purpose, epistemology, ontology, ethics, governance, incentives, okf]
okf_version: "0.2"
status: draft
---

# doctrine

`doctrine` defines the governing principles of an Architectonic system.

Install it with:

```bash
npx architectonic add doctrine
```

Teleology is the study of purpose and ends. Within Architectonic, purpose is one part of doctrine alongside ontology, epistemology, ethics, governance, incentives, method, and adaptation.

## Role

Doctrine answers:

```text
What is the system for?
What boundaries govern action?
What counts as evidence or knowledge?
What entities and relationships matter?
Who may decide, approve, delegate, or stop?
How are incentives, costs, risks, and scarce resources handled?
How should work proceed and be verified?
How may the system adapt without silently changing its purpose or authority model?
```

Doctrine makes assumptions and tradeoffs inspectable. Its principles remain open to revision when evidence, conditions, or legitimate authority change.

## Boundary

`doctrine` may contain general, runtime-neutral principles, schemas, examples, and source-backed references.

Private identity, project facts, runtime secrets, handoffs, skill corpora, model evaluations, agent instances, and knowledge corpora belong in their respective packages or instantiated workspaces.

## Core files

```text
doctrine.md          -- root principles contract
constitution.md      -- relationship to the composition contract
oikonomia.md         -- incentives, resources, risks, costs, and benefits
aletheia-sophia.md   -- knowledge and system-maintenance distinctions
physis.md            -- adaptive change and continuity
```

Greek-derived terms may serve as compact internal vocabulary, but plain-language definitions remain primary.

## Relationship to the ensemble

```text
constitution      = composes the ensemble
doctrine          = defines purpose, boundaries, and governing principles
identity          = defines actors, authority, delegation, incentives, and privacy
project           = defines operating-unit context
skills            = defines reusable procedures and verification
knowledge         = defines retained claims, sources, evidence, uncertainty, and gaps
models            = defines model capabilities, constraints, evaluations, and routing evidence
agents            = composes actors, procedures, models, knowledge, and permissions
living-knowledge  = defines governed maintenance of changing corpora
meta              = defines audit, upkeep, drift review, and revision policy
```