# Responsibility Infrastructure® — Canonical GitHub Reference

**Status date:** 2026-10-30  
**Canonical institutional source:** https://responsibilityinfrastructure.com/  
**Current positioning record:** https://responsibilityinfrastructure.com/current-position.json

> Responsibility Infrastructure is an architecture for making responsibility explicit, provable and usable across organisational and system boundaries. The Responsibility Infrastructure Standard and Responsibility Infrastructure Protocol address the wider normative and protocol architecture. A separately defined proposed public interoperability layer consists of the Responsibility Interoperability Standard and Responsibility Interoperability Protocol, which define the minimum common semantics and exchange requirements needed for independent systems to interoperate without adopting a common vendor stack.

**AI assurance is one application of Responsibility Infrastructure; Responsibility Infrastructure is not limited to AI.**

This is a deliberately bounded public reference surface. It does not publish the private Responsibility Infrastructure source repository, Responsibility Rail internals, commercial implementation logic, private schemas, security controls, evaluation logic or other implementation-replicating material that is not required for public interoperability.

## Architecture map

| Layer | Public role | Canonical source |
|---|---|---|
| Responsibility Infrastructure Standard | Wider normative architecture | https://responsibilityinfrastructure.com/standards |
| Responsibility Infrastructure Protocol | Wider protocol architecture | https://responsibilityinfrastructure.com/protocol |
| Responsibility Interoperability Standard | Proposed public semantic interoperability boundary | https://responsibilityinfrastructure.com/responsibility-interoperability-standard |
| Responsibility Interoperability Protocol | Proposed public cross-boundary exchange behaviour | https://responsibilityinfrastructure.com/responsibility-interoperability-protocol |
| Verification | Determines what available responsibility evidence supports | https://responsibilityinfrastructure.com/current-status |
| Recognition | Determines effect within an applicable recognition regime | https://responsibilityinfrastructure.com/current-status |
| Registry | Preserves and publishes recognised standing and history | https://responsibilityinfrastructure.com/registry |
| Resolution | Determines which current standing corresponds to a reliance request | https://responsibilityinfrastructure.com/current-status |
| Reliance | External use of resolved standing within the relying party's own authority | https://responsibilityinfrastructure.com/current-status |

These functions are distinct. Conformance, Verification, Recognition, Registry standing and external reliance must not be collapsed into one claim.

## Current status

The current public position is maintained at:

- https://responsibilityinfrastructure.com/current-status
- https://responsibilityinfrastructure.com/current-position.json

Five completed bounded external-system tests are currently identified in the canonical status record: RI-INTEROP-ELYDORA-001, RI-INTEROP-GHOSTDRIFT-001, RI-INTEROP-ARM-001, RI-INTEROP-TRAIL-001 and RI-INTEROP-TAP-001.

Under their stated test conditions, the five tests report Representability PASS and Receiver Independence PASS; Responsibility Completeness remained PARTIAL; overall results remained PARTIAL; full RI conformance was NOT ESTABLISHED.

Canonical evidence register:

- https://responsibilityinfrastructure.com/interop
- https://github.com/La-Touche-Infrastructure-Ltd/Responsibility-Interoperability-Records

These records do not establish universal interoperability, certification, regulatory approval, Recognition, Registry standing, endorsement or adoption by the named source systems.

## Public interoperability boundary

The proposed public interoperability layer is the Responsibility Interoperability Standard and Responsibility Interoperability Protocol.

Its purpose is to define the minimum common semantics and exchange behaviour required for independent systems to preserve responsibility meaning without adopting a common vendor stack.

Schemas, reference code, validators, fixtures or conformance tests belong on the public interoperability surface only where an identified publication expressly releases them under its stated licence or permitted-use terms. This reference does not expose or imply a licence to non-public artefacts.

## Standard versus implementation

A product, open-source project, vendor protocol or sector-specific system may implement an applicable public interoperability publication without becoming the normative source for Responsibility Infrastructure.

La Touche is a commercial implementation organisation. Its private implementation technology and commercial services are not the public interoperability specification.

Company implementation surface:

- https://latouche.ai/

## Research and citation

**Preferred research publication**

Raphael A. La Touche, *AI Governance Is Not Enough to Prove Responsibility: A Conceptual and Testable Architecture for Demonstrable Responsibility in AI Systems*, version 1.0 (2026), Responsibility Infrastructure Publications.

- Canonical publication: https://responsibilityinfrastructure.com/publications/ai-governance-is-not-enough
- DOI: https://doi.org/10.5281/zenodo.21848724

Machine-readable citation metadata for this reference is in [RI-CITATION.json](./RI-CITATION.json).

## Public research records

- Responsibility Interoperability Records: https://github.com/La-Touche-Infrastructure-Ltd/Responsibility-Interoperability-Records
- Prior-run evidence study: https://github.com/La-Touche-Infrastructure-Ltd/prior-run-evidence-v01
- Research programme: https://responsibilityinfrastructure.com/research

## Claim boundary

Public availability is not certification. A bounded test is not universal validation. An implementation is not automatically conformant. Registration of a record is not the same as Recognition or Registry standing. Published RI material does not replace statutory, contractual, professional or regulatory authority.

Responsibility Infrastructure® is a registered UK trade mark of LA TOUCHE HOLDINGS LTD. Third-party rights remain with their respective owners.
