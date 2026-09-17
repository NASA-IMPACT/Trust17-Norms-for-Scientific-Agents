# TRUST-17

**A proposal for 17 community norms for trustworthy AI agents in science.**

> **Status:** Draft v0.1 — open for community comment. Not a standard, not a specification.

TRUST-17 proposes a starting set of community *expectations* for how scientific agents should behave, how they should be engineered and evaluated, and how they should be governed across their operational lifecycle. It applies to any AI agent that materially participates in scientific work — not only enterprise or production systems.

These are not best practices. They are the baseline from which best practices can be developed, and those will reasonably differ across scientific domains.

**→ [Read the full text: TRUST-17.md](TRUST-17.md)**

## Proportionate application

The rigor required to satisfy a norm should scale with the agent's role and risk:

| Agent context | Example | How norms apply |
|---|---|---|
| Personal / exploratory | A scientist's own literature-search or analysis skill | Lightweight; primarily Layer 1, with basic provenance and awareness of limitations |
| Shared / research | Lab-developed agent shared with collaborators or published with a paper | Layers 1 + 2 strongly apply; Layer 3 begins to apply because others depend on it |
| Operational / institutional | Repository agent, production science workflow, autonomous data processing | All three layers, with formal specifications, evaluation evidence, monitoring, stewardship, change control |

## The seventeen norms

**Layer 1 — Agent-Level: how an agent should behave**

1. Defined Purpose and Boundaries
2. Grounding in Appropriate and Authoritative Scientific Evidence
3. Controlled and Authorized Use of Tools, Data, and Services
4. Uncertainty, Limits, and Escalation
5. Traceability and Process Provenance

**Layer 2 — Development and Verification: how an agent should be built and assured**

6. Define Intended Use, Excluded Use, and Expected Outcomes
7. Develop from Explicit and Reviewable Specifications
8. Include Appropriate Scientific and Domain Expertise in Design and Review
9. Evaluate Against Realistic Scientific Tasks and Failure Conditions
10. Define Human Oversight and Decision Authority
11. Version and Re-evaluate Material Changes

**Layer 3 — Operational and Ecosystem: how an agent should be shared and governed**

12. Assign Clear Stewardship and Accountability
13. Publish Standardized Agent Documentation
14. Preserve Attribution, Provenance, and Scientific Lineage
15. Make Scientific Agents Discoverable, Versioned, and Citable
16. Monitor Supported Agents After Release
17. Govern Changes, Contributions, Deprecation, and Retirement

## Feedback

Comment and discussion are welcome:

- **Discussions** — open questions, disagreement with framing, missing norms, domain-specific experience
- **Issues** — concrete proposed edits to norm text

Norm numbers (N1–N17) are stable identifiers. Cite them as, for example, *TRUST-17 N7*.

## Citation

<!-- Replace with a Zenodo DOI once a release is tagged. -->

    TRUST-17: Proposal for 17 Community Norms for Trustworthy AI Agents in Science.
    Draft v0.1. <YEAR>. <URL>

## Initial Authors
Rahul Ramachandran, Nidhi Jha, Samrawit Gebre, Kaylin Bugbee

## Contributions
Participants - 2026 Open Source Science Data Repositories Meeting, Arlington, VA. Sept 1-3, 2026

## License

<!-- CC BY 4.0 is a common choice for a document of this kind. -->
