# Mentarich LLC tax filing skill

An OMP/GitHub Agent Skill for organizing IRS and New Mexico tax-preparation records for a foreign-owned New Mexico single-member LLC.

## What it does

- separates state-law LLC status from federal tax classification;
- checks the default disregarded-entity path versus a Form 8832 corporate election;
- organizes evidence for Form 5472 and pro forma Form 1120 review;
- handles Apple W-8/W-9 questions without guessing or signing forms;
- builds transaction, Apple, banking, and expense checklists;
- keeps confidential tax and banking information out of public repositories.

## Installation

### GitHub Agent Skills

Copy `.github/skills/mentari-llc-tax-filing/` into a project repository. The skill is discovered from the standard `.github/skills/<name>/SKILL.md` location.

### OMP user skill

Copy the same skill directory into the user's configured OMP/Agent Skills directory. Keep private company records outside the repository.

## Use

Invoke the skill when asking for tasks such as:

- “Review my Mentarich LLC filing path.”
- “Build the Form 5472 preparation checklist.”
- “Organize my Apple and Wise records for IRS filing.”
- “Review whether this W-8/W-9 workflow is consistent with the facts.”

The skill organizes information. It does not sign or submit tax forms and does not replace professional tax advice.

## Privacy

Do not commit:

- EIN, SSN, ITIN, Indonesian TIN, full residential address, bank account numbers;
- tax returns or tax notices containing identifiers;
- bank statements, Apple payment details, API keys, passwords, or card images;
- private Apple case attachments.

Use redacted examples and local encrypted storage for actual records.

## License

MIT
