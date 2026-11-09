# AI Response Evaluation — Quality Assurance Report

**Project:** Module 5 — Financial AI Response Evaluation  
**Date:** 9 November 2026  
**Type:** Guided training portfolio project (not client work or an accredited certification)  
**Domain:** Accounting and financial reporting  
**Evaluation method:** Manual comparison of two AI responses per exercise

## Executive summary

Five practice exercises evaluated AI-generated answers for factual and numerical accuracy, accounting reasoning, instruction following, completeness, and communication clarity. The evaluator achieved **43/50 (86%)** based on the exercise feedback. Strong performance was demonstrated in detecting incorrect treatment of loan principal, equipment purchases, and reporting structure. A key development area is rating calibration: supporting every numerical rating with a specific rationale.

## Evaluation rubric

- **Accuracy:** Are figures, accounting classifications, and explanations correct?
- **Reasoning:** Does the explanation support the answer without contradictory steps?
- **Instruction following:** Are all requested calculations, explanations, and formats provided?
- **Completeness:** Are material limitations and assumptions disclosed?
- **Clarity:** Is the answer understandable and suitable for the intended audience?

**Important:** An answer can contain a correct number but an incorrect explanation. Numerical accuracy and reasoning quality should be annotated separately. An uncertain or provisional answer should not be described as final net profit.

## Assessment scorecard

| Exercise | Topic | Score | Key lesson |
|---|---|---:|---|
| 1 | Profit calculation | 5/5 | Check basic numerical accuracy |
| 2 | Bank reconciliation | 6/10 | Separate correct figures from incorrect adjustment explanations |
| 3 | Loan principal vs interest | 9/10 | Distinguish liability reductions from expenses |
| 4 | Operating profit and capital expenditure | 9/10 | Check requested table format and asset classification |
| 5 | Full financial report evaluation | 14/15 | Evaluate accounting accuracy, coverage, and formatting |
| **Total** | | **43/50 (86%)** | |

## Case-level quality findings

### Exercise 1 — Basic profit calculation
**Expected:** KSh 500,000 revenue − KSh 320,000 expenses = **KSh 180,000 profit**.  
**Preferred response:** A.  
**Finding:** Response B incorrectly added expenses to revenue.  
**Evaluator result:** Correct selection and explanation.

### Exercise 2 — Bank reconciliation
**Inputs:** Bank statement KSh 250,000; unpresented cheque KSh 30,000; uncredited deposit KSh 10,000.  
**Correct reconciliation:** KSh 250,000 − KSh 30,000 + KSh 10,000 = **KSh 230,000**.  
**Finding:** Response A stated the correct final amount but reversed the adjustment descriptions; Response B stated KSh 270,000 and also reversed the treatment. Neither response was fully accurate. If forced to rank the two, A is preferable for its correct final figure; if asked whether either is fully correct, neither qualifies.  
**Evaluator result:** Correctly understood the meaning of outstanding items but needed to show the reconciliation and distinguish partial from complete accuracy.

### Exercise 3 — Loan principal and interest
**Inputs:** Revenue KSh 850,000; operating expenses KSh 420,000; salaries KSh 180,000; loan repayment KSh 100,000.  
**Preferred response:** B.  
**Finding:** Loan principal repayment reduces a liability and is not automatically a profit-and-loss expense. Interest may be expensed; the principal/interest breakdown was not supplied. Assuming salaries are separate from operating expenses, KSh 250,000 is a provisional profit figure before unlisted items and tax, not necessarily final net profit.  
**Evaluator result:** Correct identification of inappropriate loan repayment treatment.

### Exercise 4 — Operating profit and office computers
**Expected:** Gross profit = KSh 1,200,000 − KSh 450,000 = **KSh 750,000**. Provisional operating profit before depreciation = KSh 750,000 − KSh 200,000 − KSh 80,000 − KSh 25,000 = **KSh 445,000**.  
**Preferred response:** B.  
**Finding:** Response A immediately expensed KSh 150,000 of computers and failed to show gross profit or the requested table. Qualifying computers should generally be capitalized, with depreciation recognized according to the relevant policy and when available for use.  
**Evaluator result:** Correct accounting classification and instruction-following assessment.

### Exercise 5 — Annual financial reporting
**Expected gross profit:** KSh 5,000,000 − KSh 2,000,000 = **KSh 3,000,000**.  
**Expected operating profit before unspecified depreciation:** KSh 3,000,000 − KSh 900,000 − KSh 360,000 − KSh 120,000 − KSh 180,000 = **KSh 1,440,000**.  
**Expected provisional profit before tax:** KSh 1,440,000 − KSh 80,000 interest = **KSh 1,360,000**.  
**Preferred response:** B.  
**Finding:** Response A failed to provide the requested table, omitted the gross-profit subtotal, and incorrectly deducted KSh 400,000 loan principal and KSh 600,000 equipment purchase as expenses. Its stated KSh 4,640,000 total equals the sum of all listed cost/payment amounts, but not all those amounts belong in the income statement. Response B disclosed the missing depreciation information.  
**Evaluator result:** Correct preference, three valid errors identified, and a useful presentation improvement: use a middle column for detailed expenses and a right-hand column for totals.

## Error taxonomy

| Error category | Observed example | Suggested QA label |
|---|---|---|
| Numerical error | Incorrect profit or adjusted balance | `CALCULATION_ERROR` |
| Accounting classification | Loan principal treated as operating expense | `CLASSIFICATION_ERROR` |
| Reasoning inconsistency | Correct bank balance with reversed adjustment narrative | `REASONING_ERROR` |
| Instruction omission | No requested gross profit or table | `INSTRUCTION_FAILURE` |
| Missing qualification | Presenting provisional profit as final net profit | `UNSUPPORTED_CERTAINTY` |
| Presentation quality | Poor subtotal/expense-column organization | `FORMAT_IMPROVEMENT` |

## Recommendations for future annotation work

1. Independently recalculate every financial figure before assigning an accuracy rating.
2. Record separate scores for the final number, the explanation, and instruction following.
3. Quote or summarize the specific evidence for every rating below 5/5.
4. Flag assumptions about depreciation, tax, cost of sales, and interest when source information is missing.
5. For pairwise comparisons, distinguish “better of two” from “fully correct.”

## Portfolio statement

This is a self-directed, guided AI response evaluation practice project using fictional financial scenarios. It demonstrates manual quality assurance, error classification, accounting reasoning, and structured feedback. Scores are training assessment scores, not an external qualification or a measure of production annotation accuracy.
