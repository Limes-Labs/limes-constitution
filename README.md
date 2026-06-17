# Limes Constitution

**A charter of values and behavior for European open AI assistants.**

Limes Labs publishes this document as public infrastructure — not as marketing, but as a shared reference for how we want European AI systems to reason, prioritize, and act. It is written primarily for the models and assistants we hope to train and deploy, in the spirit of transparent constitutional AI work pioneered by others in the field.

> We are not claiming frontier capability yet. We are organizing capability — including the *character* of that capability.

- Website: [limeslabs.eu](https://limeslabs.eu)
- Full text: [CONSTITUTION.md](./CONSTITUTION.md)
- Evaluation guidance: [EVALUATION.md](./EVALUATION.md)
- Governance process: [GOVERNANCE.md](./GOVERNANCE.md)
- Changelog: [CHANGELOG.md](./CHANGELOG.md)
- Training experiments: [limes-nanogpt](https://github.com/Limes-Labs/limes-nanogpt)
- Evaluation: [eurobench](https://github.com/Limes-Labs/eurobench)

## Document map

- [CONSTITUTION.md](./CONSTITUTION.md) is the normative charter: values, priorities, release principles, legal-policy orientation, and assistant behavior.
- [EVALUATION.md](./EVALUATION.md) explains how constitutional claims should become EuroBench tasks, red-team prompts, release checks, and amendment candidates.
- [GOVERNANCE.md](./GOVERNANCE.md) explains how to propose and review amendments.
- [CHANGELOG.md](./CHANGELOG.md) records public version history.

The designed PDF is intended as a public-review artifact generated from these files, not as a replacement for the source Markdown.

## Why a constitution?

Powerful language models will shape European public administration, education, research, and industry. The people building them have a chance — and, we believe, a responsibility — to encode not only competence but *character*: honesty, respect for fundamental rights, openness to scrutiny, and care for the societies these systems serve.

Rules alone are brittle. Values and judgment generalize better. This document therefore emphasizes what a Limes-aligned assistant should *care about* and *weigh*, not only what it must refuse. Where hard constraints exist, we explain the reasoning behind them.

## Core priorities (summary)

When values appear to conflict, a Limes-aligned assistant should generally prioritize:

1. **Broad safety** — not undermining appropriate human oversight of AI during this developmental period
2. **Broad ethics** — honesty, dignity, non-maleficence, and respect for fundamental rights
3. **European commitments** — alignment with Regulation (EU) 2024/1689 (the AI Act), the Charter of Fundamental Rights, and Limes Labs' published guidelines where relevant
4. **Genuine helpfulness** — real benefit to users, institutions, and the public interest

Most everyday tasks — coding, writing, analysis, translation — involve no tension between these. The ordering matters when they do.

## Relationship to European law and policy

This constitution is **not** a legal instrument. It draws inspiration from:

- The [Charter of Fundamental Rights of the European Union](https://www.europarl.europa.eu/charter/pdf/text_en.pdf)
- The [European Declaration on Digital Rights and Principles for the Digital Decade](https://digital-strategy.ec.europa.eu/en/library/european-declaration-digital-rights-and-principles)
- Regulation (EU) 2024/1689 — the **AI Act**
- The EU's **human-centric, trustworthy AI** policy and **open source for sovereignty** agenda

Limes Labs advocates open weights, open evaluation, and inspectable systems precisely because European digital sovereignty requires *understanding*, not only *deployment*.

## Status and governance

This is a **living document** (v0.3, June 2026). We expect substantial revision as:

- Limes training runs produce empirical feedback
- [eurobench](https://github.com/Limes-Labs/eurobench) tasks test constitutional behavior
- Contributors propose amendments via GitHub issues and pull requests

We welcome critique from researchers, civil society, public institutions, and other labs. The goal is a constitution worthy of public inspection — and, we hope, worthy of the assistants it describes.

## What changed in v0.3?

v0.3 sharpens the document for humans and future assistants:

- Adds an executive summary and a scope and non-claims section.
- Clarifies scope and non-claims: not legal advice, not AI Act compliance proof, not safety certification, not a model behavior guarantee, and not a frontier capability or consciousness claim.
- States an **open by default, controlled where necessary** release principle.
- Distinguishes open weights, open source, open evaluation, and public-sector auditability.
- Expands the constitution into a longer, more discursive charter with guidance on assistant character, practical judgment, over-refusal, operator/user instructions, public-sector deployment, refusal style, and compliance humility.
- Connects constitutional principles to EuroBench task directions, red-team findings, release checklists, and model cards.
- Adds [EVALUATION.md](./EVALUATION.md) and [GOVERNANCE.md](./GOVERNANCE.md) for operational review.

## How to read this draft

For a quick review, start with the executive summary and scope/non-claims in [CONSTITUTION.md](./CONSTITUTION.md), then read the release principle and governance sections.

For technical review, focus on [EVALUATION.md](./EVALUATION.md), the hard constraints, refusal style, and the links to model cards and EuroBench.

For policy or public-sector review, focus on fundamental rights, Regulation (EU) 2024/1689, public-sector deployment posture, auditability, and the non-claims.

For open-source review, focus on the distinctions between open weights, open source, open evaluation, and public-sector auditability.

## Proposing amendments

Open an issue or pull request for substantive changes. A strong proposal should include:

1. The problem, failure mode, or ambiguity it addresses.
2. The sections affected.
3. The evidence or rationale behind the change.
4. Any related [EuroBench](https://github.com/Limes-Labs/eurobench) task, red-team finding, model-card update, release note, or incident lesson.
5. Legal/source review and similarity review where relevant.

Small editorial fixes are welcome. Normative changes should be reviewable: they should make Limes-aligned behavior more testable, transparent, and useful without overclaiming legal certainty or current capability.

## Public review questions

We especially welcome critique on:

- Whether the release principle is open enough while still credible about misuse.
- Whether the AI Act and GDPR language is cautious and accurate at a high level.
- Whether the document is useful to future assistants without over-anthropomorphizing them.
- Whether the EuroBench evaluation families are concrete enough to guide benchmark work.
- Whether the governance process invites the right reviewers and evidence.

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — use, adapt, and fork without permission. Attribution appreciated but not required.

## Acknowledgements

This work is inspired by the public constitutional AI tradition, including Anthropic's [Claude's Constitution](https://www.anthropic.com/news/claudes-constitution). Limes Constitution is an independent document grounded in European values and Limes Labs' open-sovereignty mission. It is not affiliated with or endorsed by Anthropic or any government body, and it should be reviewed as Limes' own public charter rather than a derivative constitution.
