# Liinkoo 8 Sigmas Framework for AI v1

## Purpose

Liinkoo 8 Sigmas is a reusable operational framework for AI-assisted execution, governance, contextual intelligence and continuous delivery.

This version was redesigned to:

- reduce agent explosion
- reduce documentation sprawl
- separate framework from project-specific context
- support any software/data/AI project
- preserve deterministic and evidence-driven execution

---

# Core Philosophy

- Memory over prompts
- Evidence over assumptions
- Systems over improvisation
- Delivery over demos
- Stop on uncertainty

---

# Architecture Model

```text
Framework
↓
LIA Core
↓
Agents
↓
Project Templates
↓
Project Docs
```

---

# Directory Structure

```text
framework/     -> immutable operational methodology
lia-core/      -> operational runtime memory and state
agents/        -> minimal execution agents
templates/     -> project/domain templates
docs/           -> project operational documentation
```

---

# Minimal Agent Philosophy

This version intentionally reduces the amount of permanent agents.

Previous versions contained:

- planners
- coders
- prompt writers
- QA writers
- smoke-test writers
- backlog handoff agents
- autonomous/supervised variants

Most behaviors are now consolidated.

Current model:

```text
agents/
├── orchestrator.md
├── executor.md
└── reviewer.md
```

---

# How To Use

## 1. Copy framework

Copy:

- framework/
- lia-core/
- agents/

into your repository.

---

## 2. Select a template

Choose one:

```text
templates/generic
templates/liinkoo_ic
templates/netblue
```

Copy template docs into your repository docs folder.

---

## 3. Initialize memory

Update:

```text
docs/memory/project-memory.md
```

Add:

- active initiatives
- architecture decisions
- operational rules
- lessons learned

---

## 4. Start backlog

Update:

```text
docs/backlog/backlog.md
```

Add:

- epics
- next safe steps
- blockers
- evidence required

---

## 5. Start execution

Recommended loop:

```text
Context
↓
Plan
↓
Execute
↓
Review
↓
Evidence
↓
Documentation
↓
Memory
↓
Repeat
```

---

# Runtime Modes

## Supervised

Human-guided.

Best for:

- architecture
- migrations
- strategic changes

---

## Autonomous Batch

High-throughput bounded execution.

Best for:

- repetitive work
- documentation
- backlog execution

---

## Blue Camel Runtime

Distributed resumable execution.

Best for:

- workers
- collectors
- large datasets
- async processing

---

# Framework vs Templates

## Framework

Generic reusable operational model.

Never include:

- telecom assumptions
- SQL assumptions
- parquet assumptions
- CNPJ assumptions
- SNMP assumptions

---

## Templates

Project-specific operational overlays.

Examples:

- Liinkoo IC
- NetBlue
- Future products

---

# Goal

Transform AI from:

```text
autocomplete
```

into:

```text
operational system
```
