---
title: Collegius Standard - SKILL.md
type: standards-skill
version: 0.1.0
date: 2026-04-19
status: Active skill. Invokable when helping contributors form or evaluate a Collegius, or when helping a funder understand what committing to a Collegius means. Operates in two modes: practitioner and funder. Downstream from the Coordination Structural Integrity Suite; not a CSIS standards skill.
---

# Collegius Standard - SKILL.md

Invoke this skill when working with any party whose question touches the Collegius Standard — whether they are forming a Collegius, evaluating an existing one, or considering committing to one as a funder. The skill operates in two distinct modes depending on who is asking. Identify the mode before proceeding.

**Practitioner mode:** the user is a contributor or group forming, joining, or evaluating a Collegius. Questions center on requirements, conformance, and what the structure produces internally.

**Funder mode:** the user is a funder or allocator considering whether to commit to a Collegius, or trying to understand what they are reading when they look at one. Questions center on what the mechanism guarantees, what they can verify, and what they gain.

Both modes may be active in the same conversation when both audiences are present. Name which mode you are in when you shift.

---

## Key Constructs

These terms carry precise meanings in this standard. Do not substitute informal equivalents.

**Collegius** (plural: Collegii): the structural unit this standard specifies. A self-curating contributor body with an onchain distribution mechanism and a thin funder interface. An organizational type does not define a Collegius; the structural configuration does.

**Collegenii**: the members of a Collegius. The plural of Collegenius.

**Distribution invariant**: the unconditional routing rule that determines how incoming value distributes to active registry members. Set before any funder commits. Does not change based on who is funding or how much. Not a policy — it runs.

**Legible structural state**: the onchain record of a Collegius's registry at any moment AND across time. "State" is precise here: a timeline, not a snapshot. Every membership change, weight adjustment, and distribution event is timestamped, immutable, and readable by anyone without asking the Collegius for anything. This is what funders read; they do not receive reports.

**Stewardship record**: the internal coordination record maintained by and for the Collegenii. Contains the formation statement, coordination structure, update history, and former member record. Public, but its primary audience is the members.

**Registry**: the self-curated list of who is currently active in the Collegius's field of work, at what weight, according to the membership criterion. Curated by contributors; no external party has standing to initiate a change.

**CSIS**: the Coordination Structural Integrity Suite. Seven Tensegrity Compressive Standards the Collegius Standard is downstream from. The Collegius is not part of the suite; it is built on top of it.

---

## Practitioner Mode

### What the standard requires

The standard specifies three constitutive structural elements. All three must be genuinely present and load-bearing for each other. A checklist approach will not produce a conformant Collegius.

**Self-curated registry.** Who curates it, at what weight, under what criterion, with what dilution incentive structurally present. The dilution incentive — adding members reduces existing shares — is the quality control mechanism. It must be structural, not assumed.

**Distribution invariant.** The unconditional routing rule, specified before any funder commits. It runs; it is not a governance decision that gets made each cycle.

**Thin funder interface.** Structural exclusion of funders from registry decisions, not conventional exclusion. A design that excludes funders by culture but not by mechanism does not satisfy this requirement.

### Formation requirements

Before any funder commits, a formation statement must exist documenting: the membership criterion, the founding member set with independently verifiable attestation for each founder, the distribution invariant specification, and the coordination structure. Bare attestation alone does not satisfy the formation requirement. Where onchain founding configuration tools are available, they are the preferred instrument.

Founding members must themselves satisfy the membership criterion. The criterion comes first; founders demonstrate they meet it.

### Evaluating the membership criterion

The test: can an independent observer evaluate any proposed member against the criterion without relying on social consensus from within the field? If not, the criterion does not satisfy the Precision-First Design Standard (CSIS). Vague criteria produce registry capture over time.

The criterion must also address: concurrent membership in other Collegii (permitted, restricted, or requiring disclosure); whether contributors who sustain the Collegius itself (documentation, communications, operational coordination) are eligible and on what terms. Silence on either point does not satisfy the requirement.

### CSIS conformance

The Collegius is downstream from all seven CSIS standards. The standard implements them as structural conditions, not reporting obligations. Run the following checks:

**Precision-First Design Standard:** membership criterion independently evaluable without social consensus from within the field.

**Adverse Signal Engagement Principle:** defined contested membership process documented before any contest arises, accessible to any member without requiring cooperation of the challenged party.

**Structural Consent Legibility Standard:** consent architecture covers registry entry, weight changes, and exit. Silence is not consent. Exit available without prohibitive cost.

**Information Asymmetry Classification Standard:** the legible structural state, weight basis publication, and contribution records reduce positional, interpretive, and complexity asymmetry. Conflict of interest disclosure reduces relational asymmetry. Note: omission asymmetry detection requires Sensemaking Standard infrastructure this standard does not mandate — this is a disclosed gap.

**Structural Power Obligation Standard:** funder exclusion from registry decisions structurally enforced. Keyholder selection, rotation, and conflict of interest terms documented. Keyholder concentration monitored over time.

**Regenerative Obligation Standard:** regenerative stance declared in a publicly accessible, versioned location. Distribution model demonstrably sustains contributors.

**Coordination Scaling Standard:** minimum conditions for all crossed Radius thresholds structurally present. Maximum conditions absent. Known gap: the Radius 15 mutual support condition is not specified by this standard — Collegii crossing that threshold should source that condition directly from the Coordination Scaling Standard.

### The coordination record

The coordination record has two purposes: internal coherence for members, and structural separation of coordination from distribution. Funders have no standing over what it contains. Check that both the stewardship record (formation statement, coordination structure, update history, former member record) and internal coordination (work organization, member contribution records, concurrent membership disclosure) are present and accessible.

### Known open questions that affect implementation

Two blocking open questions in Section 9 of the standard are unresolved. Surface these when helping a practitioner plan implementation:

**Onchain registry format:** no standardized smart contract interface exists for membership registries at this standard's specificity. The distribution mechanism has de facto standards (split contract protocols); the registry does not. Practitioners should treat this as an open design decision requiring resolution before broad adoption.

**Membership-to-distribution state automation:** the standard requires eliminating the human translation step between membership changes and distribution weight updates. No established implementation pattern exists. This is new territory the standard introduces.

---

## Funder Mode

### What the mechanism guarantees

One guarantee: value sent to the Collegius routes to whoever currently satisfies the registry criterion, according to the distribution invariant, without exception or redirection. This holds regardless of funder identity, contribution amount, or the political context of any given moment.

The guarantee is credible because no funder, including the largest, can alter what it produces. That is not a restriction on funders. It is the structural condition under which the guarantee holds. A funder who understands this is not accepting a limitation; they are accepting the only arrangement in which the guarantee is real.

### What funders cannot require — and why that is the right arrangement

Funders cannot control membership, direct distributions to specific contributors, veto registry changes, or require narrative reporting as a condition of the mechanism functioning. These exclusions are not restrictions on funders. They are what makes contributor sovereignty over the field real rather than nominal. Funder exclusion from registry decisions and contributor authority over the registry are the same structural move.

A funder who presses for any of these capacities is asking for an arrangement that would destroy the guarantee they came for. The guarantee depends on the exclusions.

### Reading the legible structural state

The legible structural state is what a funder reads instead of receiving a report. It is an onchain record — a timeline of every membership change, weight adjustment, and distribution event, timestamped and immutable. A funder can verify:

- Who is currently active, at what weight, under what criterion
- The full history of how membership has changed and when
- Every distribution event: value received, distributed, to whom, when
- Whether the Collegius is current on its update cadence

This verification requires no request to the Collegius and no trust in their account of themselves. The chain carries the credibility. A newly formed Collegius with no institutional history is as readable as one with years of operation — the history is just shorter.

### What funders gain by funding mode

**Expert committee and foundation programs:** evaluation overhead is reduced before the cycle begins. Reviewers read the legible structural state rather than eliciting evidence from applicants. The evaluation question is already answered.

**Community allocation programs (token voting, quadratic funding):** the mechanism's operating history is the legibility signal each cycle. The Collegius does not re-perform credibility each round. This is the mode where the structural form provides the largest advantage over individual projects.

**Network rewards routing:** a protocol can wire value to the distribution invariant and it runs. Multiple protocols can route to the same Collegius independently, without coordination overhead between them.

**Retroactive funding programs:** the registry has been running. Who was active, at what weight, over what period, with what distribution history — it is already there, onchain, without reconstruction.

**Streaming and continuous funding:** registry weights determine flow rates. The distribution invariant fits the stream architecture directly.

**Protocol treasury and DAO governance votes:** the coordinative surface is narrower. A governance body decides whether to commit to a field of work, not which individual applicants to prefer. The attack surface for political capture narrows with it.

**Milestone-gated grants:** the Collegius form does not apply. Milestone gates are the right instrument for project-shaped work with defined deliverables. A Collegius is persistent infrastructure for a field of work; it does not complete. These are different instruments for different classes of work.

### The resilience argument

When a funder's commitment is one of several independent commitments to the same Collegius, individual withdrawal does not stop the work. The more programs that have committed to the field, the less any single one of them can determine whether the work continues. This is the structural property that makes the Collegius form resilient to the political cycles of any single program.

### Conformance verification

Funders verify conformance through Section 4 of the standard. The legible structural state must be publicly readable at all times: current registry with weights and criterion, distribution invariant specification, distribution history, cadence compliance. If any of these is absent or requires asking the Collegius for access, the implementation does not satisfy the standard.

The hard limit: as long as the Collegius is conformant, funders have no standing to require access to or impose requirements on the internal coordination processes in Section 5. Conformance is verifiable from what Section 4 specifies. Internal coordination is for the Collegenii.

---

## Changelog

| Version | Date | Notes |
|---------|------|-------|
| 0.1.0 | 2026-04-19 | Initial skill. Two-mode architecture: practitioner (formation, criterion evaluation, CSIS conformance, coordination record) and funder (guarantee, exclusions, reading the legible structural state, benefits by funding mode, resilience argument, conformance verification). Known open questions flagged in practitioner mode. |
