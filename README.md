---
type: Entry Point
title: doctrine
description: Runtime-neutral doctrine package for purpose, ethics, ontology, epistemology, governance, incentives, method, and adaptive change.
tags: [doctrine, teleology, epistemology, ontology, ethics, governance, oikonomia, physis, okf]
okf_version: "0.1"
status: draft
---

# doctrine

`doctrine` is the governing-principles package for Architectonic systems.

Install it with:

```bash
npx architectonic add doctrine
```

Legacy alias:

```bash
npx architectonic add teleology
```

`teleology` is retained only as a compatibility name. Telos is one doctrine component, not the whole package.

Optional addon commonly paired with the stack:

```bash
npx architectonic add living-knowledge
```

That addon is separate from doctrine. It governs corpus maintenance campaigns, not first-principles governance.

## Role

Doctrine answers:

```text
What is the system for?
What must not be violated?
What counts as knowledge?
What exists in the system?
Who may decide?
How are incentives, costs, risks, and scarce resources handled?
How should work proceed?
How does the system adapt without losing identity?
```

## Boundary

`doctrine` may contain general, runtime-neutral governing principles, schemas, examples, and source-backed references.

It must not contain private identity, private project facts, runtime secrets, project handoffs, skill corpora, or knowledge corpora.

## Core files

```text
doctrine.md          -- root doctrine contract
constitution.md      -- relationship to the constitution scaffold
oikonomia.md         -- incentives, resources, risks, costs, benefits
aletheia-sophia.md   -- knowledge corpus and recursive improvement
physis.md            -- adaptive growth and identity-preserving change
```

## Relationship to constitution

`constitution` is the root scaffold. `doctrine` is the principles layer inside it.

## Relationship to the rest of the stack

```text
constitution      = composes the whole stack
doctrine          = defines purpose, boundaries, and governing principles
identity          = defines actors, authority, and privacy
project           = defines operating-unit context
skills            = defines reusable procedures
knowledge         = defines the disclosed corpus of claims and evidence
meta              = defines upkeep and recursive improvement
living-knowledge  = optional addon for governed corpus maintenance campaigns
```

## Paper alignment

In the Constitutional Architectonics paper, this package corresponds to the governing layer: Archē, Telos, Ethos, Nomos, Oikonomia, Logos, and the doctrine-side definitions of Ontos, Aletheia, Sophia, and Physis.
