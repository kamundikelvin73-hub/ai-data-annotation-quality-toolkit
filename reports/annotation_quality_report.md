# Annotation Quality Report

## Project

AI Data Annotation Quality Toolkit

## Batch Summary

| Metric | Result |
|---|---:|
| Total Items Reviewed | 100 |
| Accepted Items | 92 |
| Reworked Items | 8 |
| Estimated Accuracy | 92% |
| Critical Errors | 1 |
| Major Errors | 5 |
| Minor Errors | 2 |

## Error Breakdown

| Error Type | Count |
|---|---:|
| Wrong classification label | 4 |
| Incorrect sentiment label | 2 |
| Entity span error | 1 |
| Missing reviewer note | 1 |

## Key Findings

1. Most errors came from ambiguous multi-intent text.
2. Sentiment errors occurred when annotators inferred emotion instead of using expressed language.
3. Entity errors were mostly caused by incomplete spans.
4. Reviewer feedback improved consistency across later batches.

## Recommendations

- Add more edge-case examples to the guideline.
- Require reviewer notes for ambiguous samples.
- Run calibration before large annotation batches.
- Track label-level error rates weekly.

## Portfolio Relevance

This report demonstrates annotation QA, dataset review, error analysis, and reviewer feedback skills relevant to AI training and data quality roles.
