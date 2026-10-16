# Business Discovery Interviewer

**Understand the business before recommending solutions.**

A reusable Manus skill for consultants conducting client discovery. It asks one question at a time, adapts to the industry and interviewee, investigates actual workflows, and separates statements from reviewed evidence.

[View the project on Manus Academy](https://academy.manus.im/projects/01a14616-5789-7288-8826-b7bf15c440f4).

## Install

Download [`business-discovery-interviewer.skill`](dist/business-discovery-interviewer.skill) and add it to your Manus skills. The package includes the method, references, and templates.

Alternatively, download this repository and use its [`SKILL.md`](SKILL.md) with the bundled `references/` and `templates/` directories. Do not copy the entry point alone: it depends on those files.

## Start

> Activate Business Discovery Interviewer for a distribution company. I have 30 minutes with operations and want to understand delivery delays.

Provide the client's activity, objective, interviewee's role, and available time. Optionally complete the [client profile](templates/client-profile.md). Answer each question with the interviewee's response. Say **“End interview”** to produce the discovery record.

The instructions are in English. Interviews can follow the user's preferred language.

## What it covers

Ten dimensions: business model and environment; customers and beneficiaries; demand and sales/access; product and quality; operations and delivery; economics and cash; people and knowledge; information and systems; risks and controls; leadership and change.

Use the map selectively. A short meeting does not cover everything.

| Mode | Purpose |
|---|---|
| Consultant-guided | Support a live client meeting |
| Direct | Interview the person answering |
| Preparation | Build a prioritized interview guide |
| Notes/transcript | Structure existing information and gaps |
| Cross-checking | Reconcile accounts from previous interviews |

## Output

A factual Markdown discovery record containing the business model, actual case workflow, coverage, source-attributed findings, strengths, concerns, unresolved discrepancies, separate hypotheses, and a resume point.

Evidence labels: **[D]** declared statement; **[E]** reviewed evidence; **[H]** hypothesis; **[P]** pending. Repeating a statement does not make it verified evidence.

## Customize

Keep the generic method separate from the client profile. Adapt terminology, scope, roles, and time without copying confidential context from other clients. Investigate a process or function using the [deep-dive guide](references/deep-dive.md).

## Validation and limitations

The skill metadata, file completeness, internal links, ten dimensions, and presence of ten synthetic acceptance cases were checked. The cases specify expected behavior; they are not real interviews or measured effectiveness.

This is a discovery aid, not an audit, certification, financial opinion, or automatic recommendation engine. No guaranteed outcomes or savings. External integrations and paid APIs are not required. Protect client information and obtain appropriate authorization before recording or sharing.

## Files

- [`SKILL.md`](SKILL.md): core method.
- [`references/`](references/): business map, deep dive, customization, acceptance cases.
- [`templates/`](templates/): client profile and discovery record.
- [`dist/`](dist/): installable skill package.
- [`assets/`](assets/): original initials mark, thumbnail, and favicons.
