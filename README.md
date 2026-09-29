# Evidence-backed AI answer evaluation framework

**Portfolio type:** Original illustrative evaluation framework, informed by my experience with AI-assisted risk workflows and model evaluation. All sample questions, policies, outputs, and scores are synthetic. This is a review method, not a model or production benchmark.

## The evaluation question

When an AI system drafts an answer from uploaded documents, a fluent answer can still be wrong. Is the answer responsive, supported by the cited passage, correctly scoped, and safe to show for human review?

## Method

1. Create a test set with positive, missing-evidence, conflicting-evidence, stale-document, and scope-mismatch cases.
2. Score the answer against the [rubric](docs/rubric.md). Judge the answer and citation together.
3. Apply [decision rules](docs/review-playbook.md). Critical unsupported claims fail regardless of the total score.
4. Group failures by cause and make a targeted product change; rerun the same cases to check regressions.

## Example result

In [four synthetic cases](examples/scored-cases.md), a well-supported answer passes, a scope overclaim fails, and appropriate abstention and conflicting-document responses route the underlying items to manual review. These are worked examples, not empirical system performance.

## Why this matters for product management

Evaluation should inform product decisions: what the UI displays, when it asks for human review, which evidence to surface, and which failures block launch. A high aggregate score is not enough if one severe claim could mislead a risk reviewer.

## Files

- [Rubric](docs/rubric.md)
- [Review playbook](docs/review-playbook.md)
- [Scored synthetic cases](examples/scored-cases.md)
- [Iteration log](docs/iteration-log.md)
