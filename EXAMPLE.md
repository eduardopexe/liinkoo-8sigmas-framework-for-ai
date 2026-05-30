# EXAMPLE.md

## Goal

Create a simple REST API endpoint.

This example demonstrates a complete execution cycle using the Liinkoo 8 Sigmas Framework.

---

# Initial Context

Project:

```text
Customer Management API
```

Objective:

```text
Expose GET /customers endpoint
```

Constraints:

```text
Must be documented
Must include validation
Must produce evidence
```

Success Criteria:

```text
Endpoint implemented
Validation completed
Documentation updated
Evidence captured
Memory updated
```

---

# Cycle 1 — Planning

## Inputs

* Business requirement
* Existing architecture

## Activities

* Review requirements
* Define implementation approach
* Create architecture decision record (ADR)

## Outputs

* Approved approach
* ADR created

## Evidence

```text
docs/architecture/adr/0001-customers-endpoint.md
```

---

# Cycle 2 — Execution

## Inputs

* Approved ADR

## Activities

* Implement endpoint
* Implement validation
* Add logging

## Outputs

* Working endpoint

## Evidence

```text
Source code committed
Endpoint returns expected response
```

---

# Cycle 3 — Validation

## Inputs

* Working implementation

## Activities

* Execute smoke tests
* Verify expected behavior

## Outputs

* Validation report

## Evidence

```text
docs/qa/smoke-test-results.md
```

---

# Cycle 4 — Documentation

## Inputs

* Validated implementation

## Activities

* Update operational documentation
* Update runbooks

## Outputs

* Documentation updated

## Evidence

```text
docs/operations/runbook.md
```

---

# Cycle 5 — Memory Update

## Inputs

* Completed implementation

## Activities

* Capture lessons learned
* Record proven patterns
* Update project memory

## Outputs

* Organizational knowledge retained

## Evidence

```text
docs/memory/project-memory.md
```

---

# Governance Check

Questions:

* Was evidence produced?
* Were success criteria met?
* Were assumptions validated?
* Were lessons captured?
* Can the work be replayed?

Decision:

```text
Approved
```

or

```text
Return to planning
```

---

# Result

The framework produced:

* implementation
* validation
* documentation
* evidence
* reusable knowledge

instead of code only.

This is the core objective of the Liinkoo 8 Sigmas Framework.
