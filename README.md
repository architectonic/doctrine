---
type: Entry Point
title: doctrine
description: Runtime-neutral principles for purpose, ethics, ontology, epistemology, governance, incentives, method, and adaptive change.
tags: [doctrine, purpose, epistemology, ontology, ethics, governance, incentives, okf]
okf_version: "0.2"
status: draft
---

# doctrine

```bash
npx architectonic add doctrine
```

`doctrine` defines the governing principles of an Architectonic system: purpose, boundaries, evidence, authority, incentives, method, and adaptation.

Teleology is the study of purpose and ends. Within Architectonic, purpose is one part of doctrine alongside ontology, epistemology, ethics, governance, incentives, method, and adaptation.

## In the ensemble

```text
constitution      composition contract for the ensemble
doctrine          purpose, principles, ontology, epistemology, ethics, governance, incentives
identity          actors, roles, authority, delegation, incentives, privacy
project           operating-unit context, sources, decisions, risks, continuity
skills            reusable procedures, verification, failure handling
knowledge         claims, sources, evidence, uncertainty, known unknowns
models            model metadata, evaluations, capability requirements, routing policy
agents            software actors composed from identity, skills, models, knowledge, permissions
living-knowledge  optional: governed maintenance of frequently changing corpora
meta              audit, upkeep, drift review, revision policy
```

Doctrine answers what the system is for, what boundaries govern action, what counts as evidence, who may decide or stop, how incentives and risks are handled, and how the system may adapt without silently changing its purpose or authority model. Its principles remain open to revision when evidence, conditions, or legitimate authority change.

## Commands

```bash
npx architectonic add doctrine
npx architectonic add doctrine --source npm
npx architectonic init
npx architectonic list
npx architectonic doctor
```

CLI: https://github.com/architectonic/architectonic

## Boundary

`doctrine` may contain general, runtime-neutral principles, schemas, examples, and source-backed references.

Private identity, project facts, runtime secrets, skill corpora, model evaluations, agent instances, and knowledge corpora belong in their respective packages or instantiated workspaces.

## Core files

```text
doctrine.md          root principles contract
constitution.md      relationship to the composition contract
oikonomia.md         incentives, resources, risks, costs, and benefits
aletheia-sophia.md   knowledge and system-maintenance distinctions
physis.md            adaptive change and continuity
```

Greek-derived terms may serve as compact internal vocabulary; plain-language definitions remain primary.
