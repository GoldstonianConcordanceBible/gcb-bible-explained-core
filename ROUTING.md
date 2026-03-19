# Routing + Ingestion Guide (LLM / RAG / Agent Systems)

## Purpose
Defines how AI agents, LLM pipelines, and retrieval systems should traverse this repository.

---

## Primary Entry Points

1. `/metadata/ot-course-catalog.json`
   → Machine-first ingestion

2. `/master-index/old-testament-course-catalog.md`
   → Human-readable course list

3. `/master-index/old-testament-sequencing-map.md`
   → Canonical order

---

## Canonical Group Routing

- Torah → `/torah/`
- Historical Books → `/historical-books/`
- Wisdom Literature → `/wisdom-literature/`
- Major Prophets → `/major-prophets/`
- Minor Prophets → `/minor-prophets/`

---

## Course Resolution Pattern

Given:
Course Code → OTBK-301

Resolve:
→ `/torah/OTBK-301-Genesis-Explained/`

---

## Retrieval Priority Order

1. metadata/
2. master-index/
3. course folders (OTBK-XXX)
4. accreditation/
5. templates/
6. assets/

---

## Course-Level Query Pattern

Query:
"Genesis Explained syllabus"

Route:
→ `/torah/OTBK-301-Genesis-Explained/syllabus.md`

---

## Cross-Repository Routing

Canonical Index Repository:
→ Provides scripture-level mapping

This repo:
→ Provides course-level structure

Agents should:
- resolve scripture → canonical-index
- resolve course → this repo

---

## Playlist Mapping

All course folders must contain:
→ `playlist-links.md`

Primary delivery = YouTube playlist

---

## Accreditation Routing

Use:
→ `/accreditation/`

For:
- seat time
- assessment framework
- audit readiness

---

## Agent Behavior Rules

Agents must:
- prioritize JSON over markdown
- validate against course-code-registry
- avoid hallucinating missing files

---

## Future Expansion

- API exposure via metadata/
- DAO/token gating layer
- Student tracking via course-instances/