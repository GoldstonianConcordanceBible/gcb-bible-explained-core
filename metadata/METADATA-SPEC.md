# Metadata Specification (ENFORCEMENT)

## Purpose
Defines machine-readable requirements for all metadata files in this repository.

---

## Core Files

- ot-course-catalog.json
- ot-textbook-catalog.json
- ot-playlist-catalog.json
- ot-course-tags.json
- doctrine-keywords.json

---

## Rules

1. JSON must be valid and schema-consistent
2. Course codes must match:
   → master-index/course-code-registry.md
3. No orphan entries
4. Every course must include:
   - course_code
   - title
   - canonical_group
   - playlist_reference
   - textbook_reference

---

## Enforcement

- Metadata is the PRIMARY ingestion layer for AI systems
- Broken metadata = system failure

---

## Update Policy

- Update metadata whenever:
  - new course is added
  - playlist is created
  - textbook is published