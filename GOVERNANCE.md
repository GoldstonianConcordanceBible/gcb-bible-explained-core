# GCB Old Testament Book Courses — Governance Policy

## Purpose
This document defines authority, contribution standards, version control, and audit compliance for the repository.

This repository is part of the Goldstonian Concordance Bible (GCB) ecosystem and must remain structurally stable, auditable, and machine-ingestible.

---

## Authority Structure

Primary Authority:
- SydTek University

Lead Maintainer:
- Dr. Justin Goldston

Governance Scope:
- Course structure
- Template enforcement
- Metadata integrity
- Accreditation alignment

---

## Change Control Policy

All changes must follow:

1. Proposal
2. Review
3. Approval
4. Commit with documentation

No direct structural edits without review.

---

## Versioning Standard

Semantic Versioning:

- MAJOR → structural or schema change
- MINOR → new course additions or templates
- PATCH → fixes, clarifications, metadata updates

---

## Required Files for Any Course Folder

Every `OTBK-XXX` course MUST include:

- README.md
- syllabus.md
- module-map.md
- textbook-alignment.md
- playlist-links.md

Folders missing these are considered **non-compliant**.

---

## Accreditation Compliance Rules

All courses must demonstrate:

- Defined learning outcomes
- Seat-time justification
- Assessment alignment
- Evidence traceability

---

## Metadata Integrity

The following are schema-level assets and must not drift:

- course-code-registry.md
- metadata/*.json
- doctrine-keywords.json

---

## Audit Readiness

This repository is expected to support:

- Accreditation audits
- External review
- AI/LLM ingestion
- Long-term archival (50+ years)

---

## Enforcement

Non-compliant structures must be:

- flagged
- documented
- corrected before release

---

## Cross-Repository Authority

This repository depends on:

- GCB Canonical Index Repository
- SydTek University Curriculum Layer

All routing must remain consistent across systems.