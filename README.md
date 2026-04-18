# The Collegius Standard

The Collegius Standard requires combination. Contributors who adopt it stop applying for funding individually and join a shared registry. Their individual negotiating relationships with funders are replaced by a collective structural relationship. The distribution invariant routes value to whoever currently satisfies the membership criterion — not to whoever made the strongest case this round. That is the ask, and it is not small.

The trade is flexibility for durability. Individual positioning gives way to collective infrastructure that doesn't require contributors to keep proving their existence each funding cycle. No application. No milestone report. No relationship maintenance with funders whose priorities may shift. The mechanism runs. Funders commit to a domain rather than to a project, and that commitment survives personnel changes, political moments, and the natural turnover of any contributor community over time.

Protocol Guild is the evidence this trade is worth making. They didn't design a clever mechanism and then recruit contributors willing to try it. They found themselves in the problem — individually underfunded, collectively indispensable to Ethereum's continued development — and built their way out of it. What they built happened to be a Collegius. The structural form they arrived at by necessity is exactly what the Collegius Standard makes reproducible: a self-curating registry of domain practitioners, a distribution invariant that runs without funder intervention, and a thin interface that lets funders commit to a domain rather than manage a project. Any domain facing the same structural condition can now adopt that form deliberately rather than having to rediscover it under pressure.

---

## Context-independence as a design quality

The most durable innovations share a structural property: they encode their operating logic into the mechanism itself rather than depending on ongoing human judgment to keep running.

Double-entry bookkeeping has been in continuous use for over seven hundred years because the rule (every transaction has two sides, debits equal credits) works regardless of who is applying it, what goods are being tracked, or what political arrangement is in place. TCP/IP routes packets regardless of what they contain, who sent them, or why. The Uniform Penny Post reduced administrative machinery to nearly nothing by replacing a distance-based, recipient-pays calculation with a single invariant: one price, anywhere, paid by the sender. Each of these innovations encodes its operating logic into the mechanism. The mechanism does not need to be renegotiated when conditions change. It runs.

This quality is what The Collegius Standard is designed to make achievable for contributor communities. A conformant Collegius does not need to re-prove its value each funding cycle because its architecture produces continuous, readable accountability by default. The accountability is constitutive of the structure, not a separate reporting burden on top of it.

---

## What a conformant Collegius is

A conformant Collegius is a contributor community organized around three elements held in structural tension:

A **self-curated membership registry** that tracks who is currently contributing, with allocation weights updated on a defined cadence. The registry is governed by Collegenii, not funders. Each addition dilutes existing members' shares, which creates a direct incentive for careful vetting: the people governing the registry bear the financial consequences of getting it wrong.

A **distribution invariant**: a formula, specified in advance, that determines how value flows from the registry to Collegenii. The formula runs. No funder directs distributions to specific individuals or purposes.

A **thin funder interface**: funders choose whether to send value to the Collegius and at what level. They do not govern membership, weights, or distribution timing. The funder's relationship is with the mechanism, not with any specific person or political moment.

The result is a domain router rather than a project applying for grants. The Collegius is persistent infrastructure for routing value to people doing important work in a specific domain. The funder's commitment to the mechanism survives personnel changes, political shifts, and the natural turnover of any contributor community over time.

---

## Why structural architecture generates trust at scale

Trust in contributor communities is currently personal and reputational: it requires knowing the people involved. That model works at small scale. It does not scale beyond the founding relationships. When a funder cannot know all the contributors personally, the decision becomes one of institutional trust, which means trusting whoever controls the institution, which means the funder's trust is ultimately trust in specific people rather than in a structure.

A mechanism whose operating logic can be read from its design alone generates a different kind of trust. The funder does not need to know the contributors personally. They do not need to trust the people running the mechanism. They need to verify that the mechanism's design does not privilege any specific party: it routes value according to a rule that runs the same way regardless of who satisfies it.

This is not just a fairness property. It is a trust-generation property. A credibly neutral mechanism can attract a larger and more diverse set of funders precisely because funders do not need to be inside the social network to extend trust. The mechanism's architecture is what they are trusting.

The Collegius Standard specifies what that architecture requires.

---

## Dunbar-scale legibility

Structural architecture is necessary but not sufficient. The Collegius Standard also requires that a Collegius comply with the Coordination Scaling Standard at all crossed Radius thresholds — which means minimum conditions for each scale threshold must be structurally present before that threshold is crossed.

At the Dunbar threshold of approximately 150 people, reputation-based coordination functions without institutional enforcement. The community is small enough that Collegenii can know each other's work, form views about whether the registry is being managed well, and exercise informed judgment in the coordination process. Social accountability is possible because the group is socially legible. Growth beyond any Radius threshold requires the structural conditions the Coordination Scaling Standard specifies — not a cap, but a floor that must be installed before the crossing.

---

## CSIS as the structural backbone

The Collegius Standard is a downstream operational standard from the [Coordination Structural Integrity Suite](https://github.com/coordination-structural-integrity-suite/suite) (CC BY 4.0, Regis Chapman). The suite specifies nine structural standards for coordination systems that need to be accountable, consent-legible, and exploitation-resistant. The Collegius Standard applies those conditions to contributor community infrastructure specifically.

Conformance with The Collegius Standard requires that the Collegius's architecture be configured to meet the relevant suite standards structurally — not through reporting, but through design. A Collegius that meets the standard is not one that produces reports demonstrating compliance. It is one whose architecture makes non-compliance structurally difficult.

---

## The specification

[`collegius-standard-0_1_6.md`](collegius-standard-0_1_6.md), v0.1.6, 2026-04-18.

The specification covers six sections: what a Collegius is, the interface specification (what a Collegius exposes to funders and why), internal coordination requirements, how the Collegius's architecture maps to the Coordination Structural Integrity Suite standards, conformance legibility requirements, and open questions at this version.

---

## Licensing

The written specification in this repository is licensed under [Creative Commons Attribution 4.0 International](LICENSE-SPEC) (CC BY 4.0).

Any reference implementations, tooling, or code in this repository are licensed under the [Apache License 2.0](LICENSE).

Copyright 2026 Regis Lloyd Chapman.
