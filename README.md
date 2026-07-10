---
type: Entry Point
title: doctrine
description: Runtime-neutral principles for purpose, ethics, ontology, epistemology, governance, incentives, method, and adaptive change.
tags: [doctrine, purpose, epistemology, ontology, ethics, governance, incentives, okf]
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

`teleology` is retained only for compatibility. Purpose is one part of doctrine, not the whole package.

Optional addon commonly paired with the stack:

```bash
npx architectonic add living-knowledge
```

That addon is separate from doctrine. It defines corpus-maintenance procedures rather than governing principles.

## Role

Doctrine answers:

```text
What is the system for?
What boundaries should govern action?
What counts as evidence or knowledge?
What entities and relationships matter?
Who may decide, approve, delegate, or stop?
How are incentives, costs, risks, and scarce resources handled?
How should work proceed and be verified?
How may the system adapt without silently changing its purpose or authority model?
```

Doctrine should make assumptions and tradeoffs inspectable. It should not present provisional principles as universal truths.

## Boundary

`doctrine` may contain general, runtime-neutral principles, schemas, examples, and source-backed references.

It must not contain private identity, private project facts, runtime secrets, project handoffs, skill corpora, or knowledge corpora.

## Core files

```text
doctrine.md          -- root doctrine contract
constitution.md      -- relationship to the constitution scaffold
oikonomia.md         -- incentives, resources, risks, costs, and benefits
aletheia-sophia.md   -- knowledge and system-maintenance distinctions
physis.md            -- adaptive change and continuity
```

The Greek-derived filenames are retained as internal vocabulary. Plain-language explanations should remain primary, and no reader should need the terminology to use the package.

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
meta              = defines upkeep, audit, and revision policy
living-knowledge  = optional addon for governed corpus maintenance
```
