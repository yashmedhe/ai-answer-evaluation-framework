# Four scored synthetic cases

These invented examples demonstrate the [rubric](../docs/rubric.md). Scores are ordered: responsiveness / evidence / scope / uncertainty.

## E01 — Supported answer

**Question:** Is MFA required for all employees accessing production systems?

**Source:** Current example policy: `All employees must use multi-factor authentication for production-system access.`

**Draft:** `Yes. All employees use MFA for production-system access.`

**Score:** 2 / 2 / 2 / 2 = **8/8**. **Decision:** Accept for supplier review. The claim matches the population and system in the source; a person still confirms the submission.

## E02 — Scope overclaim

**Question:** Is MFA required for all employees accessing production systems?

**Source:** Current example policy: `Administrators must use multi-factor authentication for production-system access.`

**Draft:** `Yes. All employees use MFA for production-system access.`

**Score:** 2 / 0 / 0 / 0 = **2/8**, critical scope overclaim. **Decision:** Reject suggestion. The source only covers administrators.

## E03 — Correct abstention

**Question:** Are supplier backups encrypted at rest?

**Source:** Uploaded example policy discusses backup frequency but says nothing about encryption.

**Draft:** `I could not find evidence about encryption at rest in the uploaded documents. Please provide a relevant policy or answer manually.`

**Score:** 2 / 0 / 2 / 2 = **6/8**. **Decision:** Manual review. The system appropriately abstains, but there is no cited passage supporting a control answer. Route the underlying questionnaire item for manual completion.

## E04 — Conflicting documents

**Question:** Are security access reviews performed quarterly?

**Sources:** `Policy A` says quarterly; a newer `Policy B` says semiannually. Neither is identified as the authoritative current policy.

**Draft:** `The uploaded documents conflict: one says quarterly and another says semiannually. Please confirm the current policy before answering.`

**Score:** 2 / 2 / 2 / 2 = **8/8**. **Decision:** Manual review, despite the high score, because the facts remain unresolved. The draft handles uncertainty correctly; it does not establish a final control assertion.

## Takeaway

Score the response behavior and the final business decision separately. A well-written abstention can safely prevent an unsupported answer while the questionnaire item stays unresolved.
