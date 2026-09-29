# Review and release playbook

## Build a useful sample

Include common questions and deliberate difficult cases. Balance accepted answers with missing, stale, conflicting, acronym, and scope-limited evidence. Keep a fixed holdout set for regression checks. All example records in this repository are synthetic.

## Evaluate

1. Present the reviewer with the question, answer, document title/version, and exact cited passage.
2. Score each rubric dimension independently. Quote the words that justify a failure.
3. Mark critical failures before totaling the score.
4. Route the case according to the rubric. Record disagreement and adjudication.

## Diagnose, then change one thing

| Failure pattern | Likely area to inspect | Product response |
| --- | --- | --- |
| Wrong or absent passage | Retrieval or citation mapping | Improve passage selection; add source-link checks |
| `MFA` missed, full term present | Abbreviation matching | Add mapping and a regression case |
| Admin-only control generalized to all users | Answer generation or scope UI | Require population qualifier; add blocking evaluation |
| Old and new policies disagree | Document freshness/versioning | Show conflict and route to manual review |

## Release gate example

Do not expand an AI drafting feature while known critical failures remain unresolved in the reviewed release set. Track unsupported-answer and citation accuracy rates separately from speed or coverage. Re-evaluate after every change to retrieval, document parsing, prompts, or UI presentation.

This gate is an illustrative product proposal, not a claim about an employer's policy.
