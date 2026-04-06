# AI Visibility Lifecycle Framework — Community Group Charter

**W3C Community Group**

| Field | Detail |
|---|---|
| Charter Version | 1.0 |
| Date | 6 April 2026 |
| Group Home Page | https://www.w3.org/community/ai-web-visibility/ |
| Mailing List | https://lists.w3.org/Archives/Public/public-ai-web-visibility/ |
| GitHub Repository | https://github.com/ai-visibility-architects/ai-visibility-lifecycle-cg |
| Chair | Bernard Lynch |

---

## 1. Goals

As AI systems increasingly determine what web content people see, there is no shared vocabulary, framework, or measurement approach for understanding how websites achieve visibility — or remain invisible — within AI discovery and response systems. Publishers, website developers, platform operators, agencies, AI system developers, and researchers lack common reference points for evaluating how website content is discovered, understood, trusted, and surfaced by AI systems.

The mission of the AI Visibility Lifecycle Framework Community Group is to provide a collaborative forum to explore these challenges, with the aim of developing shared vocabulary, measurement approaches, and best practices for understanding how websites and their content achieve visibility within AI discovery and response systems.

The 11-Stage AI Visibility Lifecycle framework, authored by Bernard Lynch (DOI: [10.5281/zenodo.18460710](https://doi.org/10.5281/zenodo.18460710)), is intended to serve as a starting point for discussion within the group, but is not intended to constrain the group's discussions or decisions about future deliverables.

The group is a genuine collaborative forum. While the initial framework is single-authored, the group's direction, deliverables, and priorities are determined by its participants through the decision process defined in this charter. The framework is offered as a reference point to ground early discussion, not as a fixed or locked deliverable.

### 1.1 Background and Context

AI systems now mediate a significant and growing share of how people discover web content. Search engines, conversational AI assistants, recommendation systems, and autonomous agents all crawl, evaluate, and surface websites through processes that are poorly understood and largely undocumented. There is no shared vocabulary for describing these processes and no common framework for practitioners to evaluate whether their websites are being discovered, understood, trusted, or surfaced.

The 11-Stage AI Visibility Lifecycle, published by Bernard Lynch in January 2026, is the first structured lifecycle framework specifically dedicated to describing end-to-end AI-mediated web visibility, from initial crawl through trust establishment to human surfacing. The framework identifies three phases: AI Comprehension (Stages 1–5), Trust Establishment (Stages 6–8), and Human Visibility (Stages 9–11). It is registered as an IETF Internet-Draft (draft-lynch-ai-visibility-lifecycle) and deposited on Zenodo under CC BY-NC-ND 4.0.

This Community Group exists to bring collaborative scrutiny to this emerging field. The framework provides a shared starting vocabulary; the group's participants will determine whether that vocabulary holds, how it should evolve, and what additional work is needed.

---

## 2. Scope of Work

The group's scope encompasses the study, documentation, and development of shared vocabulary and frameworks for understanding how AI systems discover, evaluate, trust, and surface websites and their content. Specific areas within scope include:

- Defining shared vocabulary for AI content visibility stages and processes
- Developing observational frameworks for how AI systems crawl, ingest, classify, and surface content
- Exploring measurement approaches for website visibility within AI discovery systems
- Documenting best practices for website architecture as it relates to AI discoverability
- Examining the relationship between structured data, semantic markup, and AI visibility
- Investigating trust signals and provenance indicators that influence AI content surfacing
- Studying the interaction between traditional search engine optimisation and AI-mediated content discovery

The group does not seek to create normative standards or protocols. Work products are observational and analytical, intended to support practitioners and researchers in understanding an emerging field.

### 2.1 Out of Scope

The following topics are explicitly out of scope:

- Prescriptive requirements or conformance criteria for AI systems
- Regulation or policy recommendations for AI content discovery
- Development of search engine ranking algorithms or proprietary optimisation techniques
- Evaluation of specific commercial AI platforms or products
- Topics covered by the AI Content Disclosure Community Group (disclosure of AI involvement in content creation)
- Marketing or promotion of specific commercial methodologies or services

---

## 3. Deliverables

### 3.1 Specifications

No Specifications will be produced under the current charter. The group's work is observational and does not define conformance requirements, protocols, or normative standards.

The group may explore whether specific technical artefacts emerging from its work — such as vocabularies, schemas, or measurement methodologies — warrant progression toward standardisation in coordination with relevant W3C groups. Should that need arise, this charter will be amended through the charter amendment process defined below.

### 3.2 Community Group Reports

The group intends to publish the following Community Group Reports:

- **AI Visibility Lifecycle Framework — Community Group Report:** A CG Report mirroring the canonical 11-Stage AI Visibility Lifecycle framework published on Zenodo (DOI: 10.5281/zenodo.18460710). This report is observational and defines no conformance requirements. The canonical source remains the Zenodo deposit under CC BY-NC-ND 4.0.

The group may produce additional Community Group Reports within the scope of this charter, including use cases, measurement methodologies, best practice guides, or white papers.

### 3.3 Test Suites and Other Software

There are no current plans to produce test suites or software. The group may develop tooling in the future if the need arises, subject to charter amendment.

---

## 4. Dependencies and Liaisons

The group anticipates interaction with the following W3C groups and external bodies:

| Group / Organisation | Relationship |
|---|---|
| AI Content Disclosure CG (W3C) | Complementary scope: disclosure addresses what content IS; visibility addresses how content is FOUND by AI systems. |
| IETF | The AI Visibility Lifecycle is registered as IETF Internet-Draft (draft-lynch-ai-visibility-lifecycle). |

---

## 5. Communication

The group will conduct its work primarily through the following channels:

- **Mailing list:** public-ai-web-visibility@w3.org (publicly archived)
- **GitHub repository:** https://github.com/ai-visibility-architects/ai-visibility-lifecycle-cg — Issues and pull requests for technical contributions.
- **Group home page:** https://www.w3.org/community/ai-web-visibility/

The group encourages questions, comments, and issues on its public mailing list and GitHub repository.

Meetings, if held, will be announced to the mailing list with reasonable advance notice. Meeting minutes will be published to the mailing list or GitHub.

---

## 6. Community and Business Group Process

The group operates under the [Community and Business Group Process](https://www.w3.org/community/about/process/). Terms in this Charter that conflict with those of the Community and Business Group Process are void.

As with other Community Groups, W3C seeks organisational licensing commitments under the [W3C Community Contributor License Agreement (CLA)](https://www.w3.org/community/about/process/cla/). When people request to participate without representing their organisation's legal interests, W3C will in general approve those requests for this group with the following understanding: W3C will seek and expect an organisational commitment under the CLA starting with the individual's first request to make a contribution to a group Deliverable.

The [W3C Code of Ethics and Professional Conduct](https://www.w3.org/Consortium/cepc/) applies to participation in this group.

---

## 7. Work Limited to Charter Scope

The group will not publish Specifications on topics other than those listed under Specifications above. See below for how to modify the charter.

---

## 8. Contribution Mechanics

Substantive Contributions to Specifications can only be made by Community Group Participants who have agreed to the [W3C Community Contributor License Agreement (CLA)](https://www.w3.org/community/about/process/cla/).

Specifications created in the Community Group must use the [W3C Software and Document License](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document). All other documents produced by the group should use that License where possible.

All Contributions are made on the group's public mailing list. Community Group participants agree to make all contributions in the GitHub repository the group is using for the particular document. This may be in the form of a pull request (preferred), by raising an issue, or by adding a comment to an existing issue.

All GitHub repositories attached to the Community Group must contain a copy of the CONTRIBUTING and LICENSE files.

---

## 9. Intellectual Property and Licensing Note

The 11-Stage AI Visibility Lifecycle framework is published on Zenodo under CC BY-NC-ND 4.0. The canonical version of the framework remains the Zenodo deposit. The W3C CLA governs only new material created collaboratively within this Community Group. The group may develop complementary work, extensions, or alternative models as separate Community Group Reports.

Any Community Group Report that mirrors the Zenodo publication will include the following notice:

> *This document is NOT the canonical source. The authoritative reference is the Zenodo deposit. In case of discrepancy, Zenodo governs.*

This charter does not transfer any intellectual property rights in the canonical framework. The CLA applies only to contributions made within the W3C Community Group context.

---

## 10. Transparency

The group will conduct all of its technical work in public. If the group uses GitHub, all technical work will occur in its GitHub repositories (and not in mailing list discussions). This is to ensure contributions can be tracked through a software tool.

Meetings may be restricted to Community Group participants, but a public summary or minutes must be posted to the group's public mailing list, or to a GitHub issue if the group uses GitHub.

---

## 11. Decision Process

This group will seek to make decisions where there is consensus. The Chair assesses consensus. Where consensus is not clear, the Chair may issue a Call for Consensus (CfC) to allow multi-day online feedback for a proposed course of action.

To afford asynchronous decisions, any resolution taken in a meeting will be considered provisional. A Call for Consensus will be issued with a response period of no fewer than five working days. If no objections are raised by the end of the response period, the resolution will be considered to have consensus.

If substantial disagreement remains and the group needs to decide an issue to make progress, the Chair will choose an alternative that had substantial support. Individuals who disagree are encouraged to document their objection and, if appropriate, take ownership of an alternative approach.

Any decisions reached at any meeting are tentative and should be recorded on the group's public mailing list or in a GitHub Issue. Any participant may object to a decision within 7 days of publication, provided they include clear reasons for their objection. The Chair will facilitate discussion to try to resolve the objection.

It is the Chair's responsibility to ensure that the decision process is fair, respects the consensus of the CG, and does not unreasonably favour or discriminate against any group participant or their employer.

---

## 12. Chair Selection

Participants in this group choose their Chair(s) and can replace their Chair(s) at any time using whatever means they prefer. However, if 5 participants, no two from the same organisation, call for an election, the group must use the following process to replace any current Chair(s) with a new Chair, consulting the Community Development Lead on election operations (e.g., voting infrastructure and using RFC 2777).

1. Participants announce their candidacies. Participants have 14 days to announce their candidacies, but this period ends as soon as all participants have announced their intentions. If there is only one candidate, that person becomes the Chair. If there are two or more candidates, there is a vote. Otherwise, nothing changes.

2. Participants vote. Participants have 21 days to vote for a single candidate, but this period ends as soon as all participants have voted. The individual who receives the most votes, no two from the same organisation, is elected Chair. In case of a tie, RFC 2777 is used to break the tie. An elected Chair may appoint co-Chairs.

Participants dissatisfied with the outcome of an election may ask the Community Development Lead to intervene. The Community Development Lead, after evaluating the election, may take any action including no action.

---

## 13. Amendments to this Charter

The group can decide to work on a proposed amended charter, editing the text using the Decision Process described above. The decision on whether to adopt the amended charter is made by conducting a 30-day vote on the proposed new charter. The new charter, if approved, takes effect on either the proposed date in the charter itself, or 7 days after the result of the election is announced, whichever is later. A new charter must receive 2/3 of the votes cast in the approval vote to pass. The group may make simple corrections to the charter such as deliverable dates by the simpler group decision process rather than this charter amendment process. The group will use the amendment process for any substantive changes to the goals, scope, deliverables, decision process, or rules for amending the charter.

---

## 14. References

| Reference | URL / Detail |
|---|---|
| Canonical Framework (Zenodo) | Lynch, B. "The 11-Stage AI Visibility Lifecycle." DOI: 10.5281/zenodo.18460710 |
| IETF Internet-Draft | https://datatracker.ietf.org/doc/draft-lynch-ai-visibility-lifecycle/ |
| W3C CG Process | https://www.w3.org/community/about/process/ |
| W3C CLA | https://www.w3.org/community/about/process/cla/ |
| W3C Code of Ethics | https://www.w3.org/Consortium/cepc/ |
| Group Home Page | https://www.w3.org/community/ai-web-visibility/ |

---

*End of Charter*
