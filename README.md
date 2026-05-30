<p align="center">
  <img src="assets/logo-icon.png" width="180">
</p>

# Liinkoo 8 Sigmas Framework for AI

Reusable operational framework for AI-assisted execution, governance, contextual intelligence and continuous delivery.

Designed to transform AI from a conversational assistant into a repeatable, evidence-driven operational system.

**Website:** https://liinkoo.com

**Documentation:** EXAMPLE.md

---

## Purpose

Liinkoo 8 Sigmas is a reusable operational framework designed to transform AI from a conversational assistant into an operational execution system.

The framework provides a structured approach for:

* AI-assisted software development
* Data engineering initiatives
* Infrastructure and automation projects
* Operational intelligence platforms
* Long-running AI execution workflows
* Continuous improvement programs

This version was redesigned to:

* reduce agent explosion
* reduce documentation sprawl
* separate framework from project-specific context
* support any software, data or AI initiative
* preserve deterministic and evidence-driven execution

---

## Core Philosophy

The framework is built on five fundamental principles:

### Memory over Prompts

Persistent context is more valuable than increasingly complex prompts.

### Evidence over Assumptions

Decisions should be supported by observable facts.

### Systems over Improvisation

Repeatable processes outperform ad-hoc execution.

### Delivery over Demos

Working outcomes matter more than presentations.

### Stop on Uncertainty

When evidence is insufficient, stop and validate before continuing.

---

## Who Is This For?

This framework is designed for:

* Software engineers
* AI-assisted development teams
* Data engineering teams
* Platform engineering teams
* Infrastructure and automation specialists
* Product development initiatives
* Operational intelligence platforms

The framework is model-agnostic and can be used with:

* ChatGPT
* Claude
* GitHub Copilot
* Gemini
* DeepSeek
* Cursor
* Windsurf
* Future AI systems

---

## Architecture Model

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

Each layer has a clear responsibility.

```text
Framework
    Operational methodology

LIA Core
    Runtime state and memory

Agents
    Execution roles

Templates
    Project-specific overlays

Project Docs
    Operational artifacts
```

---

## Directory Structure

```text
framework/
    Immutable operational methodology

lia-core/
    Operational memory and runtime state

agents/
    Minimal execution agents

templates/
    Project and domain templates

docs/
    Project operational documentation
```

---

## Minimal Agent Philosophy

Previous versions accumulated many specialized agents:

```text
planner
coder
reviewer
prompt writer
documentation writer
qa writer
smoke-test writer
handoff writer
...
```

Over time this created:

* governance complexity
* context duplication
* operational overhead

The framework now adopts a minimal agent model:

```text
agents/
├── orchestrator.md
├── executor.md
└── reviewer.md
```

### Orchestrator

Responsible for:

* planning
* sequencing
* execution coordination

### Executor

Responsible for:

* implementation
* documentation
* operational work

### Reviewer

Responsible for:

* validation
* evidence review
* quality gates

---

## Quick Start

### Step 1 — Copy the Framework

Copy:

```text
framework/
lia-core/
agents/
```

into your repository.

---

### Step 2 — Select a Template

Choose a template:

```text
templates/generic
templates/liinkoo_ic
templates/netblue
```

Copy the selected template into your project documentation structure.

---

### Step 3 — Initialize Project Memory

Update:

```text
docs/memory/project-memory.md
```

Document:

* active initiatives
* architecture decisions
* operational rules
* proven patterns
* lessons learned

---

### Step 4 — Build the Backlog

Update:

```text
docs/backlog/backlog.md
```

Include:

* epics
* tasks
* blockers
* dependencies
* required evidence

---

### Step 5 — Execute the First Cycle

Recommended cycle:

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

## Example Execution Flow

A simplified example:

```text
Goal:
Create a REST API
```

### Cycle 1

```text
Define architecture
Create ADR
Document assumptions
```

Output:

```text
ADR approved
Architecture documented
```

### Cycle 2

```text
Implement endpoint
Create smoke test
Execute validation
```

Output:

```text
Working endpoint
Evidence captured
```

### Cycle 3

```text
Review execution
Update memory
Capture lessons learned
```

Output:

```text
Updated documentation
Reusable knowledge
```

---

## Learn by Example

For a complete end-to-end execution example, see:

```text
EXAMPLE.md
```

The example demonstrates how planning, execution, validation, documentation and memory updates work together inside a complete execution cycle.

---

## Runtime Modes

### Supervised Mode

Human-guided execution.

Recommended for:

* architecture changes
* migrations
* strategic decisions
* high-risk operations

---

### Autonomous Batch Mode

Bounded high-throughput execution.

Recommended for:

* repetitive work
* backlog execution
* documentation generation
* operational maintenance

---

### Blue Camel Runtime

Distributed resumable execution.

Recommended for:

* workers
* collectors
* large datasets
* asynchronous processing
* long-running operations

---

## Framework vs Templates

### Framework

Reusable operational methodology.

The framework should never include:

* telecom assumptions
* SQL assumptions
* parquet assumptions
* CNPJ assumptions
* SNMP assumptions
* project-specific rules

---

### Templates

Project-specific overlays.

Examples:

```text
Liinkoo IC
NetBlue
Future products
Customer projects
```

Templates adapt the framework to a domain without changing the framework itself.

---

## Design Goals

The framework aims to provide:

* repeatability
* governance
* traceability
* contextual intelligence
* operational scalability
* continuous improvement

---

## Goal

Transform AI from:

```text
autocomplete
```

into:

```text
execution assistant
```

and ultimately into:

```text
operational system
```

---

## Typical Use Cases

The framework is primarily designed for:

* AI-assisted software development
* Data engineering pipelines
* Infrastructure automation
* Network automation
* Operational intelligence platforms
* Documentation-driven projects
* Product development initiatives
* Long-running AI execution workflows

The framework is intentionally domain-agnostic and can be adapted to different industries, technologies and execution models.

---

## License

Licensed under the Apache License 2.0.

See:

```text
LICENSE
```

for details.

---

## Project Status

Current Status:

```text
v1.1.0
Initial Open Source Release
```

This repository contains the public version of the Liinkoo 8 Sigmas Framework.

The framework is under active validation through real-world projects involving:

* AI-assisted execution
* network automation
* operational intelligence
* large-scale data processing
* observability platforms

Contributions, feedback and improvements are welcome.

---

## Contact

**Website**

https://liinkoo.com

**Email**

[framework@liinkoo.com](mailto:framework@liinkoo.com)

**GitHub**

https://github.com/eduardopexe/liinkoo-8sigmas-framework-for-ai

---

Maintained by the Liinkoo community and contributors.
