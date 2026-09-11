# US Tax Filing Skill

A task-oriented OMP/GitHub Agent Skill for founders who need to prepare U.S. federal and New Mexico tax records without paying for a full-service tax consultant.

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

### GitHub Agent Skills

Copy `.github/skills/us-tax-filing/` into a project repository. The skill is discovered from the standard `.github/skills/<name>/SKILL.md` location.

### OMP user skill

Copy the same skill directory into the user's configured OMP/Agent Skills directory. Keep the actual tax documents outside the repository.

## Example requests

- “Review my foreign-owned New Mexico single-member LLC filing path.”
- “Build the Form 5472 related-party transaction ledger.”
- “Map every field in Form W-8BEN to my private source documents.”
- “Check whether Apple is asking for the right withholding form.”
- “Prepare a pro forma Form 1120 and Form 5472 draft checklist; do not sign or submit.”
- “Create a deadline calendar and identify missing evidence for my first tax year.”

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
