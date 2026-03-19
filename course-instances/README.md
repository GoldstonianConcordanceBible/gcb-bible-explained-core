# Course Instances Layer

This layer tracks real student participation, progress, and completion across all active and archived course offerings in the GCB Old Testament book-courses system.

## Purpose
- Provide accreditation evidence
- Track enrollment and participation
- Validate seat time and course progress
- Maintain completion records
- Support audit readiness

## Directory Structure

- `schema/` → JSON validation structures for enrollment, progress, and completion records
- `active/` → live course instances by course code
- `archived/` → completed or past-term course instances

## Core Record Types
- Student profile
- Enrollment status
- Playlist/course progress
- Time logs
- Quiz results
- Assignment status
- Completion record

## Audit Relevance
This layer provides the dynamic proof-of-learning record required for accreditation, quality review, and registrar-level reporting.