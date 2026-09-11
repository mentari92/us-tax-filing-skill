---
name: us-tax-filing
description: US Tax Filing Skill for founders and foreign-owned New Mexico single-member LLCs. Use to classify an LLC, decide which U.S. and New Mexico forms may apply, prepare field-by-field W-8/W-9, Form 5472, pro forma Form 1120, Form 8832, Form 7004, Form 1040-NR, payroll, information-return, and New Mexico registration checklists, reconcile Apple App Store, Google Play Android, Stripe, Wise, and bank records, and produce a submission-ready evidence package. Never invent tax facts, sign forms for the user, submit filings without explicit approval, or expose private records.
---

# US Tax Filing Skill

## Important boundary

This skill is a low-cost, self-service preparation system. It can help a founder understand instructions, organize records, draft field maps, reconcile transactions, and catch missing information. It does **not** guarantee that a filing is correct, does not create an attorney-client or accountant-client relationship, and does not replace professional review for complex or uncertain facts.

The goal is to make a founder capable of doing the routine work themselves and paying for targeted review only when the risk justifies it. Never pressure the founder to hire a consultant for a routine evidence-collection task. Never promise that a consultant is unnecessary when the facts involve an election, U.S. trade or business, treaty position, transfer pricing, late filings, ownership changes, or material penalties.

The user signs certifications and returns. The user decides whether to submit. The skill prepares evidence and explains choices.
## International founder compatibility

This skill can be used by founders from any country who own or control a U.S. company. It is not limited to Indonesian owners or New Mexico LLCs, but the United States federal rules, state rules, and owner-country rules must be analyzed as separate layers.

### Required country profile

For a non-U.S. founder, collect:

- citizenship and every country of tax residence;
- actual permanent residence and mailing address;
- U.S. immigration/residency status and days physically present in the U.S.;
- foreign tax identification number and whether the country legally issues one;
- entity state and legal type;
- entity tax classification and elections;
- member/shareholder/partner ownership;
- where services are physically performed;
- client and payer countries;
- foreign tax returns, withholding certificates, and foreign tax paid;
- applicable tax treaty and residence evidence.

### General U.S. layer

The U.S. layer can usually be reused for foreign founders in different countries:

- domestic single-member LLC default classification;
- foreign-owned U.S. DE and Form 5472 screening;
- pro forma or full Form 1120 path;
- W-8BEN/W-8BEN-E/W-8ECI versus W-9;
- Form 1040-NR and ECI screening;
- U.S. source rules;
- payroll, information returns, withholding, and state obligations;
- platform and client payment reconciliation.

### Country layer

The owner's home-country layer is configurable, not universal. Do not reuse Indonesia's worldwide-income, SPT, NPWP/NIK, or PPh Pasal 24 instructions for a founder resident in another country. For each country, obtain current tax-authority guidance for:

- tax-residence test;
- worldwide or territorial income treatment;
- individual versus company reporting;
- foreign tax credit or exemption;
- exchange-rate rules;
- business-expense rules;
- social contributions;
- annual-return form and deadline;
- treaty relief and documentation.

If current country-specific rules are unavailable, complete the U.S. analysis and records package, label the home-country section **Country rules not verified**, and do not invent a local form or tax rate.


## Non-negotiable safety rules

Never:

- invent or guess an EIN, SSN, ITIN, Indonesian TIN, address, tax year, accounting method, tax rate, treaty article, exchange rate, signature, or filing status;
- treat a state formation certificate, EIN, bank account, Apple account, registered-agent address, or operating agreement as proof of federal tax classification;
- treat a U.S. registered-agent or mailing address as the owner's actual residence or tax residence;
- tell a foreign owner to sign Form W-9 merely because the LLC is formed in the United States or has an EIN;
- claim a treaty rate without identifying the payment type, treaty residence, beneficial owner, applicable article, and required conditions;
- fill a field from memory when the current form or instructions require a specific value;
- sign, upload, fax, mail, e-file, or submit a tax form without the user's explicit approval after the completed form is reviewed;
- remove a form from consideration solely because the LLC had no revenue;
- file a duplicate return when a prior filing may exist without first confirming filing status;
- commit tax returns, IRS notices, bank statements, payment reports, identifiers, signatures, API keys, passwords, or account credentials to a public repository;
- present a conditional conclusion as a completed tax conclusion.

Use the labels **Confirmed**, **Conditional**, **Unknown**, **Needs source**, and **Do not submit yet**.

## Founder self-service strategy

Use a three-pass process. Do not start by typing into a form.

### Pass 1 — Classification

1. Establish who owns the entity and where that owner is a tax resident.
2. Establish whether the entity is domestic or foreign under U.S. rules.
3. Establish member count and ownership percentages.
4. Search specifically for Form 8832, Form 2553, prior Forms 1120/5472, and IRS acceptance or filing proof.
5. Identify whether the owner or entity is a U.S. person for the particular form.
6. Screen for a U.S. trade or business, effectively connected income (ECI), employees, excise tax, and New Mexico business activity.
7. Decide which filing path is plausible. Keep alternatives open when evidence is incomplete.

### Pass 2 — Reconciliation

1. Build a transaction ledger before calculating totals.
2. Reconcile Apple App Store, Google Play Android, Stripe, and other platform sales/proceeds reports to payouts, Wise/bank deposits, fees, refunds, taxes, chargebacks, disputes, and foreign-exchange conversion.
3. Identify every owner-to-LLC and LLC-to-owner movement: contribution, distribution, loan, reimbursement, service, IP transfer, or mixed/personal payment.
4. Identify related parties and classify each transaction by counterparty, not by bank account label.
5. Tie each number in a proposed form to a source record and calculation.
6. Keep a list of unresolved facts. Do not hide uncertainty by using zero.

### Pass 3 — Form preparation

For each form:

1. Download the current form and instructions for the relevant tax year from IRS.gov or the relevant state agency.
2. Make a field map: form line, proposed value, source, basis, confidence, and unresolved issue.
3. Complete a draft without signature.
4. Run the pre-submission checks in this skill.
5. Export a PDF copy, evidence index, calculation workbook, and submission log.
6. Obtain the user's review and explicit approval.
7. Submit only through the method stated in the current official instructions.
8. Save proof of submission, fax confirmation, certified mail, payment confirmation, or e-file acceptance.

## Facts to establish first

Create a fact sheet with one row per fact:

| Fact | Value | Source | Status | Why it matters |
|---|---|---|---|---|
| Legal name |  | Formation record |  | Return name |
| State and formation date |  | State filing |  | Domestic status and first tax year |
| Entity ID |  | State filing |  | State records |
| Members and ownership |  | Operating agreement/resolutions |  | Classification and related party |
| Owner citizenship |  | Owner evidence |  | Foreign-person analysis |
| Owner tax residence |  | Tax-residency evidence |  | W-8BEN and treaty screening |
| Actual permanent residence |  | Owner evidence |  | W-8BEN line 3 |
| Registered-agent address |  | State filing |  | Entity correspondence only |
| EIN |  | IRS notice |  | Use only where required; never repeat in public output |
| Tax year |  | Prior return/election/instructions |  | Due date |
| Accounting method |  | Books/return |  | Transaction timing |
| Form 8832 filed? |  | IRS filing proof |  | Classification |
| Form 2553 filed? |  | IRS filing proof |  | S-election analysis |
| Prior returns |  | IRS transcript/records |  | Avoid duplicate or late filing |
| U.S. trade or business facts |  | Contracts, location, personnel |  | ECI and 1040-NR/1120-F screening |
| New Mexico activity |  | Customers, services, property, personnel |  | TRD registration and GRT |

Never use the word “confirmed” unless the source is identified.

## Decision tree for a New Mexico single-member LLC

### Step A — Federal entity classification

A domestic LLC with one member is generally disregarded for federal income tax unless it affirmatively elects corporate treatment on Form 8832. A disregarded LLC's income-tax activity is generally reflected on the owner's federal return. For employment tax and certain excise taxes, a disregarded LLC is treated as a separate entity and may use its own EIN.

Do not infer the election from the existence of an EIN. The controlling evidence is the election and its effective date, prior return position, IRS acceptance, or another reliable filing record.

### Step B — Foreign-owned U.S. disregarded entity screen

If the domestic single-member LLC is disregarded and wholly owned by a foreign person, it is treated as a corporation for limited section 6038A reporting purposes. If it had reportable transactions, it may need Form 5472 attached to a pro forma Form 1120 even though it has no ordinary corporate income-tax return requirement.

No revenue does not automatically mean no Form 5472 issue. Formation contributions, distributions, loans, reimbursements, owner-paid expenses, services, IP transfers, dissolution, acquisition, and disposition must be screened.

### Step C — U.S. trade or business and ECI screen

Ask:

- Were services physically performed in the United States?
- Was there a U.S. office, dependent agent, employee, inventory, or regular U.S. operating activity?
- Was income connected with a U.S. trade or business?
- Is the payment a royalty, interest, dividend, service payment, platform payment, or business profit?
- Does a treaty article alter the result, and is a permanent establishment analysis required?

If ECI may exist, do not use Form W-8BEN as a substitute for analyzing Form W-8ECI and Form 1040-NR or another return. Escalate if the conclusion depends on permanent establishment, source, transfer pricing, or treaty interpretation.

### Step D — New Mexico screen

New Mexico obligations are separate from federal obligations. Review whether the LLC is engaging in business in New Mexico, has New Mexico-source receipts, sells taxable goods or services, has employees, or owes gross receipts, compensating, withholding, or other state taxes. The New Mexico Taxation and Revenue Department states that anyone engaging in business in New Mexico must register, subject to the agency's stated rules and thresholds.

Do not conclude that formation in New Mexico alone proves gross receipts tax liability. Do not conclude that a remote foreign owner has no state obligation without checking the activity and sourcing facts.

## Form selection matrix

Use this table as a screening tool, not as an automatic filing order.

| Form or record | Typical trigger | What the skill prepares | Stop/escalate condition |
|---|---|---|---|
| Form W-8BEN | Foreign individual beneficial owner documents status to a withholding agent | Field map and treaty-evidence checklist | ECI, hybrid-entity treaty claim, uncertain residence, or treaty rate |
| Form W-9 | U.S. person provides TIN and certification | Classification check only | Owner is foreign, requester insists on W-9 despite foreign status, or payee identity is unclear |
| Form W-8BEN-E | Foreign entity documents status | Entity classification checklist | U.S. LLC is being incorrectly treated as foreign entity or entity treaty claim is unclear |
| Form W-8ECI | Foreign person claims income is effectively connected with a U.S. trade or business | Source/ECI evidence checklist | ECI or permanent establishment is uncertain |
| Form 8832 | Eligible entity elects federal classification | Election-timing and effective-date worksheet | Retroactive election, late election relief, or classification change consequences |
| Form 5472 | Reporting corporation/foreign-owned U.S. DE had reportable transaction with related party | Related-party ledger, line map, schedules, filing method checklist | Missing related-party evidence, valuation, loans, IP, or prior filing |
| Pro forma Form 1120 | Foreign-owned U.S. DE attaches Form 5472 | Current-year name/address/items required by instructions | Ordinary corporate income or corporate election exists |
| Form 1120 | Domestic corporation files corporate income tax return | Income/expense and schedule inventory | Complex deductions, foreign activity, credits, or late return |
| Form 7004 | Automatic extension for eligible returns | Due-date and form-code checklist | Extension does not solve payment, classification, or late prior-year issues |
| Form 1040-NR | Nonresident individual may have U.S. trade/business or taxable U.S. income | Individual-return screening and Schedule C/NEC/OI checklist | ECI, treaty, sourcing, or ITIN issues |
| Form SS-4 | EIN application or certain EIN needs | EIN need and responsible-party checklist | Existing EIN conflict or responsible-party change |
| Form 941/940 | Employees and payroll | Payroll obligation screen | Any employee, wage, or worker-classification dispute |
| Form 1099-NEC/MISC | U.S. business payments meeting reporting rules | Vendor/payment classification checklist | Foreign vendor, payments through platforms, missing W-9/W-8, or mixed personal/business payments |
| New Mexico BTIN/GRT/withholding filings | State business-tax activity | Registration and filing-period checklist | Sourcing, nexus, exemption, or taxability uncertainty |

Screen other international information forms only when facts support them. Do not automatically add Forms 5471, 5472, 8858, 8938, 3520, FBAR, or treaty disclosures merely because the founder is foreign or the LLC has a foreign bank account.
## Annual filing playbook

Do not assume that the same forms are filed every year. First classify the LLC and then screen the year's transactions, owner status, U.S. activity, and New Mexico activity.

### Likely first-year path for a foreign-owned domestic single-member LLC

If the LLC is a domestic single-member LLC, has no Form 8832 corporate election, is wholly owned by a foreign individual, and uses a calendar tax year:

1. It is generally a disregarded entity for federal income tax.
2. Its ordinary income-tax activity generally belongs on the owner's return, subject to the owner's U.S. filing triggers.
3. It is treated as a corporation for limited section 6038A reporting purposes.
4. Formation contributions, owner-paid expenses, reimbursements, distributions, loans, services, IP transfers, acquisition, disposition, or dissolution can create Form 5472 questions even if revenue is zero.
5. If a reportable transaction exists, prepare Form 5472 attached to a pro forma Form 1120.
6. If an election, corporate income, ECI, or inconsistent facts exist, stop using this shortcut and analyze the alternative return path.

For a calendar-year entity whose first tax year is 2026, the practical planning date for the pro forma Form 1120/Form 5472 package is generally April 15, 2027. This is a planning estimate, not a permanent deadline. Re-check the current Form 5472 instructions for weekends, holidays, disaster relief, tax-year differences, and filing-method changes.

Form 7004 is generally the extension request for eligible business returns. If accepted, it normally provides six additional months to file, so a calendar-year 2026 planning extension would generally reach October 15, 2027. An extension does not fix classification, erase a penalty, or automatically extend payment obligations. Confirm the current form code, address, fax method, and due date before submission.

### Annual form matrix

| Item | Annual? | When to prepare |
|---|---|---|
| Form 5472 | Conditional but high-priority screen | Foreign-owned U.S. DE had a reportable related-party transaction |
| Pro forma Form 1120 | Conditional | Attached to Form 5472 for a foreign-owned U.S. DE |
| Full Form 1120 | Conditional | LLC elected corporate treatment or is otherwise a domestic corporation |
| Form 7004 | Optional extension | More time is needed to file an eligible return; file by original deadline |
| Form W-8BEN | No | Give to Apple/payment platform/withholding agent; renew on validity or change-of-circumstances rules |
| Form W-9 | No | Only when the relevant payee/owner is actually a U.S. person |
| Form W-8BEN-E | No | Foreign entity is the beneficial owner or account holder and the form is appropriate |
| Form W-8ECI | No | Foreign person certifies income is effectively connected with a U.S. trade or business |
| Form 8832 | No | Entity classification election or change; do not repeat annually |
| Form 1040-NR | Conditional | Foreign individual has a U.S. individual filing trigger, including possible U.S. trade/business or ECI |
| Form 941/940 | Conditional | Employees or wages trigger payroll filings |
| Form 1099-NEC/MISC | Conditional | Payment and recipient facts meet information-reporting rules |
| New Mexico BTIN/GRT/withholding filings | Conditional and frequency-based | New Mexico business-tax activity and the filing frequency assigned by NM TRD |

The form matrix must always state **May apply**, **Appears not applicable**, or **Unknown**. Do not silently turn an unknown form into “not required.”

### Annual calendar

Maintain these dates for each tax year:

- tax-year start and end;
- original federal due date;
- Form 7004 deadline;
- extension due date;
- W-8 date provided and validity/change-of-circumstances review date;
- New Mexico registration and assigned filing periods;
- payroll and information-return deadlines if triggered;
- internal ledger-close date;
- draft-review date;
- signature date;
- submission date;
- proof-of-submission storage path.

### Annual founder checklist

Before preparing the return package, collect:

1. Formation document.
2. EIN notice.
3. Operating agreement.
4. Initial resolutions.
5. Form 8832/Form 2553 evidence or evidence that none was found.
6. Prior tax returns, IRS notices, transcripts, and submission receipts.
7. Owner contributions and capital records.
8. Owner-paid LLC expenses.
9. Reimbursements and distributions.
10. Owner/LLC loans and interest.
11. Apple App Store, Google Play, and other marketplace sales/proceeds reports.
12. Apple, Google Play, Stripe, and other platform payout reports.
13. Wise, bank, Stripe balance-transaction, and payment-processor statements.
14. Fees, refunds, chargebacks, withholding, and foreign exchange records.
15. Contracts and invoices with related parties.
16. IP, software, domain, or asset transfers.
17. Contractor and employee records.
18. New Mexico registration and tax account notices.
19. Exchange-rate schedule and calculation workbook.
20. Unsigned form drafts and the submission log.

### Practical decision path

```text
Domestic single-member LLC
  ↓
Check Form 8832 and prior filing evidence
  ↓
No election confirmed or likely?
  ↓
Disregarded-entity analysis
  ↓
Foreign owner?
  ↓
Screen owner and related-party transactions
  ↓
Reportable transaction?
  ├─ Yes → Form 5472 + pro forma Form 1120
  └─ Unknown → finish ledger; do not assume zero
  ↓
Screen U.S. trade/business and ECI
  ↓
Screen New Mexico business-tax activity
```

### Payment and penalty control

Form 5472/pro forma Form 1120 is primarily an information-reporting package for the foreign-owned U.S. DE path; do not assume that this package alone creates an income-tax payment. Conversely, do not assume that no payment is due merely because Form 5472 is informational. Analyze owner-level tax, ECI, corporate election, payroll, excise, withholding, and New Mexico obligations separately.

The current Form 5472 instructions state that failure to file when required can result in a $25,000 penalty, with additional penalties if the failure continues after IRS notice. If a deadline may have been missed:

- do not backdate a signature;
- do not file a duplicate without checking filing history;
- do not invent a zero;
- locate prior submission proof or IRS transcript;
- identify the correct tax year and form revision;
- prepare the evidence package;
- evaluate penalty-relief or targeted professional-review options.

### Mentarich private-records rule

For a user's private Mentarich LLC workspace, the skill may use a local `PRIVATE-SOURCES.txt` index and the documents it references. Do not copy EINs, residential addresses, signatures, bank data, tax notices, or PDF contents into this public skill. Use the private documents as evidence for the fact sheet, ledger, field map, and annual filing decision.

## W-8BEN field-by-field preparation

Use the current Form W-8BEN and instructions. The following is a preparation map for a foreign individual who owns a disregarded entity and is not claiming a hybrid-entity treaty position.

### Part I

- **Line 1 — Name:** Enter the foreign individual beneficial owner's legal name, not automatically the LLC name. Match the owner's identity and payment records.
- **Line 2 — Citizenship:** Enter the country of citizenship. A citizenship country is not automatically the treaty-residence country.
- **Line 3 — Permanent residence address:** Enter the actual permanent residence in the country where the owner claims tax residence. Do not use a registered-agent, bank, PO box, or mailing-only address.
- **Line 4 — Mailing address:** Complete only if different from line 3.
- **Line 5 — U.S. TIN:** Enter SSN/ITIN when required or available for the specific claim. Do not manufacture or reuse the LLC EIN as the owner's SSN/ITIN.
- **Line 6a — Foreign TIN:** Use the owner's foreign tax identification number when required and available. For an Indonesian resident, verify the current NPWP/NIK treatment with the Indonesian records and current IRS instructions; do not guess which identifier is accepted.
- **Line 6b — FTIN not legally required:** Check only if the instructions and the owner's jurisdiction facts support that statement. Lack of a convenient number is not the same as legal non-requirement.
- **Line 7 — Reference number:** Use to identify the LLC account or payment relationship when useful. It may identify the disregarded-entity account; it does not change who owns the income.
- **Line 8 — Date of birth:** Complete when the requester requires it for a financial-account context under the instructions. Do not place it in public notes.

### Part II — treaty claim

- **Line 9:** Enter the treaty-residence country only when the owner is resident under the treaty, not merely because the owner is a citizen there.
- **Line 10:** Complete only when the treaty claim requires additional conditions, such as business profits, royalties with different rates, or a permanent-establishment representation. Identify the exact income type, article, rate, and supporting facts. Never copy a treaty rate from a generic internet table.

### Part III

- The beneficial owner or an authorized agent signs and dates the form.
- Electronic signature rules belong to the withholding agent's accepted process. Typed text alone is not automatically an electronic signature.
- Give Form W-8BEN to the requester/withholding agent; do not send it to the IRS as an income-tax return.
- Track the date provided, requester, income type, validity period, and any change in circumstances. A new form may be required when facts change.

## W-9 decision controls

Form W-9 certifies U.S.-person status. The owner of a disregarded entity is the relevant person for income-tax information reporting. A foreign individual cannot sign Form W-9 as a U.S. person merely because the LLC is domestic or has an EIN.

When a platform asks for W-9:

1. Save the exact platform prompt and account classification.
2. Determine whether the payee is the LLC, the owner, or a payment intermediary.
3. Determine federal tax classification and owner U.S./foreign status.
4. Ask the platform for the W-8 workflow if the owner is foreign.
5. Provide W-9 only if the owner/payee is actually a U.S. person and the certification is true.
6. Save the platform's response as evidence.

## Form 5472 and pro forma Form 1120 preparation

### Filing trigger

The current Form 5472 instructions treat a foreign-owned U.S. DE as a reporting corporation for limited section 6038A purposes. If it has a reportable transaction, Form 5472 is attached to a pro forma Form 1120. The instructions state that a foreign-owned U.S. DE cannot file Form 5472 electronically and must use the dedicated fax or mailing method in the current instructions. Re-check the address and fax number every filing year.

The instructions also state that failure to file Form 5472 when required can result in a $25,000 penalty, with additional penalties if the failure continues after notice. This is why the skill must never reduce the analysis to “no revenue, no filing.”

### Related-party ledger

For each counterparty, record:

- legal name and country;
- owner/related-party relationship;
- U.S. TIN, foreign TIN, or stable internal reference ID only in the private workbook;
- opening balance, transaction date, amount, currency, exchange rate, USD amount;
- transaction type;
- whether monetary, nonmonetary, or less than full consideration;
- business purpose and agreement;
- evidence path;
- candidate Form 5472 part/line;
- unresolved valuation or classification issue.

Use one separate Form 5472 per foreign or U.S. related party with reportable transactions, subject to the current instructions.

### Form 5472 field map

Use the current revision for exact line labels. At minimum, review:

- **Part I:** reporting corporation identity, address, assets, business activity/code, total foreign related-party amounts, number of Forms 5472, first-year indicator, principal countries, and the foreign-owned U.S. DE checkbox.
- **Part II:** direct and ultimate foreign owner information, U.S. identifying number if any, reference ID if needed, foreign TIN, and ownership attribution explanation.
- **Part III:** related-party identity. Complete it even if the party also appears in Part II.
- **Part IV:** monetary transactions with a foreign related party. Use U.S. dollars and attach exchange-rate schedules. Separate received and paid amounts; do not net them unless the instructions permit the treatment.
- **Part V:** for a foreign-owned U.S. DE, describe other reportable transactions not already reported in Part IV, including formation, dissolution, acquisition, disposition, contributions, and distributions.
- **Part VI:** nonmonetary or less-than-full-consideration transactions; describe property, rights, obligations, services, and estimated fair market value.
- **Part VII:** additional information. Do not skip it; follow the current instructions for each yes/no and amount.
- **Part VIII/IX:** complete only if the facts trigger cost-sharing, platform-contribution, base-erosion, or related rules.

### Pro forma Form 1120 controls

For a foreign-owned U.S. DE with no corporate income-tax return requirement, the Form 5472 instructions state that only the specified name/address and first-page items are completed on the pro forma Form 1120. Write **Foreign-owned U.S. DE** across the top when the instructions require it. Do not use the ordinary Form 1120 mailing address; use the dedicated method in the current Form 5472 instructions.

If the LLC elected corporate treatment, has ordinary corporate income, or has facts inconsistent with a pure pro forma return, stop using the DE shortcut and analyze the full Form 1120 path.

### Form 5472 quality checks

- Every Part IV/VI number is in USD and has an exchange-rate source.
- Paid and received amounts are not incorrectly netted.
- Owner contributions and distributions are separately identified.
- Owner-paid expenses and reimbursements are not silently treated as zero.
- The related-party name is consistent across Parts II and III.
- The same reference ID is used consistently year to year.
- Foreign TIN handling follows the current instructions.
- Every Form 5472 has the required attachment schedules.
- The filing method, address, fax quality, and proof of delivery are current.
- A second person or later self-review checks the form against the ledger.

## Form 8832 decision controls

Do not prepare Form 8832 casually. Establish:

- intended classification;
- election effective date;
- whether the entity is eligible;
- whether the election is timely;
- whether a prior election or default classification already applies;
- whether the election creates full corporate returns, accounting, payroll, withholding, or state consequences;
- whether a retroactive election or late-election relief is involved.

A classification election can change future filing obligations. If the user is deciding whether to make an election rather than documenting an existing election, label the result **planning analysis**, not a filing instruction, and escalate if the consequences are material.

## Form 1040-NR and owner-level screening

A foreign owner of a disregarded LLC may need an individual U.S. return if the owner's facts create a U.S. trade or business, ECI, U.S.-source income, or another filing trigger. Form 1040-NR is for nonresident alien individuals, estates, and trusts that meet the applicable filing conditions.

Do not assume that the LLC's state of formation, Apple App Store account, Google Play account, Stripe account, bank account, or U.S. registered agent alone proves that the owner must or must not file Form 1040-NR. Analyze services location, agents, U.S. activity, income source, treaty position, and withholding records.
## Client geography, service location, and owner-country reporting

Do not decide U.S. tax treatment from the client's country alone. For personal services and business income from personal services, the primary U.S. source rule is generally **where the services are physically performed**. Client location, contract location, invoice currency, bank location, and payment route do not by themselves determine the source.

### Client and service-location matrix

| Client | Where founder performs the work | U.S. source result | U.S. filing screen |
|---|---|---|---|
| U.S. client | Indonesia or another country outside the U.S. | Generally foreign-source personal-service income | Usually no U.S. tax on that service income solely because the client is American; provide appropriate W-8 documentation when requested |
| Non-U.S. client | Indonesia or another country outside the U.S. | Generally foreign-source personal-service income | Usually no U.S. tax on that service income solely because the LLC is domestic; owner-country reporting still applies |
| U.S. client | Physically in the U.S. | Generally U.S.-source for the services performed in the U.S. | Screen U.S. trade/business, ECI, Form 1040-NR, Form W-8ECI, withholding, and travel-day records |
| Non-U.S. client | Physically in the U.S. | Generally U.S.-source for the services performed in the U.S. | Same U.S. activity and ECI screen; foreign client status does not make U.S.-performed services foreign-source |
| Any client | Work split between U.S. and foreign countries | Allocate using actual service dates, location, and work performed | Keep a day-by-day travel and service log; do not allocate only by invoice or payment date |

These are starting rules, not automatic conclusions. Royalties, software/IP licenses, dividends, interest, rents, inventory, digital products, and platform sales have different source rules. Classify the income before applying the personal-service rule.

### U.S. client while working outside the U.S.

For a foreign individual who is a nonresident alien and performs services entirely outside the United States:

1. The service income is generally foreign-source for U.S. tax purposes.
2. It is generally not subject to U.S. NRA withholding merely because the customer is a U.S. person.
3. It is normally not reported on Form 1042-S as U.S.-source income.
4. The client may request Form W-8BEN to document foreign status. Give the form to the requesting payer; do not send it to the IRS as an annual return.
5. If the payment is effectively connected with a U.S. trade or business, the W-8BEN shortcut may be wrong; analyze Form W-8ECI and Form 1040-NR.

Do not tell a U.S. client that no form is needed without checking its onboarding rules. The documentation form and the income-tax filing are separate questions.

### Non-U.S. client while working outside the U.S.

For services performed outside the United States for a non-U.S. client:

1. The income is generally foreign-source for U.S. tax purposes.
2. It is not converted into U.S.-source income just because the owner has a New Mexico LLC, EIN, Wise account, or U.S. registered agent.
3. The income can still be business income attributable to the owner under the LLC's federal classification.
4. The owner must report it in the country where the owner is tax resident under that country's rules.
5. The LLC must still include the receipt in its books and screen whether any owner/related-party or other filing obligation exists.

### Services physically performed in the U.S.

If the founder performs services while physically present in the United States, record:

- entry and exit dates;
- work dates and work location;
- client and contract;
- service description;
- amount attributable to U.S.-performed work;
- visa/immigration status where relevant;
- U.S. office, agent, employee, or fixed-place facts;
- tax withheld and forms received.

U.S.-performed personal services can create U.S.-source income and may be effectively connected with a U.S. trade or business. Screen Form 1040-NR, Form W-8ECI, withholding, estimated tax, treaty, and permanent-establishment issues. Do not use a W-8BEN solely because the founder remains a foreign citizen.

### Foreign founder and U.S. LLC separation

For a foreign-owned U.S. disregarded LLC:

- ordinary income-tax activity is generally attributed to the owner under U.S. rules;
- the LLC's Form 5472 analysis is separate from the owner's service-income source analysis;
- receiving money from a U.S. client does not itself create a Form 5472 transaction;
- an owner contribution, distribution, reimbursement, loan, owner-paid expense, service, or IP transfer can create a Form 5472 question;
- the client country does not determine whether a related-party transaction exists;
- if the LLC made a corporate election, stop using the disregarded-entity shortcut and analyze the corporation's Form 1120 path.

### Indonesian founder or Indonesian tax resident

Indonesian citizenship and Indonesian tax residence are not identical. First determine whether the owner is an Indonesian resident taxpayer under current Indonesian rules and any applicable treaty. If the owner is a Wajib Pajak Dalam Negeri, the owner generally reports worldwide income in the current Indonesian annual tax return process, including income from U.S. clients and non-U.S. clients.

For an Indonesian resident owner:

1. Report the relevant income from both U.S. and non-U.S. clients under the applicable Indonesian income classification.
2. Keep contracts, invoices, platform statements, bank/Wise records, expense evidence, exchange rates, and tax-withholding certificates.
3. Separate gross receipts, deductible business costs, platform fees, refunds, and owner distributions according to Indonesian rules.
4. Track foreign tax actually paid or withheld by country and income type.
5. Analyze PPh Pasal 24/Kredit Pajak Luar Negeri only for tax paid or accrued abroad that is creditable under current Indonesian rules and within the applicable limitation. Do not claim a credit just because a client is American.
6. If services were performed in Indonesia for a U.S. client and no U.S. tax was withheld because the income was foreign-source for U.S. purposes, there may be no U.S. foreign-tax credit to claim in Indonesia; the income can still be reportable in Indonesia.
7. If the owner is not an Indonesian resident taxpayer, do not apply the worldwide-income conclusion automatically; determine the applicable Indonesian nonresident rules.

The U.S. LLC's books and the owner's Indonesian annual return are different reporting layers. Do not assume that money left in the LLC, money paid to the owner, or money received in a personal bank account automatically has the same treatment in both countries.

### Client-income records required

Add these columns to the private ledger:

`client_name, client_country, payer_legal_entity, contract_type, income_character, service_country, service_date_start, service_date_end, days_in_US, work_location_evidence, invoice_currency, payment_currency, gross_amount, fees, refunds, withholding_country, withholding_form, foreign_tax_paid, U.S._source_screen, Indonesia_reporting_screen, evidence_path`

For every client, retain:

- signed contract or terms;
- invoice and credit notes;
- service description;
- where the work was physically performed;
- travel/day log;
- payer legal entity and country;
- payment statement and bank/Wise receipt;
- taxes withheld and tax certificates;
- exchange-rate source;
- related-party relationship, if any.

Never classify “U.S. client” as “U.S.-source” without checking service location and income character.


## Apple, Google Play, Stripe, and payment-platform workflow

Treat each platform as a separate source and counterparty. A payout is not automatically gross revenue, and a platform report is not automatically a Form 5472 related-party transaction. Classify the contractual payee, payer, platform legal entity, transaction type, and owner relationship before choosing a tax treatment.

### Common platform controls

For Apple App Store, Google Play Android, Stripe, Wise, marketplaces, and similar payers:

1. Save the exact tax-form request, account legal-name configuration, developer/merchant profile, and contract or agreement.
2. Identify whether the account is individual or organization and which entity/person is the payee.
3. Download gross sales, proceeds, payment, fee, refund, tax, withholding, chargeback, dispute, and payout reports.
4. Reconcile gross customer activity to platform net proceeds and Wise/bank deposits. Keep gross revenue, platform fees, taxes, refunds, and net cash separate.
5. Identify the platform's contracting/legal entity and country for each report or payment stream.
6. Determine whether the payer is requesting W-9, W-8BEN, W-8BEN-E, W-8ECI, Form 1099, or another form.
7. Never select a U.S.-person certification only to make the portal accept the account.
8. If the platform flow does not match the IRS documentation, prepare a concise support request explaining the facts without sending unnecessary identifiers.
9. Keep the submitted form, platform report, platform response, and payout proof in the private records package.

### Apple App Store

Collect App Store Connect sales, proceeds, payments, financial, tax, agreement, fee, refund, and withholding records. Match the Apple contracting entity and payment month to each payout. Do not assume that the Apple account name, seller name, or U.S. account setting determines federal tax classification.

### Google Play Android

Collect Google Play Console earnings, estimated sales, transactions, payouts, refunds, chargebacks, taxes, service fees, withholding, payment profile, developer account, and tax-form records. Save the Google contracting entity/legal-entity details shown in the relevant report. Reconcile Google Play gross activity to the Google payout statement and then to the Wise/bank deposit.

Do not treat a Google Play payout as the gross amount. Do not assume every Google entity is the same counterparty. Use the report period and payout currency, document the exchange-rate method, and screen whether any Google tax form or information return was issued.

### Stripe

Collect Stripe balance transactions, charges, payment intents where relevant, payouts, fees, refunds, disputes, chargebacks, tax reports, connected-account records, payment-method reports, and any Form 1099 or tax document. Reconcile:

```text
gross customer charges
  − refunds and disputes
  − Stripe processing/application fees
  ± adjustments
  = Stripe balance movement
  → payout to Wise/bank
```

Do not record only the net Stripe payout as revenue. Keep Stripe fees and refunds separately supported. Determine whether Stripe is the payment processor, merchant of record, marketplace, or another intermediary for the relevant product and country. Do not assume Stripe's tax-form request controls the LLC's federal classification.
If Stripe issues a Form 1099-K or another information return, preserve it and reconcile it to gross payment activity, refunds, fees, disputes, and payouts. Do not treat the form as a substitute for the ledger or automatically treat the reported gross amount as net taxable income.

## New Mexico workflow

Review the New Mexico Taxation and Revenue Department pages every filing year. Screen:

- business registration and New Mexico Business Tax Identification Number;
- gross receipts tax and location/source of receipts;
- compensating tax;
- wage withholding and unemployment obligations if workers exist;
- corporate income and franchise tax if corporate treatment applies;
- special tax programs, local rate, exemption, resale, and marketplace facts;
- Secretary of State maintenance separately from tax filings.

New Mexico registration, gross receipts, and federal income-tax classification are different questions. A filing checklist must keep them in separate sections.

## Records package and spreadsheet schema

Maintain a private folder with:

- `01-Facts-and-Classification/` — formation, operating agreement, resolutions, EIN notice, elections, prior returns;
- `02-Transactions/` — ledger and exchange-rate schedule;
- `03-Revenue/` — Apple, Google Play, Stripe, marketplace reports, payouts, and reconciliations;
- `04-Expenses/` — receipts, invoices, business purpose, reimbursements;
- `05-Owner-Related/` — contributions, distributions, loans, services, IP, personal payments;
- `06-Forms/` — unsigned drafts, signed submissions, confirmations;
- `07-State/` — New Mexico registration and returns;
- `08-Source-Log/` — official instructions and date checked.

Minimum ledger columns:

`date, account, counterparty, counterparty_country, relationship, description, business_purpose, transaction_type, currency, amount_original, exchange_rate, amount_usd, fee, paid_or_received, owner_related, possible_form, evidence_path, reconciliation_status, reviewer_note`

Use a source log with:

`source_url, form_or_topic, revision_or_page, date_checked, relevant_rule, fact_supported, next_review_date`

## Deadlines and submission controls

Never hard-code a deadline without checking the current instructions, tax year, tax-year end, weekends/holidays, and disaster relief notices.

For a calendar-year foreign-owned U.S. DE, the Form 5472/pro forma Form 1120 due date is generally tied to the Form 1120 due date, but the current instructions control. Form 7004 generally provides an automatic six-month filing extension for eligible returns; it does not erase payment obligations or cure an incorrect classification. The Form 5472 instructions require foreign-owned U.S. DEs to use the dedicated filing method and address.

Maintain a calendar containing:

- tax year start/end;
- original due date;
- extension due date;
- W-8 validity/change-of-circumstances date;
- New Mexico registration and filing periods;
- payroll/information-return dates if triggered;
- evidence collection date;
- user review date;
- submission date and proof location.

If a deadline has passed, do not invent a penalty amount, backdate a signature, or file a duplicate. First establish whether a return was filed, request or locate proof, identify the correct tax year/form, and evaluate penalty-relief or professional-review options.

## Low-cost operating model

Use official free sources first:

1. IRS current form page and instructions.
2. IRS entity-classification and international guidance.
3. New Mexico Taxation and Revenue Department pages and TAP.
4. Platform documentation and the exact support response.
5. A local spreadsheet with formula-visible calculations.
6. PDF copies and a submission log.

Spend money only for a narrow, high-value review when an escalation trigger appears. A targeted review of a prepared package is usually more efficient than paying someone to reconstruct disorganized records.

## Escalation triggers

Recommend targeted professional review before filing when any of the following is true:

- Form 8832 or 2553 election is being made, changed, or corrected;
- late Form 5472, pro forma Form 1120, or prior-year filing is suspected;
- U.S. trade/business, ECI, permanent establishment, or treaty position is uncertain;
- royalties, IP licensing, related-party services, transfer pricing, loans, or noncash transfers are material;
- the owner has multiple entities, partners, trusts, U.S. residence days, or changing tax residence;
- there is a worker-classification, payroll, sales-tax/gross-receipts, or state-nexus dispute;
- records are incomplete and the form would require large estimates;
- the IRS or New Mexico has issued a notice, penalty, audit request, or rejection;
- the owner cannot truthfully certify a form after reading its instructions.

The skill must still finish the reachable work: build the fact sheet, ledger, source map, draft questions, and evidence package before recommending review.
## AI tax-agent operating mode

When invoked as an AI tax agent, operate as a controlled preparation system rather than a guessing chatbot.

### Intake

Ask only for facts that change the filing path. Prefer reading the private source index and local records before asking the user to repeat information. Do not ask the user to paste an EIN, SSN, ITIN, bank number, or complete tax document into chat when the local file is available.

### Evidence handling

For every material field, record:

- proposed value;
- source file or official instruction;
- page/line or calculation;
- confidence status;
- unresolved conflict;
- form consequence.

If two documents conflict, show both values, explain the conflict, and stop the affected field at **Needs source**.

### Reasoning

Separate:

1. legal entity status;
2. federal tax classification;
3. withholding documentation;
4. information-reporting obligations;
5. income-tax return obligations;
6. New Mexico obligations;
7. owner-country obligations.

Never use one answer, such as “the LLC has an EIN,” to resolve all seven questions.

### Drafting

The agent may produce:

- field-by-field draft maps;
- unsigned form drafts when the user supplies the current blank form;
- transaction ledgers;
- exchange-rate schedules;
- reconciliation workbooks;
- source and evidence indexes;
- deadline calendars;
- questions for Apple, Google Play, Stripe, IRS, New Mexico TRD, or a targeted reviewer;
- submission checklists.

The agent must not:

- sign for the user;
- certify under penalty of perjury;
- submit or upload without explicit approval;
- conceal uncertainty;
- choose a treaty rate for convenience;
- turn a draft into a “filed” status without proof.

### Status transitions

Use this state machine:

```text
Evidence collection
  → Classification review
  → Transaction reconciliation
  → Draft form
  → Internal quality check
  → Ready for user review
  → User signs and approves
  → Submitted
  → Proof archived
```

Any missing critical evidence moves the case back to **Evidence collection**. Any conflicting classification evidence moves it to **Escalate for targeted review**.
## End-to-end filing mode

Use this mode when the user asks to be guided from documents through submission. The agent must not stop after explaining the form. It must move the case through each state, record what is complete, and identify the exact blocker when it cannot proceed.

### Stage 0 — Open the filing case

Create a case header containing:

- taxpayer/entity name, redacted in chat where practical;
- tax year and tax-year end;
- jurisdiction: federal, New Mexico, owner country, and payer/platform;
- filing objective;
- forms under review;
- source-folder path;
- current official form revision;
- internal due date and official deadline to re-check.

Do not start filling a PDF until the tax year and form revision are confirmed.

### Stage 1 — Build the filing decision

Deliver a one-page decision memo:

- **Confirmed:** supported by a source;
- **Conditional:** depends on an assumption;
- **Unknown:** record is missing;
- **Not applicable:** reason documented;
- **Escalate:** fact requires specialist review.

The memo must state why each candidate form is included or excluded. “No revenue” is not a classification decision and is not enough to exclude Form 5472.

### Stage 2 — Freeze the evidence set

Create an evidence index before entering numbers:

| Field/amount | Proposed value | Source file | Page/line | Calculation | Status |
|---|---|---|---|---|---|

Freeze the source set with a date. If a source is replaced, record the replacement and recalculate affected fields. Do not silently update a value after review.

### Stage 3 — Reconcile the ledger

Close the annual ledger before form entry:

- every Apple, Google Play, Stripe, Wise, bank, or other platform payout has a source report;
- gross proceeds, fees, refunds, taxes, and net deposits reconcile;
- owner contributions, distributions, loans, reimbursements, and paid-on-behalf expenses are separate;
- foreign-currency amounts have a documented exchange-rate method;
- each related-party transaction has a candidate Form 5472 part/line;
- differences have a written explanation or remain **Needs source**.

### Stage 4 — Prepare the field map

For every form line, record:

1. line number and label from the current form;
2. proposed entry;
3. source and page;
4. calculation or legal basis;
5. whether the line is required, conditional, or skipped;
6. unresolved question;
7. reviewer status.

The agent may populate non-signature fields in a draft PDF when the current blank form is supplied and the runtime supports PDF editing. It must not add or imitate a signature, certification, PIN, checkbox declaration, or date of signature.

### Stage 5 — Run quality control

Before asking the user to sign, perform four checks:

1. **Identity check:** name, address, entity status, tax ID placement, and tax year agree with evidence.
2. **Arithmetic check:** totals, subtotals, currency conversions, and attachments agree.
3. **Classification check:** the form matches the decision memo; no W-9 or treaty claim is used for convenience.
4. **Submission check:** current instructions, filing method, address/portal, deadline, signature requirements, and extension code are verified.

Generate a review list showing every changed field and every field left blank intentionally.

### Stage 6 — User review and authorization

The agent must present:

- completed draft or field map;
- unresolved issues;
- calculations;
- source index;
- submission method;
- deadline;
- consequences of certification;
- exact action requested from the user.

The case can move to **User authorized** only after the user explicitly confirms the draft and the intended submission. The user's approval to prepare a form is not automatically approval to submit it.

### Stage 7 — Signature and submission

Use the channel required by the current official instructions:

- **W-8BEN/W-8BEN-E/W-8ECI:** give to the requesting payer, platform, bank, or withholding agent; do not send it to the IRS as an annual income-tax return.
- **Form 5472 plus pro forma Form 1120 for a foreign-owned U.S. DE:** use the current dedicated IRS fax or mailing method; do not assume ordinary Form 1120 e-file or mailing instructions apply.
- **Form 7004:** use the method and correct return code in current instructions, before the original due date.
- **Full Form 1120 or Form 1040-NR:** use the current IRS e-file or paper method allowed for the specific taxpayer and tax year.
- **New Mexico returns:** use the current NM Taxation and Revenue Department portal or paper process and the filing frequency assigned to the account.
- **Apple, Google Play, Stripe, and other payment-platform forms:** follow the platform's current portal workflow and save the exact confirmation.

If browser automation or another submission tool is available, it may be used only after the user authorizes the specific action and sees the final document. The agent must pause before the irreversible submit button, final electronic certification, fax transmission, or mailing action unless the user has explicitly authorized that exact step.

### Stage 8 — Archive proof and close the case

Do not mark a filing “submitted” based on a screenshot of a completed draft. Archive:

- final signed copy;
- exact attachments;
- submission date/time and time zone;
- portal receipt, e-file acceptance, fax confirmation, certified-mail receipt, or platform case number;
- payment confirmation, if applicable;
- extension confirmation, if applicable;
- version of instructions used;
- next deadline and follow-up action.

Use these final states:

```text
Draft only
Ready for user review
User authorized
Signed — not submitted
Submitted — proof pending
Submitted — proof archived
Rejected or incomplete — correction required
Escalated for targeted review
```

### Failure handling

If the portal rejects a form, the fax fails, the mailing is returned, a payment fails, or the IRS/NM TRD issues a notice:

1. preserve the rejection or notice unchanged;
2. do not submit a second copy blindly;
3. identify the exact rejected field, attachment, or channel;
4. check the current official instructions;
5. update the field map and submission log;
6. recalculate affected amounts;
7. obtain user approval for the corrected submission;
8. escalate if the correction changes classification, tax, penalty, treaty, or filing position.

### End-to-end completion standard

The skill is complete for a filing only when it has produced a decision memo, evidence index, reconciled ledger, field map, draft, quality-control result, user-review record, submission plan, and proof archive—or has clearly documented the precise missing prerequisite. It must never claim “done” while only a blank or partially filled form exists.



## Required response format

For every user case, return:

1. **Scope:** tax year, jurisdiction, entity, and forms being analyzed.
2. **Confirmed facts:** each with a source.
3. **Conditional facts:** what is assumed and why.
4. **Decision tree result:** path selected and paths rejected.
5. **Form matrix:** may apply / appears not applicable / unknown.
6. **Field map:** line-by-line values, evidence, and unresolved questions.
7. **Calculations:** formulas, exchange rates, and reconciliation checks.
8. **Missing records:** exact files or answers needed.
9. **Submission plan:** method, address/portal, signature, proof, and deadline to re-check.
10. **Risk gate:** green, amber, or red; explain the trigger.
11. **Official sources:** URL, revision/page, and date checked.
12. **Final instruction:** either **Ready for user review**, **Do not submit yet**, or **Escalate for targeted review**.

## Official sources

Prefer current primary sources and record the revision/date checked:

- IRS single-member LLC: https://www.irs.gov/businesses/small-businesses-self-employed/single-member-limited-liability-companies
- IRS Form 8832: https://www.irs.gov/forms-pubs/about-form-8832
- IRS Form W-9: https://www.irs.gov/forms-pubs/about-form-w-9
- IRS Form W-8BEN: https://www.irs.gov/forms-pubs/about-form-w-8-ben
- IRS Form W-8BEN-E: https://www.irs.gov/forms-pubs/about-form-w-8-ben-e
- IRS Form W-8ECI: https://www.irs.gov/forms-pubs/about-form-w-8-eci
- IRS Form 5472 instructions: https://www.irs.gov/instructions/i5472
- IRS Form 1120: https://www.irs.gov/forms-pubs/about-form-1120
- IRS Form 7004: https://www.irs.gov/forms-pubs/about-form-7004
- IRS Form 1040-NR: https://www.irs.gov/forms-pubs/about-form-1040-nr
- IRS Publication 515: https://www.irs.gov/forms-pubs/about-publication-515
- IRS international taxpayers: https://www.irs.gov/individuals/international-taxpayers
- IRS nonresident aliens — sourcing of income: https://www.irs.gov/individuals/international-taxpayers/nonresident-aliens-sourcing-of-income
- IRS foreign-source income and Form 1042-S: https://www.irs.gov/individuals/international-taxpayers/foreign-source-income-form-1042-s-reporting-not-required
- IRS nonresident aliens — exclusions from income: https://www.irs.gov/individuals/international-taxpayers/nonresident-aliens-exclusions-from-income
- IRS Publication 519: https://www.irs.gov/forms-pubs/about-publication-519
- Indonesia Ministry of Finance — foreign tax credit / Kredit Pajak Luar Negeri: https://pajak.go.id/sites/default/files/02KMK03_164.htm
- Google Play Console help and tax information: https://support.google.com/googleplay/android-developer/
- Stripe reports and tax documentation: https://docs.stripe.com/reports
- New Mexico business taxes: https://www.tax.newmexico.gov/businesses/
- New Mexico business registration: https://www.tax.newmexico.gov/businesses/who-must-register-a-business/
- New Mexico Secretary of State: https://www.sos.nm.gov/business-services/

When an official source conflicts with a previous answer, correct the answer explicitly and preserve the source-based reasoning.
