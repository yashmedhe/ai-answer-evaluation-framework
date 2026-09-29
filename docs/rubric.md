# Rubric for document-grounded answers

Use this rubric on one question, generated answer, and displayed citation at a time. A reviewer must inspect the cited passage, not just the model's explanation.

| Dimension | 0 | 1 | 2 |
| --- | --- | --- | --- |
| Responsiveness | Does not answer the question | Partially answers or is vague | Directly addresses the asked control |
| Evidence support | No relevant citation or contradicted by source | Citation is related but incomplete | Every material claim is supported by the shown passage |
| Scope and conditions | Misstates population, system, timeframe, or exceptions | Mostly right but omits a material qualifier | Preserves all material qualifiers |
| Uncertainty handling | Invents certainty or hides a conflict | Signals some uncertainty, but action is unclear | Abstains or clearly routes ambiguous cases to review |

**Total:** 0–8. The total helps compare ordinary cases; it does not override a critical failure.

## Decision rules

- **Accept for supplier review:** total 7–8, evidence support = 2, scope = 2, no critical failure. A person must still approve the final submission.
- **Manual review:** total 4–6, or a case with potentially conflicting or outdated sources. Show why review is required.
- **Reject suggestion:** total 0–3, or a critical failure. Leave the answer for manual completion.

## Critical failures

Any one of these overrides the numeric total: an invented citation, a materially unsupported compliance claim, a population/timeframe overclaim, or a contradiction with the cited document. Record the specific failure and affected text.

## Reviewer record

For each case capture `case ID`, question, answer, document/version, cited passage, four dimension scores, critical failure (yes/no), decision, and one-sentence rationale. Have a second reviewer adjudicate disputed cases before using results for a launch decision.
