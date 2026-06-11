# Annotation Quality Checklist

Use this checklist before accepting a labeled dataset.

## Dataset-Level Checks

- All required fields are present
- No duplicate IDs
- No missing labels
- Label values match the approved taxonomy
- Dataset version is documented
- Edge cases are flagged
- Reviewer notes are included where needed

## Item-Level Checks

- Text was read fully before labeling
- Label matches the primary intent
- Sentiment is based on expressed language
- Entities use the correct span
- Ambiguous examples are escalated
- No unsupported assumptions are added

## Reviewer Acceptance Criteria

A batch can be accepted when:

- Accuracy is at least 95% for straightforward labels
- Ambiguous cases are documented
- Critical errors are corrected
- Reviewer feedback is clear and actionable
- Rework items are resolved

## Critical Errors

- Wrong label that changes meaning
- Missing high-priority entity
- Labeling based on personal assumption
- Using labels outside the taxonomy
- Failing to follow project-specific instructions
