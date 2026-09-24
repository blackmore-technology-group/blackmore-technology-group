# Blackmore Technology Group

**Open systems engineering for sovereign digital authority, verifiable information, data rights and interoperability.**

Blackmore Technology Group develops open infrastructure intended to let people, organizations, applications and digital systems preserve identity, authority, rights, evidence and economic state without making a cloud provider, registrar, resolver, storage operator or platform vendor sovereign merely because it operates infrastructure.

Our primary open-source project is **ENTITY**.

## ENTITY

[**ENTITY**](https://github.com/blackmore-technology-group/ENTITY) is a provider-independent protocol and reference implementation for persistent digital identity, delegated authority, provenance, evidence, data rights, portable recovery and rights-bearing economic state.

Its core primitives are:

**ENTITY · AUTHORITY · RIGHT · EVENT · VALUE**

The current protected public release is **v3.2.0 — Adoption Layer and Rights Passport Infrastructure**.

**v3.3 — Verifiable Reality, Evidence and Economic Causality** is in protected release qualification. It adds a formal distinction between cryptographic verification, protocol verification and evidence supporting claims about the external world.

> **ENTITY does not make reality indisputable. It makes claims about reality attributable, evidentiary, contestable, machine-verifiable and economically traceable.**

### Start with the engineering

- [ENTITY repository](https://github.com/blackmore-technology-group/ENTITY)
- [Start Here](https://github.com/blackmore-technology-group/ENTITY/blob/entity-v3.3.0-development/START_HERE.md)
- [Engineering Evidence](https://github.com/blackmore-technology-group/ENTITY/blob/entity-v3.3.0-development/docs/ENGINEERING_EVIDENCE.md)
- [Interoperability Challenge](https://github.com/blackmore-technology-group/ENTITY/blob/entity-v3.3.0-development/docs/INTEROPERABILITY_CHALLENGE.md)
- [Releases](https://github.com/blackmore-technology-group/ENTITY/releases)
- [Security](https://github.com/blackmore-technology-group/ENTITY/blob/main/SECURITY.md)

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

Start with the [contribution guide](https://github.com/blackmore-technology-group/ENTITY/blob/entity-v3.3.0-development/CONTRIBUTING.md) or the [interoperability challenge](https://github.com/blackmore-technology-group/ENTITY/blob/entity-v3.3.0-development/docs/INTEROPERABILITY_CHALLENGE.md).

Large protocol implementations are not expected as a first contribution. Small, independently owned tasks are deliberately part of the contributor path.

---

**Blackmore Technology Group Limited**  
Primary project: [ENTITY](https://github.com/blackmore-technology-group/ENTITY)  
License: ENTITY is published under Apache License 2.0.
