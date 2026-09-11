---
name: mentari-llc-tax-filing
description: Prepare and review U.S. IRS and New Mexico filing records for a foreign-owned New Mexico single-member LLC. Use when Mentari asks to classify the LLC, prepare Form 5472/pro forma Form 1120 or Form 1120 materials, organize Apple/payment records, review W-8/W-9 questions, build transaction ledgers, or create filing checklists. Never invent tax IDs, sign forms, submit filings, or expose private documents without explicit confirmation.
---

# Mentarich LLC tax filing assistant

## Scope and safety

This skill organizes evidence and explains official filing instructions. It is not a tax return, legal opinion, tax-residency determination, treaty ruling, or substitute for a qualified tax professional. Treat all tax conclusions as conditional until the entity classification, ownership, tax year, transactions, and income source are verified.

Never:

- invent or guess an EIN, SSN, ITIN, Indonesian TIN, address, tax rate, treaty article, or exchange rate;
- claim that an EIN proves corporate tax treatment;
- treat a U.S. mailing or registered-agent address as the owner's residence;
- sign, upload, fax, mail, or submit a tax form without the user's explicit instruction after reviewing the completed form;
- commit PDFs, bank statements, tax IDs, API keys, passwords, card images, or account credentials to a public repository;
- claim that W-8BEN, W-9, Form 5472, or Form 1120 is required without stating the facts and source supporting the conclusion.

Use redacted copies for GitHub. Keep sensitive records in the user's local Mentarich LLC folder.
If a private `PRIVATE-SOURCES.txt` file exists beside this skill, use it only as a local source index and read the referenced records directly; never copy source contents into public repository files.

## Workflow

### 1. Establish the facts

Read only the relevant local records and record an evidence matrix. Confirm:

- legal name and state of formation;
- formation date and state/entity ID;
- number of members and ownership percentages;
- owner citizenship, tax residence, and actual permanent address;
- EIN and responsible-party information without repeating the number in chat or repository files;
- tax year and accounting method if known;
- whether Form 8832, Form 2553, a prior Form 1120, Form 5472, or other IRS election/return exists;
- employees, excise-tax activities, U.S. offices, agents, or other U.S. business activity;
- Apple, Stripe, Wise, bank, contractor, owner, and related-party transactions.

Do not infer a tax election from a state formation certificate, EIN letter, operating agreement, Apple account, or bank account.

### 2. Determine the federal classification path

Use the current IRS instructions and state the decision as conditional:

- A domestic single-member LLC is generally disregarded for federal income tax unless it filed Form 8832 to elect corporate treatment.
- A disregarded LLC's income-tax activity generally belongs on the owner's return; an EIN may still be used for banking, employment tax, or excise-tax reasons.
- A foreign-owned U.S. disregarded entity is treated as a corporation for limited section 6038A reporting purposes. If it has reportable transactions, Form 5472 may need to be attached to a pro forma Form 1120.
- If Form 8832 elected corporate treatment, analyze Form 1120 and related international filings instead.
- If income is effectively connected with a U.S. trade or business, analyze Form 1040-NR/Form 1120-F or another applicable return; do not use W-8BEN for income that should be documented with Form W-8ECI.
- New Mexico filing obligations are separate from IRS obligations and require current New Mexico guidance.

### 3. Handle Apple and withholding forms carefully

Explain the distinction:

- Form W-8BEN is a withholding certificate for a foreign individual beneficial owner. Give it to Apple or another withholding agent; do not send it to the IRS as a tax return.
- Form W-8BEN-E is for a foreign entity, not automatically for a U.S. LLC with a foreign individual owner.
- Form W-9 certifies U.S.-person status. A foreign owner of a disregarded entity must not sign a W-9 merely because the LLC has a U.S. address or EIN.
- A treaty rate must not be guessed. First identify the payment type, treaty residence, beneficial ownership, and any required conditions.
- Ask Apple to confirm its classification of developer proceeds and the correct upload workflow when App Store Connect's U.S.-based account flow conflicts with the IRS documentation path.

### 4. Build the records package

Create or update a local preparation folder containing:

- README/decision memo;
- checklist;
- transaction ledger;
- formation and governance records;
- EIN notice;
- owner and tax-residency evidence;
- Apple agreements, sales/proceeds reports, payouts, fees, tax statements, and correspondence;
- Wise/bank/payment-processor statements;
- expense receipts and business purpose;
- owner-to-LLC contribution, distribution, loan, reimbursement, service, and IP records;
- copies of forms submitted to Apple and IRS filing receipts.

For each transaction record date, counterparty, country, description, business purpose, currency, original amount, USD conversion, fees, account, owner-related status, evidence path, and possible filing relevance.

### 5. Identify Form 5472 issues

Review whether the LLC had transactions involving the foreign owner or another related party. Pay particular attention to:

- formation and capital contributions;
- distributions;
- loans and interest;
- owner-paid or LLC-paid expenses;
- reimbursements;
- transfers of property or intellectual property;
- services between owner and LLC;
- acquisition, disposition, or dissolution transactions.

Do not assume that no revenue means no reportable transaction. Do not assume that every Apple payout is a Form 5472 transaction; classify the counterparty and transaction using the current instructions.

### 6. Produce a decision-oriented result

End every review with:

1. facts confirmed;
2. facts still missing;
3. likely classification path;
4. forms that may apply and forms that do not appear applicable;
5. records still needed;
6. exact next action;
7. official source links and the date checked.

Use labels such as **Confirmed**, **Conditional**, **Unknown**, and **Do not submit yet**. Never present a conditional filing path as a completed tax conclusion.

## Official sources to check

Prefer current primary sources:

- IRS single-member LLC guidance: https://www.irs.gov/businesses/small-businesses-self-employed/single-member-limited-liability-companies
- IRS Form W-9: https://www.irs.gov/pub/irs-pdf/fw9.pdf
- IRS Form W-8BEN instructions: https://www.irs.gov/pub/irs-pdf/iw8ben.pdf
- IRS Form W-8BEN-E instructions: https://www.irs.gov/pub/irs-pdf/iw8bene.pdf
- IRS Form 5472 instructions: https://www.irs.gov/instructions/i5472
- IRS Form 1120: https://www.irs.gov/forms-pubs/about-form-1120
- IRS Form 7004: https://www.irs.gov/forms-pubs/about-form-7004
- IRS Form 8832: https://www.irs.gov/forms-pubs/about-form-8832
- Apple tax information: https://developer.apple.com/help/app-store-connect/manage-tax-information/provide-tax-information/
- New Mexico Secretary of State business services: https://www.sos.nm.gov/business-services/

When a source conflicts with a previous answer, correct the answer explicitly and preserve the source-based reasoning.
