---
type: Entry Point
title: doctrine
description: Runtime-neutral doctrine package for purpose, ethics, ontology, epistemology, governance, incentives, and method.
tags: [doctrine, teleology, epistemology, ontology, ethics, governance, oikonomia, okf]
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
```

## Boundary

`doctrine` may contain general, runtime-neutral governing principles, schemas, examples, and source-backed references.

It must not contain private identity, private project facts, runtime secrets, project handoffs, or skill corpora.

## Core files

```text
doctrine.md       -- root doctrine contract
constitution.md   -- relationship to the constitution scaffold
oikonomia.md      -- incentives, resources, risks, costs, benefits
aletheia-sophia.md -- knowledge corpus and recursive improvement
```

## Relationship to constitution

`constitution` is the root scaffold. `doctrine` is the principles layer inside it.
