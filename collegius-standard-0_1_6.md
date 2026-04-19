---
title: The Collegius Standard
document_id: collegius-standard-0_1_6.md
ring: Bucket (working specification)
version: v0.2.6
date: 2026-04-19
status: Working draft. Downstream from the Coordination Structural Integrity Suite and the Coordination Scaling Standard; not part of either. First specification built on top of the Coordination Structural Integrity Suite as structural backbone. The atomic unit is a Collegius; its members are Collegenii. General infrastructure any funder or ecosystem can adopt.
---

# The Collegius Standard

## Preamble

People doing sustained work in a particular field have no durable way to be recognized and funded collectively. They apply as individuals, explain themselves repeatedly to rotating audiences, and compete with each other for attention from funders who have limited context and less continuity than the work itself. Funders who want to support a field of work end up choosing between individual projects, which gives them more influence over who does the work than they may want or be equipped to exercise. And because claims are self-reported, there is no independent way to verify who has actually been doing the work over time.

This standard is the argument that all three problems are structural, and that a structural form can solve them — for contributors who currently apply as individuals, for funders who currently choose between individual projects rather than committing to a field of work, and for anyone trying to evaluate where sustained work is actually happening.

This standard specifies that structural form. Contributors form a collective body that curates its own membership. Funders commit to the body — and to the field of work it represents — not to individual projects. Value routes automatically to whoever is currently active, according to a rule set before any funder commits. The membership registry is publicly readable at all times: who is active, at what weight, with what history. Anyone can verify this directly, without asking. The form keeps funders out of membership decisions and keeps contributors in control of their field of work.

Adopting it requires a real trade. Contributors give up individual funding relationships in favor of a collective one. Individual positioning is replaced by collective infrastructure. That trade produces something more durable: a structure that persists through personnel changes and political moments that would end any individual grant relationship.

---

## Section 1: What a Collegius Is

A Collegius is a tensegrity configuration, not an organizational type. In structural terms: three elements hold each other in dynamic tension such that removing any one collapses the others. A DAO, a multisig, a foundation, or an unincorporated collective can each be a Collegius depending on whether those three constitutive conditions are present and genuinely load-bearing; the organizational form is not the test. The tensegrity concept and its application to coordination structures is developed in the Coordination Structural Integrity Suite at coordination-structural-integrity-suite.github.io.

The question "is this a Collegius or a project" is the wrong question in the same way that "is this precise or non-harming" is the wrong question in normative specification. A Collegius is what a project looks like when it has developed the structural architecture that makes its work organically sustainable: the project face and the routing face have become constitutively the same thing.

The structural configuration has three elements held in dynamic tension:

A self-curated membership registry. The registry tracks who is currently active in the field of work the Collegius covers, at what weight, according to a criterion specific enough that an independent observer can evaluate it without relying on social consensus. The registry is curated by contributors, not funders. Adding members dilutes existing members' shares, which makes careful vetting the economically rational choice rather than an imposed obligation.

A distribution invariant. Value sent to the Collegius routes to whoever currently satisfies the registry criterion, according to a rule that is specified before any funder commits and does not change based on who is funding or how much. The invariant is not a policy. It runs.

A funder interface that is stable precisely because it is thin. Funders commit to the field of work and the mechanism. They have no standing over membership, weights, or distribution timing. The interface's stability is not a limitation on funders; it is what makes funder exclusion from registry decisions the same move as contributor sovereignty over their field of work.

These three elements are not a checklist. Each one is structurally load-bearing for the others. A registry without the dilution incentive is a list. An invariant without a credible registry is a formula applied to noise. A thin funder interface without genuine contributor authority behind it is a facade. The tensegrity holds only when all three are present and genuinely constitutive of each other.

---

## Section 2: Membership and Registry

The coordination structure must enforce what the interface promises. Funder exclusion from registry decisions is not a cultural norm; it is a structural requirement enforced by the mechanism itself. A coordination arrangement where funders are excluded by convention but not by design does not satisfy this section.

**Formation statement.** Before any funder commits, a Collegius must produce a formation statement documenting: the membership criterion, the founding member set with independently verifiable attestation for each founder, the distribution invariant specification, and the coordination structure. The formation statement is the structural origin point of the attribution chain. The distribution invariant cannot be trustworthy without an attribution model underneath it: a distribution rule applied to contested or undocumented inputs is a formula applied to noise.

The formation statement must be recorded in a durable, timestamped format that is non-contestable retroactively and that includes the attribution precision bare attestation alone does not provide. Where onchain founding configuration tools are available, they are the preferred instrument for this purpose. Where they are not, the formation statement must document attribution as precisely as current tools allow. The formation requirement is not satisfied by bare attestation alone.

Founding members must themselves satisfy the membership criterion. A Collegius cannot be founded by people who do not qualify for membership. This is the structural resolution to the founding registry political bottleneck: the criterion comes first, and the founders demonstrate they meet it.

**The registry** is self-curated. Contributors propose additions and removals. No external party has standing to initiate a registry change. The dilution incentive is the quality control mechanism: because adding members reduces each existing member's share of distributions, the people curating the registry bear direct financial consequences for admitting members who should not be there. This incentive must be structurally present, not assumed.

**The membership criterion** must be specific enough that an independent observer can evaluate any proposed member against it without relying on social consensus from within the field. Vague criteria produce registry capture over time. The criterion must also state the Collegius's position on concurrent membership in other Collegii: whether it is permitted, restricted, or requires disclosure. Silence on this point does not satisfy the requirement. The criterion must state whether contributors whose work sustains the Collegius itself — documentation, communications, fundraising, operational coordination — are eligible for membership, and on what terms. This is a scope decision; the standard does not prescribe the answer, but requires one be given.

**The weight basis** — the method by which member weights are calculated — must be published and accessible to all members. Whether formula-based or criterion-based, any member must be able to evaluate whether their weight and others' are being calculated correctly. Opacity in weight-setting is a reliable source of friction; the requirement is that the method be clear enough to be checked.

**Membership attestation** must be independently verifiable by an external observer without requiring the Collegius's own assertion. Ethereum Attestation Service (EAS) is the reference implementation. Other mechanisms are conformant if they satisfy the same verifiability condition.

**Scale.** The Collegius must comply with the Coordination Scaling Standard at all crossed Radius thresholds. Effective Radius is an aggregate determination based on member count, interaction frequency and quality, shared context depth, and communication medium mix. Minimum conditions for all crossed thresholds must be structurally present; maximum conditions for all crossed thresholds must be absent. Growth does not require a membership cap; it requires that minimum conditions for each crossed threshold be installed before the crossing. The Coordination Scaling Standard specifies what those conditions are. A known gap: the minimum condition at Radius 15 — explicit mutual support architecture — is not currently specified by this standard. Collegii that cross the Radius 15 threshold should treat this as an open structural exposure and install explicit mutual support provisions before or at that crossing, drawing directly from the Coordination Scaling Standard.

**Conflict of interest disclosure.** Nominators proposing membership additions or weight changes must disclose conflicts of interest: advisory relationships, financial ties, or other relationships that could bias the proposal. The disclosure obligation falls on the nominator, not the nominee.

**Contested membership.** A defined process for contested membership decisions must exist and be documented before any contest arises. The process must name: who can raise a challenge, what evidence is required, how deliberation runs, and what constitutes resolution. This standard does not inherit an untested dispute resolution condition; the process must be specified and documented before any contest arises.

**Active and inactive status** must be defined. What constitutes a contribution break, how long a break can last before a member's status changes, and what happens to their weight and distributions during a break must all be specified and accessible to members before they join.

**Voluntary exit** must be available to any member without prohibitive cost. The terms of exit, including any effect on vested distributions, must be documented and accessible to members before they join.

**Keyholder structure:** selection, rotation, and conflict of interest terms for multisig or DAO keyholders must be documented. Keyholder composition must be monitored for concentration over time.

**Legal entity.** If the Collegius incorporates a legal entity, the entity's share of distributions, its stated purpose, and its accumulation limits must be documented and accessible to members and funders. The entity exists to serve the Collegius; its share and purpose must be justified and capped rather than open-ended.

---

## Section 3: Coordination Structural Integrity Suite Compliance Requirements

A Collegius operating under the Collegius Standard is downstream from the Coordination Structural Integrity Suite. The standard implements several of the suite's seven Tensegrity Compressive Standards as structural conditions rather than reporting obligations. Where the implementation is partial, this section produces the structural exposure disclosure the suite requires.

**Precision-First Design Standard:** the membership criterion must be independently evaluable without relying on social consensus from within the field. If the criterion cannot be evaluated from outside the Collegius's own interpretive frame, it does not satisfy this standard.

**Adverse Signal Engagement Principle:** a defined process for contested membership decisions must exist and be documented before any contest arises, accessible to any member without requiring the cooperation of the party being challenged.

**Structural Consent Legibility Standard:** contributor consent architecture must cover entry into the registry, any subsequent weight changes, and exit. Silence is not consent to entry. Exit must be available without prohibitive cost.

**Information Asymmetry Classification Standard:** the legible structural state, weight basis publication, and member contribution records reduce positional, interpretive, and complexity asymmetry within the Collegius. Conflict of interest disclosure in curation reduces relational asymmetry. The update history requirement in Section 5 addresses temporal and omission asymmetry to the extent the deliberation record surfaces what was considered. The six-class taxonomy is not adopted as a formal instrument; the omission class specifically requires Sensemaking Standard infrastructure that this standard does not mandate. This is the disclosure for that gap.

**Structural Power Obligation Standard:** funder exclusion from registry decisions must be structurally enforced. Keyholder selection, rotation, and conflict of interest terms must be documented.

**Regenerative Obligation Standard:** the Collegius must declare a regenerative stance in a publicly accessible, versioned location. The distribution model must demonstrably sustain contributors rather than route value past them.

**Coordination Scaling Standard:** minimum conditions for all crossed Radius thresholds must be structurally present. Maximum conditions for all crossed thresholds must be absent. The Collegius's registry architecture is the structural mechanism through which scale-legibility is maintained as the Collegius grows.

**Partial coverage disclosure**

Three areas where this standard's coverage is partial: the Radius 15 mutual support condition is not specified and must be sourced directly from the Coordination Scaling Standard when that threshold is crossed; omission asymmetry detection requires Sensemaking Standard infrastructure this standard does not mandate; and the contested membership and consent mechanisms depend on relational conditions that, in low-trust environments, can make structurally present mechanisms functionally hollow. These are known limits, not design oversights. Ecosystems implementing this standard should treat all three as adoption considerations.

---

## Section 4: The Funder Interface

The funder interface exposes three things: a receiving address, a legible structural state, and a defined update cadence. That is the complete interface. Its completeness is its thinness.

Funders can rely on one guarantee: value sent to the Collegius routes to whoever currently satisfies the registry criterion, according to the distribution invariant, without exception or redirection. This guarantee holds regardless of funder identity, contribution amount, or the political context of any given moment.

What the interface structurally excludes is as load-bearing as what it includes. Funders cannot control membership, direct distributions to specific contributors, veto registry changes, or require narrative reporting as a condition of the mechanism functioning. These exclusions are not restrictions on funders. They are what makes contributor sovereignty over their field of work real rather than nominal. The same structural move that excludes funder control is what gives contributors genuine authority over their own registry.

This fusion is the interface's central feature. A funder who understands it is not accepting a limitation; they are accepting the only arrangement under which the guarantee holds. The guarantee is only credible because no funder, including the largest, can alter what it produces.

The legible structural state is the legibility layer. "State" is used precisely here: an onchain record that exists as a timeline, not a snapshot. Every membership change, weight adjustment, and distribution event is timestamped, immutable, and readable by anyone, without asking the Collegius for anything. Current members, their weights, the date of the last update, the history of what has flowed and when — all of it is there because the mechanism is operating, not because a funder requested it.

A funder does not receive a report; they read the state directly. These are structurally different relationships. A report depends on the Collegius producing something for the funder; the legible structural state is produced by the mechanism's own operation and persists regardless of any funder relationship. The onchain format is also what substitutes for earned institutional trust. A newly formed Collegius has no accumulated credibility from years of operation. The chain provides it: any funder can verify how the Collegius has operated, for how long, with what membership history, without relying on the Collegius's own account of itself.

The vesting duration is the period over which donated value accrues before distribution. A Collegius may offer funders more than one option, but all available terms must be declared before any funder commits. Vesting duration is part of what a funder is agreeing to; changing it after a commitment is made is a breaking change to the interface.

The update cadence is the temporal commitment the Collegius makes to funders. New Collegii operate on a graduated cadence tied to time from formation, not to external trust assessment. Weekly updates are required for the first six months. Monthly updates are required for months seven through eighteen. Quarterly updates are the minimum floor thereafter. The cadence reduction is automatic on the time condition being met. No party certifies the transition.

The graduated cadence creates a gaming surface: a Collegius could perform minimal-effort updates that technically satisfy the frequency requirement without running meaningful coordination. This is not a problem the specification attempts to solve through additional requirements. The update history in Section 5 — what changed, what was deliberated, what was ratified — makes the quality of coordination legible to funders over time. A Collegius performing empty updates produces a legible record of doing so. This is consistent with the foundational principle: the specification creates conditions for legibility; funders and the ecosystem interpret what legibility reveals.

The following must be publicly readable at all times:

**Current registry:** active members, individual weights, the date weights were last calculated, the criterion against which they were assessed, and a link to each member's contribution record.

**Distribution invariant specification:** the distribution rule, versioned. Changes to the distribution invariant are breaking changes to the funder interface and must be disclosed with adequate notice before taking effect.

**Distribution history:** value received, value distributed, amounts per registry period, dates.

**Cadence compliance:** the current required update frequency given the Collegius's age from formation, and the date of the last update.

A new Collegius cannot inherit institutional trust. The legible structural state must therefore be implemented in a way that makes trust independently verifiable: readable directly by any party, without relying on the Collegius's own account of its state, without depending on member diligence, and without depending on the continuity of any individual operator. An implementation that requires a funder or observer to trust a party's description of what the state contains rather than reading it directly does not satisfy this requirement.

Membership changes, weight adjustments, and changes to the distribution invariant must be implemented such that no change takes effect in the distribution without a verifiable window during which any coordination actor can observe the pending change and respond. The length of that window, the consent architecture governing it, and the conditions for emergency action are governed by the Adverse Signal Engagement Principle and the Structural Consent Legibility Standard. Conformance with those standards is required. This standard does not re-specify those requirements; it requires that they be met.

External parties and funders verify conformance through what is specified in this section. As long as the Collegius is conformant, they have no standing to require access to or impose requirements on the internal coordination processes specified in Section 5.

---

## Section 5: The Coordination Record

The coordination record serves two distinct purposes. The first is internal coherence: members need shared context to coordinate with each other, evaluate contributions, and maintain the registry over time. The second is the structural separation of coordination from distribution: because the coordination record is maintained by and for the Collegenii, funders who commit through the funder interface have no standing to coordinate what it contains. The distribution invariant runs on the registry; it does not depend on funder access to the record that maintains the registry's integrity.

Both categories below are public. Their primary audience is the Collegenii.

**Stewardship record**

**Formation statement:** the founding configuration record, including the attribution model at formation and the founding member attestations, recorded in the most durable and verifiable format available at time of formation.

**Coordination structure:** how decisions are made, who holds multisig or DAO keys, selection and rotation terms.

**Update history:** for each update, what changed, what was deliberated, and what was ratified. The content of each update is part of the coordination record, not a summary produced for external parties.

**Former member record:** members who have left the Collegius, with dates of active membership. Former members are part of the attribution history of the field of work. The record must be publicly accessible.

**Internal coordination**

**Work organization.** The Collegius must document how its work is internally structured: what strands of work exist, how they relate to each other, and what each strand produces. The vocabulary — working groups, practice areas, focus areas, or another frame — is for each Collegius to determine. The requirement is that the structure be documented, accessible to all members, and reviewed periodically as the work evolves. It is a living description, not a founding artifact.

**Member contribution record.** Each active member maintains a contribution record that documents what they specifically do in the collective's field of work, with links to verifiable artifacts — repositories, research, published output, or equivalent evidence appropriate to the field — at a level of specificity that allows any other member to evaluate the contribution independently. A dedicated contribution page linked from the registry entry is the appropriate form at scale. The form is for each Collegius to determine; the specificity level is not.

**Concurrent membership disclosure.** Each active member must disclose any concurrent active membership in another Collegius. The Collegius's stated position on whether concurrent membership is permitted is set in the membership criterion. Disclosure is how that position is maintained in practice.

---

## Section 6: The Coordination Layer

The structural requirements in Sections 1 through 5 describe what a Collegius must have in place. This section describes what those requirements produce for the people inside it, not for funders and not for the broader ecosystem.

Funders need the interface to be thin. Members need the inside to be legible. These are different requirements served by different parts of the structure. A collective that is legible outward but opaque inward is not stable: internal opacity produces the same political dynamics the standard is designed to avoid, with decisions made by whoever has the most social capital, weights that cannot be evaluated, and contributions visible only to people who already know the contributor.

Shared orientation comes first. When the work is documented — what strands exist, who does what, what each strand produces — members can locate themselves and each other within the collective's work. This matters most as the Collegius grows: above a certain scale, the only reliable way to maintain genuine shared context is to make it readable rather than assume it is known.

Weight legibility reduces friction that compounds. When the basis for weights is published and applied consistently, members can evaluate whether weights are fair without that evaluation becoming a political contest. The weight formula must be available, the inputs documented, and any member able to calculate any other member's weight from first principles.

The curation process, when visible to all members with a defined deliberation window and required conflict-of-interest disclosure, produces more than accurate membership decisions. It creates a shared record of how the collective thinks about who belongs. That record becomes the clearest statement of what the membership criterion means in practice, as distinct from what the formation statement says it means.

Contributors who can see what each other does, who have a record of shared deliberation, and who have a persistent stake in the health of their shared field develop shared context that episodic collaboration does not produce. This is what makes the collective something beyond a payment-splitting arrangement, and what makes the work legible to contributors who join the collective later.

---

## Section 7: Structural Position Across Public Goods Funding Contexts

Every major funding mode is trying to answer the same question: is value being produced, by whom, with what evidence? The Collegius produces that evidence as a byproduct of operating. The question is already answered before any evaluation cycle begins.

What you gain from that varies by mode.

In expert committee and foundation programs, you stop being evaluated on what you tell reviewers. Reviewers read the legible structural state: who is active, at what weight, with what history. The evaluation work is done before anyone asks for it.

In community allocation programs — token voting, quadratic funding — the structural disadvantage runs deepest for contributors with limited marketing capacity and no institutional reputation. Individual projects must earn credibility each round through applications, community presence, and relationship maintenance. When you form a Collegius, your legitimacy as an organized collective in that field becomes structural. The mechanism's operating history speaks each cycle without you performing it again.

In network rewards routing, where protocols allocate a percentage of fees or block rewards to ecosystem work, a protocol can wire value to the distribution invariant and it runs. Multiple protocols can route to the same Collegius without coordinating with each other, and without coordination overhead between them.

In retroactive funding programs, you do not reconstruct your impact for evaluation. The registry has been running. Who was active, at what weight, over what period: it is already there. A Collegius is structurally self-evidencing in retroactive contexts in a way individual project applications cannot replicate.

In streaming and continuous funding, the distribution invariant fits the stream architecture directly. Registry weights determine flow rates.

In protocol treasury and DAO governance votes, a body voting to fund a Collegius decides whether to commit to the domain of expertise that particular collegius takes, not which individual applicants to prefer. The coordinative surface is narrower, and the attack surface for political capture narrows with it.

The one mode where the form does not apply is milestone-gated grants, and it is not a disadvantage — it is a boundary. Milestone gates are the right instrument for project-shaped work with completion dates. A Collegius is a persistent domain-specific coordination infrastructure; it is not complete. These are different instruments for different classes of work.

When your funding depends on any single program's allocation decision, whether you can sustain the work is hostage to that program's political cycle, personnel, and priorities in any given round. The thin funder interface is built to aggregate independent commitments. Any program can commit to the field your Collegius covers without affecting what others do. If one program withdraws, the others remain. The more programs that have committed to the field, the less any single one of them can determine whether the work continues.

---

## Section 8: Impact and the Structural Precondition

Under the project-oriented approach, impact has been nearly impossible to measure systematically, and therefore nearly impossible to improve on. The evaluation loop — where data from one cycle informs the next allocation decision — cannot close when legibility is episodic, self-reported, and reset each round. Without evaluation data that persists and compounds, each funding cycle begins from approximately the same starting point as the one before it. Funding does not become more targeted. The loop stays open.

The selection history of well-designed programs makes this visible. When an entity with structural legibility is chosen consistently over entities with self-reported impact, the pattern names something the programs have not yet articulated: funders and allocators are gravitating toward the only thing legible enough to trust consistently, without a shared vocabulary for why it is more trustworthy. The Collegius form names it.

What you gain by forming a Collegius is not simply a better mechanism. It is the capacity to close the loop your work has been caught in.

Your work persists past funding cycles. The distribution invariant routes value to whoever currently satisfies the membership criterion, regardless of what any single program allocates in any given round. You are no longer dependent on the outcome of any individual application. The work continues because the mechanism sustains it.

You stop being individually responsible for justifying collective impact. Impact in public goods accumulates through sustained collective presence, not individual deliverables. The project-oriented approach requires individual actors to attribute impact to themselves to remain legible to funders — accurate in a narrow sense, but misleading about how systemic change actually happens. The Collegius attributes collectively by design. Value flows to everyone currently contributing to the collective's field of work, which is structurally more honest about how the impact is produced.

The capacity you were spending on grant applications, milestone reports, community engagement, and funder relationship maintenance goes back to the work. For communities doing important collective work, that overhead is a direct tax on impact production. The mechanism produces legibility as a byproduct of running; the thin interface removes the need for ongoing relationship maintenance. Both free capacity that was previously spent on proving the work rather than doing it.

All three arrive simultaneously when you form a Collegius. Persistence, honest attribution, and reduced overhead are not sequential gains or conditional improvements. They are structural properties of the form, and individual projects working in the same field pursuing them separately are duplicating coordination overhead, fragmenting collective legitimacy, and each facing the cycle-reset problem alone.

The boundary operates at two levels. The first is the nature of the work: the Collegius form suits combinations where the output is collective rather than individually attributed, where sustained presence in the field compounds rather than resets, and where contributors' interests in the shared field are complementary rather than purely competitive. Entities that compete in some respects can cooperate structurally on the dimensions where interests genuinely align. The question is whether the specific work being brought into the Collegius is complementary, not whether the entities have competitive relationships elsewhere. The second level is the specific combination: even where the work fits, not every grouping of contributors will. Compatible coordination orientations and genuine shared interest in collective rather than individual attribution are preconditions the work type alone does not guarantee. Where both are met, the advantage is substantial.

## Section 9: Open Questions

**Membership criterion design for new fields of work.** How does a Collegius establish a legible membership criterion in a field where social consensus about who qualifies does not yet exist? When a field of work has pre-existing consensus about who its contributors are, the criterion inherits that legibility. New Collegii in less established fields must design that legibility from scratch. The formation statement requirement addresses the formal record; the question of how to build the social legibility that makes the criterion credible remains open.

**Transition from existing projects.** How does an existing project in an adopting ecosystem migrate toward Collegius structure? This is not a question the standard can resolve internally; it depends on the policies of the ecosystem adopting the Collegius Standard. Left to each ecosystem's implementation.

**Multiple Collegius membership.** Contribution across multiple fields of work is real and should be recognizable. Each Collegius defines its own membership criterion, which may or may not permit concurrent membership in another Collegius. This standard does not prescribe a position on the question; it is a criterion design decision internal to each Collegius.

**Collegius dissolution.** What happens when a Collegius fails, loses quorum for its coordination process, or dissolves? The distribution invariant specification must include terms for what happens to unvested funds at dissolution before any funder commits. The broader question of coordination failure short of dissolution is open.

**Onchain registry format.** This standard requires that the legible structural state be implemented as an onchain record with verifiable history. No standardized smart contract interface currently exists for membership registries at the specificity this standard requires. Distribution mechanisms have de facto standards in split contract protocols; the membership registry does not. A canonical onchain format for the registry — field schema, update event structure, and query interface — is required for ecosystem-wide legibility and tooling to be possible. This is a blocking open question for adoption at scale and should be resolved by a coordination data protocol specification before broad ecosystem adoption proceeds.

**Membership state to distribution state automation.** This standard's trust architecture requires eliminating the human translation step between membership changes and distribution weight updates — the gap where social trust currently substitutes for structural verifiability. No established implementation pattern for this automation exists. The automation creates attack surface that the Adverse Signal Engagement Principle and Structural Consent Legibility Standard govern in principle; the specific implementation architecture remains unresolved. This is new territory this standard introduces and requires a reference implementation before it can be specified normatively.

---

## Changelog

| Version | Date | Notes |
|---------|------|-------|
| v0.2.6 | 2026-04-19 | Section 1: tensegrity gloss added — plain-language explanation of what tensegrity means structurally, organizational form is not the test, CSIS reference and URL added. Section 4 opening: "readable registry state" corrected to "legible structural state" for consistency with the term defined later in the section. |
| v0.2.5 | 2026-04-19 | Section 4: legible structural state paragraph rewritten to define "state" precisely as an onchain timeline record, establish the temporal and historical dimension, and name the trust-building rationale for new Collegii. Trust architecture normative statement added: independent verifiability requirement; CSIS conformance requirement for membership change windows (Adverse Signal Engagement Principle and Structural Consent Legibility Standard). Section 7: "mechanism's state" corrected to "legible structural state"; sufficiency paragraph rewritten to remove undefined term and explain the resilience argument directly. Section 8: "coopetition" jargon removed. Section 9: two new open questions added — onchain registry format (blocking for adoption at scale) and membership-to-distribution state automation gap. |
| v0.2.4 | 2026-04-19 | Document-wide vocabulary pass: "domain" replaced with "field of work," "field," "the work," or equivalent expansions throughout — the term was overused (~30 instances) as unexplained shorthand. Frame Language governance pass: remaining normative instances of "govern/governance" replaced with precise action terms ("curated by contributors," "control membership," "registry decisions," "contributor authority," "coordination structure") per Frame 2 register requirements. Three intentional user-authored expansions retained in Section 7 ("domain of expertise," "domain-specific," "domain expertise"). |
| v0.2.3 | 2026-04-19 | Major section restructuring: document reorganized around the internal/external audience boundary. New Section 2 (Membership and Registry, formerly Section 3) moved before the funder interface sections. New Section 3 (CSIS Compliance, formerly Section 4). New Section 4 (The Funder Interface, formerly Section 2) restructured: legible structural state items added as formal list, hard limit statement added (funders have no standing to require access to internal coordination processes as long as conformant), Frame Language corrections applied throughout. New Section 5 (The Coordination Record) combines the stewardship record from former Section 5 and internal coordination from former Section 6: two-purpose framing added (internal coherence and structural separation of coordination from distribution). Former Sections 7–10 renumbered to 6–9. Section 6 cross-reference updated (Sections 1–5). Frame Language corrections throughout: "accountability" → "legibility," "governance arrangement/structure" → "coordination arrangement/structure," "Multisig or DAO keyholder governance" → "Keyholder structure," "member contribution descriptions" → "member contribution records," "compatible governance orientations" → "compatible coordination orientations." |
| v0.2.2 | 2026-04-19 | Preamble rewritten: problem paragraph added (individual application, self-reported claims, funder over-influence); bridging sentence names the standard as a structural argument for contributors, funders, and impact evaluation; solution paragraph follows; trade paragraph retained. All Protocol Guild mentions removed from body, frontmatter, and changelog. Changelog collapsed: v0.1.0–v0.1.9 entries replaced with single summary entry. |
| v0.2.1 | 2026-04-19 | Section 5 restructured: two-layer framing added with approved vocabulary. Legible structural state (external-facing: current registry, distribution invariant specification, distribution history, cadence compliance) separated from stewardship record (internal coordination record: formation statement, governance structure, update history, former member record). Framing paragraph explains audience distinction — funders need only the legible structural state; the stewardship record is for the Collegenii. "Invariant specification" corrected to "distribution invariant specification" throughout Section 5. Frontmatter version corrected from v0.1.9 to v0.2.1 (v0.2.0 was not reflected in frontmatter). |
| v0.2.0 | 2026-04-19 | CSIS conformance recheck against canonical GitHub repo. Section 4 rewritten: Information Asymmetry Classification Standard added as seventh compressive standard; structural exposure disclosure added per suite integration guide requirements (Radius 15 gap, omission class detection gap, detection reliability bounds on contested membership and consent architecture). Opening paragraph corrected to not imply full suite conformance. |
| v0.1.0–v0.1.9 | 2026-04-17 to 2026-04-19 | Working draft developed through an extended collaborative process. Early versions established the core structural form; subsequent versions corrected naming, section organization, and CSIS conformance. Precision-mode revision began at v0.2.0. |
