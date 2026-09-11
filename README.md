# US Tax Filing Skill

A task-oriented AI tax-preparation skill for founders who need to prepare U.S. federal and New Mexico tax records without paying for a full-service tax consultant.

The skill is designed for evidence-first self-service preparation. It helps a founder understand classification, collect records, reconcile transactions, map form fields, prepare drafts, and create a clean package for filing or targeted professional review.

## What it covers

- domestic single-member LLC classification: disregarded entity versus corporate election;
- foreign-owned U.S. disregarded entity screening;
- Form 5472 and pro forma Form 1120 preparation workflow;
- Form 8832 election-risk checklist;
- Form W-8BEN, W-9, W-8BEN-E, and W-8ECI decision controls;
- Form 1040-NR and effectively connected income screening;
- Form 7004 extension workflow;
- New Mexico registration, gross receipts, withholding, and corporate-tax screening;
- Apple App Store Connect and payment-platform tax-document workflows;
- transaction-ledger, exchange-rate, owner-related transaction, and submission-proof controls;
- low-cost founder workflow and escalation triggers.

## Display name and identifier

- Display name: **US Tax Filing Skill**
- Technical identifier: `us-tax-filing`

## Installation

### GitHub-based agent

Copy `.github/skills/us-tax-filing/` into an agent project that supports the `.github/skills/<name>/SKILL.md` convention.

### Other LLMs and agent frameworks

The skill is plain Markdown with YAML frontmatter and contains no vendor-specific API calls. Any LLM can use it when the file is supplied as a system/developer instruction or loaded by an agent framework. Automatic discovery depends on that framework's directory convention; a GitHub repository by itself does not make every LLM load the skill automatically.

Keep the actual tax documents outside the repository.

## Example requests

- “Review my foreign-owned New Mexico single-member LLC filing path.”
- “Build the Form 5472 related-party transaction ledger.”
- “Map every field in Form W-8BEN to my private source documents.”
- “Check whether Apple is asking for the right withholding form.”
- “Prepare a pro forma Form 1120 and Form 5472 draft checklist; do not sign or submit.”
- “Create a deadline calendar and identify missing evidence for my first tax year.”
## AI tax-agent mode

The skill can be used as a controlled AI tax-preparation agent. It can read private source records, build a classification decision tree, reconcile transactions, map form fields, create unsigned drafts, run quality checks, create a deadline calendar, guide the user through the required submission channel, and archive submission proof.

It supports an end-to-end state flow: evidence collection, classification, reconciliation, draft form, quality check, user review, authorization, signature, submission, and proof archive. It pauses before an irreversible submit, certification, fax, or mailing action unless the user explicitly authorizes that exact step. It does not sign for the user, certify under penalty of perjury, or hide unresolved facts.

## Annual self-service workflow

1. Close the transaction ledger.
2. Confirm entity classification and Form 8832 evidence.
3. Screen owner and related-party transactions.
4. Reconcile Apple/payment/bank records.
5. Map each applicable form field to evidence.
6. Review the deadline and current filing method.
7. Produce an unsigned draft and risk gate.
8. Obtain user approval, signature, and submission proof.


## Self-service principle

Founders can often perform the evidence collection, bookkeeping reconciliation, source checking, and draft preparation themselves. The skill does not promise that every filing is safe to submit without professional review. It flags high-risk cases such as late filings, elections, ECI, treaty positions, related-party IP/loans, payroll, state nexus, and IRS or New Mexico notices.

The user remains responsible for the truth of the information, signature, certification, payment, and submission.

## Privacy

Do not commit or paste into the public repository:

- EIN, SSN, ITIN, Indonesian TIN, full residential address, bank account numbers;
- tax returns, IRS notices, signatures, identity documents, or private Apple case attachments;
- bank statements, Apple payment reports, API keys, passwords, or card images.

Use the private local source index for personal LLC documents. Public skill files contain workflow logic only.

## License

MIT
