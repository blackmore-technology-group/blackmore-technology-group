# Blackmore Technology Group

**Open systems engineering for sovereign digital authority, verifiable information, data rights and interoperability.**

Blackmore Technology Group develops open infrastructure intended to let people, organizations, applications and digital systems preserve identity, authority, rights, evidence and economic state without making a cloud provider, registrar, resolver, storage operator or platform vendor sovereign merely because it operates infrastructure.

Our primary open-source project is **ENTITY**.

## ENTITY

[**ENTITY**](https://github.com/blackmore-technology-group/ENTITY) is a provider-independent protocol and reference implementation for persistent digital identity, delegated authority, provenance, evidence, data rights, portable recovery and rights-bearing economic state.

Its core primitives are:

**ENTITY · AUTHORITY · RIGHT · EVENT · VALUE**

The current protected public release is **v3.3.0 - Verifiable Reality, Evidence and Economic Causality**.

v3.3 adds a formal distinction between cryptographic verification, protocol verification and evidence supporting claims about the external world. It preserves the v3.2 Rights Passport/adoption layer and the existing ENTITY market lifecycle.

> **ENTITY does not make reality indisputable. It makes claims about reality attributable, evidentiary, contestable, machine-verifiable and economically traceable.**

### Current v3.3 engineering evidence

- protected release commit: `9c79f987207592cb6791e1a8956f23351cdfb2d3`;
- complete regression: **144/144 PASS**;
- targeted v3.3 suite: **16/16 PASS**;
- sealed v3.3 reality vectors: **20/20 PASS** (10 valid / 10 invalid);
- canonical sealed kit SHA-256: `f8b39ee01fb7346f33a57530e925b545d2bf9a770c7ec60724e28a4971d55a46`;
- deterministic result SHA-256: `82bd1f1fb328edd37a26d8ea60ede5a599c7d9af5027bffd73b9e52843b5a51d`;
- protected GitHub checks and CodeQL: **PASS**.

### Developer & research portal

The public engineering program now separates project navigation, governance, release discipline, technical publications, interoperability evidence and security review into explicit surfaces:

- [Developer Portal](https://github.com/blackmore-technology-group/ENTITY/blob/main/DEVELOPERS.md) — start by objective: reproduce, review, contribute, implement or test interoperability.
- [Engineering Evidence](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/ENGINEERING_EVIDENCE.md) — public evidence hierarchy and claim boundaries.
- [Open-Source Governance](https://github.com/blackmore-technology-group/ENTITY/blob/main/GOVERNANCE.md) — stewardship, decision classes, protocol governance and maintainer boundaries.
- [Release Policy](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/governance/RELEASE_POLICY.md) — evidence-gated release discipline and historical-integrity rules.
- [Architecture & ADRs](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/architecture/README.md) — durable architecture decisions and change-control boundaries.
- [Technical Papers](https://github.com/blackmore-technology-group/ENTITY/tree/main/docs/papers) — public engineering notes separated from normative protocol material.
- [Interoperability Status](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/interoperability/STATUS.md) — controlled baselines and the live external milestone scoreboard.
- [Independent Security Review Program](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/security/INDEPENDENT_SECURITY_REVIEW_PROGRAM.md) — scoped pathway for external security review.
- [Contributor Recognition](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/community/CONTRIBUTOR_RECOGNITION.md) — factual recognition without overstating endorsement or validation.

### Start with the engineering

- [ENTITY repository](https://github.com/blackmore-technology-group/ENTITY)
- [ENTITY v3.3.0 release](https://github.com/blackmore-technology-group/ENTITY/releases/tag/v3.3.0)
- [v3.3 engineering launch discussion](https://github.com/blackmore-technology-group/ENTITY/discussions/34)
- [Start Here](https://github.com/blackmore-technology-group/ENTITY/blob/main/START_HERE.md)
- [Interoperability Challenge](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/INTEROPERABILITY_CHALLENGE.md)
- [Contributing](https://github.com/blackmore-technology-group/ENTITY/blob/main/CONTRIBUTING.md)
- [Security](https://github.com/blackmore-technology-group/ENTITY/blob/main/SECURITY.md)

### Pick a bounded contributor task

You do not need to understand or implement the whole protocol to contribute.

- [Verify the v3.3 sealed reality kit on Linux](https://github.com/blackmore-technology-group/ENTITY/issues/20) — portability / reproducibility.
- [Verify the v3.3 sealed reality kit on macOS](https://github.com/blackmore-technology-group/ENTITY/issues/21) — portability / reproducibility.
- [Add a minimal Evidence Object and claim-transition example](https://github.com/blackmore-technology-group/ENTITY/issues/22) — small documentation/code example.
- [Audit the Start Here path from a fresh clone](https://github.com/blackmore-technology-group/ENTITY/issues/26) — onboarding usability.
- [Build a narrow independent v3.3 reality-vector classifier](https://github.com/blackmore-technology-group/ENTITY/issues/27) — clean-room interoperability evidence.

A reproducible failure, counterexample or specification ambiguity is a useful result.

## Independent implementation is the next major milestone

BTG maintains controlled native ENTITY baselines in **Rust, TypeScript, C#, Go, Swift and Java**. These are useful cross-language reproducibility evidence, but we do **not** describe BTG-controlled implementations as independent third-party validation.

The external challenge is stronger:

> **Can an unrelated engineer or organization reproduce ENTITY semantics from public specifications and sealed test material without using BTG implementation code?**

The frozen [ENTITY Protocol 1.0 External Conformance Kit](https://github.com/blackmore-technology-group/ENTITY-Protocol-1.0-Conformance-Kit) provides a bounded clean-room starting point.

You do not need to implement the entire protocol to contribute. Reproducing a test, finding an ambiguity, breaking a vector assumption, reviewing a schema, improving portability or building a narrow independent subset is useful work.

## Public implementation repositories

BTG-controlled cross-language repositories are published so their engineering can be inspected:

- [Rust](https://github.com/blackmore-technology-group/ENTITY-RUST-CLEANROOM)
- [TypeScript](https://github.com/blackmore-technology-group/ENTITY-TYPESCRIPT-CLEANROOM)
- [C# / .NET](https://github.com/blackmore-technology-group/ENTITY-CSHARP-CLEANROOM)
- [Go](https://github.com/blackmore-technology-group/ENTITY-GO-CLEANROOM)
- [Swift](https://github.com/blackmore-technology-group/ENTITY-SWIFT-CLEANROOM)
- [Java](https://github.com/blackmore-technology-group/ENTITY-JAVA-CLEANROOM)

These repositories are **controlled qualification baselines**, not independent external implementations.

## Engineering principles

We try to make important boundaries explicit rather than hide them behind broad claims:

- registration is not ownership;
- provenance is not truth;
- a valid signature is not objective external truth;
- custody and hosting are not sovereign authority;
- external evidence sources do not silently become protocol authority;
- data bytes need not be artificially scarce for rights to be economically scarce;
- historical signed state is superseded rather than silently rewritten;
- internal qualification is not the same as independent external validation.

## Contributing

If you are evaluating ENTITY, criticism backed by a reproduction, counterexample, failing vector or ambiguous rule is welcome.

Start with the [Developer Portal](https://github.com/blackmore-technology-group/ENTITY/blob/main/DEVELOPERS.md), the [contribution guide](https://github.com/blackmore-technology-group/ENTITY/blob/main/CONTRIBUTING.md), the [interoperability challenge](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/INTEROPERABILITY_CHALLENGE.md), or [Discussion #34](https://github.com/blackmore-technology-group/ENTITY/discussions/34).

Large protocol implementations are not expected as a first contribution. Small, independently owned tasks are deliberately part of the contributor path.

---

**Blackmore Technology Group Limited**  
Primary project: [ENTITY](https://github.com/blackmore-technology-group/ENTITY)  
Developer portal: [ENTITY Developers](https://github.com/blackmore-technology-group/ENTITY/blob/main/DEVELOPERS.md)  
License: ENTITY is published under Apache License 2.0.