# Joint Pursuit Framework (JPF)

**Version 0.2 — public working draft**

JPF is a lightweight, vendor-neutral way for independent companies—and the AI assistants working for them—to pursue an RFP together without losing track of **who owns each claim, who approved it, and who must deliver what was promised**.

It is intentionally usable with ordinary documents and spreadsheets. You do not need agent-to-agent infrastructure, a shared knowledge base, or a particular proposal platform.

> Combine the proposal, not the participants' identities, evidence, authority, or accountability.

## The problem

Joint proposals often move faster than their governance. A creative firm, engineering partner, specialist consultant, reseller, or subcontractor may each contribute useful material, but the final response can quietly blur important distinctions:

- One company's experience is written as if the whole team delivered it together.
- Product documentation is presented as proof of an implemented solution.
- An idea becomes a commitment before the delivery owner approves it.
- “Shared” responsibility leaves nobody accountable after award.
- Sensitive source material spreads into another company's systems without clear limits.
- Pricing, support, change control, and delivery assumptions are resolved late.
- AI makes all of this happen faster and more fluently.

JPF adds just enough structure to expose those problems before submission.

## The five-minute explanation

JPF uses:

1. **A pursuit charter** that defines the participants, authority, commercial structure, and data-use boundaries.
2. **One authoritative register** that connects every important requirement to its response, evidence, claim owner, delivery owner, status, and approval.
3. **Three approval gates**—before drafting, before committing, and before submission/closeout.

AI can help extract requirements, compare sources, find contradictions, draft qualified language, and identify gaps. Humans still approve disclosure, compliance claims, staffing, pricing, contracts, delivery commitments, and the final response.

## What changed in 0.2

Version 0.1 described a broad agent-exchange framework. A real joint RFP pilot showed that the immediate value came from disciplined proposal governance using ordinary documents—not from implementing a new interoperability protocol.

Version 0.2 therefore:

- Renames the concept from **Joint Sales Framework** to **Joint Pursuit Framework**.
- Reduces the process to three required gates.
- Makes one authoritative register the center of the workflow.
- Moves the charter and commercial decisions to the beginning.
- Gives every promised outcome one accountable delivery owner.
- Separates evidence classes and approval states more precisely.
- Adds submission freeze, closeout, and proposal-to-delivery transition.
- Treats structured partner requests as an exception for unresolved items, not overhead for every exchange.

## Quick start

### 1. Copy the templates

Create a private workspace for the opportunity and copy:

- [`templates/01-pursuit-charter.md`](templates/01-pursuit-charter.md)
- [`templates/02-authoritative-register.md`](templates/02-authoritative-register.md)
- [`templates/03-partner-request.md`](templates/03-partner-request.md), when needed
- [`templates/04-submission-and-closeout.md`](templates/04-submission-and-closeout.md)

Do not put confidential pursuit data in a public fork of this repository.

### 2. Pass Gate 1: charter and data use

Before the team writes persuasive proposal language, agree on:

- Prime contractor or client lead
- Bid manager and official communication path
- Areas each participant may lead, contribute to, review, or not represent
- Pricing and contract authority
- What information may be shared, with whom, for what purpose, and for how long
- What happens if a participant withdraws

Open questions can remain open, but they must be visible and owned.

### 3. Build the authoritative register

Add one row for every material requirement, differentiator, exception, and contractual commitment. At minimum record:

- Exact source and requirement
- Draft response
- Claim owner and supporting evidence
- Accountable delivery owner
- Estimate or commercial dependency
- Approval state
- Risks, assumptions, and unresolved questions

Email, chat, meeting notes, and AI output may feed the register. They do not override it silently.

### 4. Pass Gate 2: requirements and ownership

Before an answer becomes approved proposal language, ask:

- Who actually has this capability?
- What kind of evidence supports it?
- Is the wording about one company, one person, coordinated delivery, or proven joint delivery?
- Who is accountable if the buyer accepts the promise?
- Has that owner approved the scope, assumptions, estimate, and wording?

If the answer is unclear, mark the item unresolved. Do not let polished prose conceal the gap.

### 5. Draft and reconcile

Draft from the register, not from memory. Use AI to find contradictions and missing evidence, but have domain and commercial owners approve the resulting commitments.

When another participant must answer a question, use a bounded [partner request](templates/03-partner-request.md) tied to a register item. Ask for the minimum necessary information and record the returned answer's owner, limitations, and approval state.

### 6. Pass Gate 3: freeze and close out

Before submission:

- Reconcile every mandatory requirement.
- Confirm one accountable delivery owner for every promised outcome.
- Confirm that evidence is permitted for buyer use.
- Resolve or visibly qualify conflicting estimates and assumptions.
- Obtain final approvals.
- Freeze and identify the exact submitted files.

After the decision, either convert the commitments into the delivery plan or apply the agreed retention and deletion rules.

## A useful claim test

Distinguish these four statements:

1. **Member capability:** A named company can perform the work.
2. **Personnel experience:** A named person has relevant experience, possibly from another employer.
3. **Coordinated capability:** Participants have defined complementary roles for this pursuit.
4. **Proven joint delivery:** These same participants have delivered comparable work together.

Do not rewrite the first three as the fourth.

## Evidence is not one thing

JPF 0.2 separates:

- **Product documentation** — says a product is designed to do something.
- **Demonstration evidence** — shows a behavior in a bounded test or demo.
- **Planned configuration** — describes work expected to enable a capability.
- **Custom development** — describes work that must be designed, built, and tested.
- **Proven implementation** — shows comparable delivery in a real environment.

The proposal wording should not imply a stronger evidence class than the record supports.

## Using JPF as an AI skill

This repository is also a portable agent skill. Place the repository folder where your agent discovers skills, then invoke:

```text
Use $joint-pursuit-framework to set up a governed workspace for this RFP.
```

The skill does not grant the agent authority to disclose information, contact partners, submit a proposal, or make commitments. Those actions remain subject to the users' normal permissions and the JPF approval gates.

## Repository map

```text
joint-pursuit-framework/
├── README.md
├── SKILL.md
├── QUICKBYTE.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── jpf-feedback.md
├── agents/
│   └── openai.yaml
├── examples/
│   └── fictional-pursuit.md
├── references/
│   └── framework.md
└── templates/
    ├── 01-pursuit-charter.md
    ├── 02-authoritative-register.md
    ├── 03-partner-request.md
    └── 04-submission-and-closeout.md
```

## Current status and feedback sought

JPF 0.2 is an experimental public working draft, not a standard or certification program. It has been informed by one real joint RFP pilot; broader usefulness remains to be tested.

The most useful feedback is concrete:

- Which field or gate prevented a real mistake?
- Which part created overhead without changing a decision?
- What was still ambiguous after using the templates?
- Did the register transfer cleanly into delivery after award?
- What would make this usable by smaller teams under a short deadline?

Open an issue or discussion with the opportunity anonymized. Do not post buyer-confidential, partner-confidential, personal, pricing, or source material without permission.

## Scope and disclaimer

JPF governs joint pursuit information and decisions. It does not replace a teaming agreement, NDA, subcontract, security review, legal review, procurement rules, or professional judgment.

JPF 0.2 is released under the [MIT License](LICENSE).
