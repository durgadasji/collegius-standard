---
title: The Clan Standard
document_id: clan-standard-0_1_4.md
ring: Bucket (working specification)
version: v0.1.5
date: 2026-04-17
status: Working draft. Collaboratively developed across one session. All six sections present. Downstream from the Coordination Structural Integrity Suite and the Coordination Scaling Standard; not part of either. First specification built on top of the Coordination Structural Integrity Suite as structural backbone. The atomic unit is a Clan. CLaaS (Clan-As-A-Service) is the service category a company would build to implement this standard; the standard itself is The Clan Standard. Not Octant-specific; general infrastructure any funder or ecosystem can adopt. Protocol Guild is the primary empirical reference.
---

# The Clan Standard

## Section 1: What a Clan Is

A clan is a tensegrity configuration, not an organizational type. The question "is this a clan or a project" is the wrong question in the same way that "is this precise or non-harming" is the wrong question in normative specification. A clan is what a project looks like when it has developed the structural architecture that makes its work organically sustainable: the project face and the routing face have become constitutively the same thing.

The structural configuration has three elements held in dynamic tension:

A self-curated membership registry. The registry tracks who is currently active in the domain, at what weight, according to a criterion specific enough that an independent observer can evaluate it without relying on social consensus. The registry is governed by contributors, not funders. Adding members dilutes existing members' shares, which makes careful vetting the economically rational choice rather than an imposed obligation.

A distribution invariant. Value sent to the clan routes to whoever currently satisfies the registry criterion, according to a rule that is specified before any funder commits and does not change based on who is funding or how much. The invariant is not a policy. It runs.

A funder interface that is stable precisely because it is thin. Funders commit to the domain and the mechanism. They do not govern membership, weights, or distribution timing. The interface's stability is not a limitation on funders; it is what makes funder exclusion from governance the same move as contributor sovereignty over the domain.

These three elements are not a checklist. Each one is structurally load-bearing for the others. A registry without the dilution incentive is a list. An invariant without a credible registry is a formula applied to noise. A thin funder interface without genuine contributor governance behind it is a facade. The tensegrity holds only when all three are present and genuinely constitutive of each other.

---

## Section 2: The Interface Specification

The funder interface exposes three things: a receiving address, readable registry state, and a defined update cadence. That is the complete interface. Its completeness is its thinness.

Funders can rely on one guarantee: value sent to the clan routes to whoever currently satisfies the registry criterion, according to the invariant, without exception or redirection. This guarantee holds regardless of funder identity, contribution amount, or the political context of any given moment.

What the interface structurally excludes is as load-bearing as what it includes. Funders cannot govern membership, direct distributions to specific contributors, veto registry changes, or require narrative reporting as a condition of the mechanism functioning. These exclusions are not restrictions on funders. They are what makes contributor sovereignty over the domain real rather than nominal. The same structural move that excludes funder control is what gives contributors genuine authority over their own registry.

This fusion is the interface's central feature. A funder who understands it is not accepting a limitation; they are accepting the only arrangement under which the guarantee holds. The guarantee is only credible because no funder, including the largest, can alter what it produces.

The readable registry state is the accountability layer. Current members, their weights, the date of the last update, the history of what has flowed and when. All of this is publicly verifiable by anyone at any time. The accountability is not produced by reporting. It is produced by the mechanism's own operation. A funder does not receive a report; they read the state. These are structurally different relationships to accountability. The first depends on the clan producing something for the funder. The second depends on the funder being able to read what the clan produces for itself.

The clan must expose this state in a format readable by an external conformance tool. The specification defines what must be exposed. What surfaces that state to funders is external infrastructure (a CLaaS Viewer or equivalent) whose specification lives separately. The clan's obligation is legible state, not the viewer that reads it.

The update cadence is the temporal commitment the clan makes to funders. New clans operate on a graduated cadence tied to time from formation, not to external trust assessment. Weekly updates are required for the first six months. Monthly updates are required for months seven through eighteen. Quarterly updates are the minimum floor thereafter. The cadence reduction is automatic on the time condition being met. No party certifies the transition.

The graduated cadence creates a gaming surface: a clan could perform minimal-effort updates that technically satisfy the frequency requirement without running meaningful governance. This is not a problem the specification attempts to solve through additional requirements. The CLaaS Viewer surfaces the content of each update (what changed, what was deliberated, what was ratified) making the quality of governance legible to funders over time. A clan performing empty updates produces a legible record of doing so. This is consistent with the foundational principle: the specification creates conditions for legibility; funders and the ecosystem interpret what legibility reveals.

---

## Section 3: Internal Governance Requirements

The governance structure must enforce what the interface promises. Funder exclusion from registry decisions is not a cultural norm; it is a structural requirement enforced by the mechanism itself. A governance arrangement where funders are excluded by convention but not by design does not satisfy this section.

**Formation statement.** Before any funder commits, a clan must produce a formation statement documenting: the membership criterion, the founding member set with independently verifiable attestation for each founder, the invariant specification, and the governance structure. The formation statement is the structural origin point of the attribution chain. The invariant cannot be trustworthy without an attribution model underneath it: a distribution rule applied to contested or undocumented inputs is a formula applied to noise.

The Founding Charter Tool (FCT) is the designated instrument for producing the formation statement, as it produces a durable, timestamped, onchain founding configuration record that is non-contestable retroactively and includes the attribution precision that bare attestation services do not provide. Where FCT is not yet available, the formation statement must document attribution as precisely as current tools allow, with an explicit commitment to FCT migration when the tool reaches specification. The formation requirement is not satisfied by bare attestation alone.

Founding members must themselves satisfy the membership criterion. A clan cannot be founded by people who do not qualify for membership. This is the structural resolution to the founding registry political bottleneck: the criterion comes first, and the founders demonstrate they meet it.

**The registry** is self-curated. Contributors propose additions and removals. No external party has standing to initiate a registry change. The dilution incentive is the quality control mechanism: because adding members reduces each existing member's share of distributions, the people governing the registry bear direct financial consequences for admitting members who should not be there. This incentive must be structurally present, not assumed.

**The membership criterion** must be specific enough that an independent observer can evaluate any proposed member against it without relying on domain social consensus. Vague criteria produce registry capture over time.

**Membership attestation** must be independently verifiable by an external observer without requiring the clan's own assertion. Ethereum Attestation Service (EAS) is the reference implementation. Other mechanisms are conformant if they satisfy the same verifiability condition. The CLaaS Viewer reads whichever mechanism the clan uses and surfaces membership evidence in a standard format.

**Scale.** The clan must comply with the Coordination Scaling Standard at all crossed Radius thresholds. Effective Radius is an aggregate determination based on member count, interaction frequency and quality, shared context depth, and communication medium mix. Minimum conditions for all crossed thresholds must be structurally present; maximum conditions for all crossed thresholds must be absent. Growth does not require a membership cap; it requires that minimum conditions for each crossed threshold be installed before the crossing. The Coordination Scaling Standard specifies what those conditions are.

**Contested membership.** A defined process for contested membership decisions must exist and be documented before any contest arises. The process must name: who can raise a challenge, what evidence is required, how deliberation runs, and what constitutes resolution. Protocol Guild has never had a public hard membership dispute; the specification cannot inherit that untested condition.

**Voluntary exit** must be available to any member without prohibitive cost. The terms of exit, including any effect on vested distributions, must be documented and accessible to members before they join.

**Multisig or DAO keyholder governance:** selection, rotation, and conflict of interest terms must be documented. Keyholder composition must be monitored for concentration over time.

---

## Section 4: Coordination Structural Integrity Suite Compliance Requirements

A clan operating under the Clan Standard is downstream from the Coordination Structural Integrity Suite. Compliance with the following standards is required as structural conditions, not as reporting obligations. The clan does not report compliance; it is configured for it. The clan's organic functioning produces suite-relevant structural conditions as a byproduct, in the same way Protocol Guild arrived at these conditions without knowing the suite existed.

**Precision-First Design Standard:** the membership criterion must be independently evaluable without domain social consensus. If the criterion cannot be evaluated from outside the clan's own interpretive frame, it does not satisfy this standard.

**Adverse Signal Engagement Principle:** a defined process for contested membership decisions must exist and be documented before any contest arises, accessible to any member without requiring the cooperation of the party being challenged.

**Structural Consent Legibility Standard:** contributor consent architecture must cover entry into the registry, any subsequent weight changes, and exit. Silence is not consent to entry. Exit must be available without prohibitive cost.

**Structural Power Obligation Standard:** funder exclusion from registry governance must be structurally enforced. Multisig or DAO keyholder selection, rotation, and conflict of interest terms must be documented.

**Regenerative Obligation Standard:** the clan must declare a regenerative stance in a publicly accessible, versioned location. The distribution model must demonstrably sustain contributors rather than route value past them.

**Coordination Scaling Standard:** minimum conditions for all crossed Radius thresholds must be structurally present. Maximum conditions for all crossed thresholds must be absent. The clan's registry architecture is the structural mechanism through which scale-legibility is maintained as the clan grows.

---

## Section 5: Conformance Legibility

The clan must expose the following state in a format readable by an external conformance tool. The clan's obligation is the state. The CLaaS Viewer or equivalent tool that reads it is external infrastructure.

**Current registry:** active members, individual weights, the date weights were last calculated, and the criterion against which they were assessed.

**Invariant specification:** the distribution rule, versioned. Changes to the invariant are breaking changes to the funder interface and must be disclosed with adequate notice before taking effect.

**Update history:** for each update, what changed, what was deliberated, and what was ratified. The content of each update is part of the exposed state, not a summary produced for funders.

**Distribution history:** value received, value distributed, amounts per registry period, dates.

**Governance structure:** how decisions are made, who holds multisig or DAO keys, selection and rotation terms.

**Cadence compliance:** the current required update frequency given the clan's age from formation, and the date of the last update.

**Formation statement:** the founding configuration record, including the attribution model at formation and the founding member attestations. Where FCT has been completed, the FCT record satisfies this requirement. Where FCT is pending, the best available formation record must be present with explicit notation of the gap.

---

## Section 6: Open Questions

**Membership criterion design for new domains.** How does a clan establish a legible membership criterion in a domain where social consensus about who qualifies does not yet exist? Protocol Guild's criterion was pre-legible because the Ethereum ecosystem had existing consensus about L1 core contributors. New clans in less obvious domains must design that legibility from scratch. The formation statement requirement addresses the formal record; the question of how to build the social legibility that makes the criterion credible remains open.

**Transition from existing projects.** How does an existing project in an adopting ecosystem migrate toward clan structure? This is not a question the standard can resolve internally; it depends on the policies of the ecosystem adopting the Clan Standard. Left to each ecosystem's implementation.

**Multiple clan membership.** Can a contributor be an active member of more than one clan simultaneously? Protocol Guild does not address this. Logically, contribution to multiple domains is real and should be recognizable. How weights and distributions are handled across memberships requires further specification.

**Clan dissolution.** What happens when a clan fails, loses quorum for its governance process, or dissolves? Protocol Guild's contracts specify what happens to unvested funds at dissolution; the invariant specification must include these terms before any funder commits. The broader question of governance failure short of dissolution is open.

**CLaaS Viewer specification.** The conformance tool that reads clan state and surfaces it to funders requires its own specification. It may be implemented as part of Revelis, as a standalone interface, or as ecosystem-specific tooling. Its specification lives separately from this document.

**FCT readiness.** The Founding Charter Tool is the designated instrument for formation statements but is not yet at specification stage. Early clans forming before FCT is ready must document the gap explicitly and commit to migration. The timing and process for that migration is open.

---

## Changelog

| Version | Date | Notes |
|---------|------|-------|
| v0.1.5 | 2026-04-17 | Section 3 Scale paragraph: Effective Radius factor list updated to match Coordination Scaling Standard v0.1.3. "Developmental alignment" removed; "communication medium mix" added. No other content changes. |
| v0.1.4 | 2026-04-17 | Section 3 Scale paragraph rewritten: removed cap framing, reversed direction error on Radius 150 informal governance, removed organizational prescriptions not present in the Coordination Scaling Standard. Section 4 SPOS entry trimmed to funder exclusion and keyholder governance only; Radius subsidiarity language removed. Coordination Scaling Standard added as explicit compliance item in Section 4. |
| v0.1.3 | 2026-04-17 | Renamed from Clan-As-A-Service Specification to The Clan Standard. CLaaS is the service category for implementations; the standard itself is The Clan Standard. Remaining "CLaaS" reference in Section 6 corrected to "the Clan Standard." |
| v0.1.2 | 2026-04-17 | Section 4 title expanded to full suite name. "Governance decisions" replaced with "Coordination decisions" in Sections 3 and 4 (Frame Language). Em-dash pass applied throughout. Prose improvements to registry state accountability passage and CLaaS Viewer reference. |
| v0.1.1 | 2026-04-17 | Scale references updated to use Radius vocabulary and point to the Coordination Scaling Standard. Frontmatter updated to name the Coordination Scaling Standard as explicit dependency. |
| v0.1.0 | 2026-04-17 | Complete working draft. All six sections. Renamed from Guild-As-A-Service to Clan-As-A-Service (CLaaS). Formation statement, FCT reference, EAS attestation, Dunbar nested structure, subsidiarity, CSIS compliance, conformance legibility, open questions |
