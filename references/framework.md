# JPF 0.2 Reference

Read this reference when the basic README and templates do not provide enough detail for a complex or higher-risk pursuit.

## Core principles

### Sovereignty and minimum necessary disclosure

Each participant controls its source material, systems, and approvals. Joining a pursuit does not grant another participant general access. Prefer bounded questions, approved summaries, or query-only access over bulk source transfer.

### Purpose limitation

Information approved for one opportunity is not automatically approved for another proposal, marketing, model training, or general business development. Record the purpose, audience, allowed transformations, retention period, and buyer-submission permission.

### Attribution and provenance

Material claims, evidence, estimates, and commitments retain their organization, human owner, source, date, limitations, and approval state. A final editor may create one narrative but must not erase these distinctions.

### Proposal ownership maps to delivery ownership

For every promised outcome, identify the accountable delivery owner, responsible contributors, acceptance criteria, dependencies, estimate owner, and proposal-language approver. Decompose “shared” responsibility until one party is accountable.

### Reversibility and auditability

Access should expire or be revocable. Decisions and approvals should be reconstructable. Freeze the submitted package rather than treating a mutable working document as submission history.

## Roles

- **Opportunity sponsor:** owns bid/no-bid and major commercial escalation.
- **Prime or client lead:** owns the buyer relationship and contractual interface.
- **Bid manager:** maintains schedule, register, working draft, and gates.
- **Domain owner:** approves representations and commitments in a discipline.
- **Information owner:** approves disclosure and reuse of source material.
- **Commercial approver:** approves price, margin, assumptions, and contract risk.
- **Delivery owner:** is accountable after award for a work package or outcome.
- **Agent operator:** supervises AI access and use; this role does not confer business approval authority.

## Claim classes

1. **Member capability** — a specific organization can perform the work.
2. **Personnel experience** — a named person has relevant experience, possibly from another employer.
3. **Coordinated capability** — participants have agreed complementary roles and interfaces.
4. **Proven joint delivery** — the same participants have delivered comparable work together.

Never infer class 4 from classes 1–3.

## Evidence classes

1. **Product documentation** describes intended product capability.
2. **Demonstration evidence** shows bounded observed behavior.
3. **Planned configuration** describes work expected to enable a capability.
4. **Custom development** requires design, implementation, and testing.
5. **Proven implementation** documents comparable real delivery.

Record freshness, comparability, confidentiality, and permitted use separately from evidence class.

## Permission envelope

For sensitive or cross-company information, record:

- Owner and authoritative contact
- Opportunity and permitted purpose
- Intended recipients or roles
- Allowed transformations: quote, summarize, paraphrase, or validate only
- Whether storage is allowed and for how long
- Whether buyer submission is allowed or requires another approval
- Whether external models or services may process the information
- Revocation or deletion instructions
- Required attribution

## Approval states

- Draft
- Needs evidence
- Needs owner
- Needs approval
- Approved with conditions
- Approved
- Excluded
- Superseded

Do not use a binary approved/unapproved field when conditional approval changes the proposal language.

## Three gates

### Gate 1 — charter and data use

Confirm opportunity identity, current solicitation version, prime structure, communication authority, participant boundaries, commercial decision rights, information rules, withdrawal path, and register location.

### Gate 2 — requirements and delivery ownership

Confirm traceability, evidence class, claim owner, one accountable delivery owner per outcome, estimates, dependencies, commercial assumptions, and required domain approvals.

### Gate 3 — submission freeze and closeout

Reconcile requirements and commitments, confirm disclosure permission, obtain organization-level approvals, freeze the submission package, record buyer communications, and transition or close the pursuit.

## AI validation questions

Before recommending or inserting material language, an AI assistant should be able to answer:

- What exact requirement does this address?
- Which organization owns the claim?
- What evidence class and source support it?
- Is the evidence current, comparable, and permitted for this use?
- Is this member capability, personnel experience, coordinated capability, or proven joint delivery?
- Who is accountable for performing the promise?
- Has that owner approved the scope, assumptions, estimate, and wording?
- Does the statement conflict with another requirement, source, decision, or estimate?
- Are limitations buyer-visible where needed?

When an answer is missing, flag the item. Do not fill the gap with plausible language.

## Source reliability

Treat executed agreements, official solicitation documents, approved registers, and named approvals as authoritative according to their role. Treat meeting notes, transcripts, AI summaries, recollections, and unapproved inventories as sources to reconcile. They may reveal an issue; they do not prove approval by themselves.

## Conformance to the spirit of JPF 0.2

A pursuit follows JPF when:

- Participants retain control of their source material.
- Material claims remain attributable and supportable.
- The proposal does not imply combined competence the participants cannot execute.
- Participants know who may communicate, recommend, approve, price, and deliver each part.
- Every promised outcome has one accountable delivery owner.
- Sensitive information has explicit purpose and use boundaries.
- AI accelerates analysis and drafting without making unapproved commitments.
- The exact submission and its approvals can be reconstructed.
- A winning proposal can transition into delivery without rediscovering who promised what.
