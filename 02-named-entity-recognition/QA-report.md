# Named Entity Recognition (NER) — Quality Assurance Report

**Reviewer:** Lydia Wakarura Ngothi
**Tool:** Label Studio
**Project:** NER Practice Test
**Review Date:** 4 November 2026

## Project Overview
This project involved manually reviewing Named Entity Recognition annotations to assess label accuracy, entity boundaries, missing entities, and annotation consistency.

## Annotation Categories
- PER — Person
- ORG — Organization
- LOC — Location
- Date — Date expression
- Money — Monetary amount

## QA Training Results
| Exercise | Score | Accuracy |
|---|---|---|
| Basic QA | 5/5 | 100% |
| Intermediate QA | 6/6 | 100% |
| Advanced QA | 4/6 | 66.7% |
| **Overall** | **15/17** | **88.2%** |

## Dataset Audit Results
Ten annotated tasks were reviewed manually using screenshots from Label Studio.

| Metric | Result |
|---|---|
| Tasks reviewed | 10 |
| Entities reviewed | 37 |
| Correct entities | 37 |
| Classification errors | 0 |
| Boundary errors | 0 |
| Missing entities | 0 |
| Observed sample accuracy | 100% |

## QA Methodology
1. Reviewed the highlighted entities in each task.
2. Checked labels against the project annotation guidelines.
3. Verified entity span boundaries.
4. Checked for missing or unnecessary annotations.
5. Documented the review findings.

## Findings
All 37 visible entity annotations across the 10 reviewed tasks were correctly classified and had appropriate boundaries. No errors were identified in the reviewed sample.

## Limitations
The 100% observed accuracy applies only to the 10 reviewed tasks and does not establish accuracy across the complete dataset. Task IDs 212–216 were confirmed; subsequent task IDs should be verified.

## Skills Demonstrated
- Named Entity Recognition
- Annotation Quality Assurance
- Entity Classification
- Boundary Validation
- Manual Error Review
- Label Studio
- QA Documentation

## Next Steps
- Review more complex annotation examples.
- Expand the audit sample.
- Practise text classification and topic labelling.
- Continue developing the GitHub annotation portfolio.
