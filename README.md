# Blackmore Technology Group

**Open infrastructure for sovereign digital authority, data rights, continuous provenance and interoperable economic state.**

Our primary open-source project is **[ENTITY](https://github.com/blackmore-technology-group/ENTITY)**.

> **Run it. Verify it. Break it. Implement it independently.**

## Start in 5 minutes

- **Run ENTITY:** [Quick start](https://github.com/blackmore-technology-group/ENTITY#quick-start)
- **Verify the published evidence:** [Engineering evidence](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/ENGINEERING_EVIDENCE.md)
- **Challenge the protocol:** [Interoperability challenge](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/INTEROPERABILITY_CHALLENGE.md)
- **Take a bounded contributor task:** [Open issues](https://github.com/blackmore-technology-group/ENTITY/issues?q=is%3Aissue+is%3Aopen)
- **Read the docs:** [ENTITY-DOCS](https://blackmore-technology-group.github.io/ENTITY-DOCS/)

## What ENTITY is

ENTITY is an open-source protocol and reference implementation for persistent digital identity, delegated authority, provenance, evidence, rights, trusted state transitions, portable recovery and data-economic infrastructure.

Its core primitives are:

**ENTITY · AUTHORITY · RIGHT · EVENT · VALUE**

ENTITY is designed for systems where identity, authority, rights and provenance must survive changes in provider, application, host, device or custody.

**One ENTITY Passport. Many jurisdictions, industries, standards and contexts. No new sovereignty silos.**

## Current release and v3.4.2 freeze

The current published canonical release is **v3.4.1 — Protocol Origin Lineage & Sovereign User Bootstrap**.

The frozen **v3.4.2** candidate is now in release review as [PR #52](https://github.com/blackmore-technology-group/ENTITY/pull/52). It adds the Blackmore Technology Data Universe (BTDU) and canonical-protocol protection while preserving sovereign user ownership and a zero automatic protocol royalty.

Current v3.4.2 qualification recorded in the release PR includes:

- **203/203** final regression PASS
- **26-vector** Global Passport verifier PASS
- final BTDU verification: **4,927 objects · 37,628 atoms · 38,278 bonds · 19,681 compounds**
- destructive torn-journal recovery: **PASS**
- protected-state recovery: **PASS**
- canonical lineage preserved: **Shawn Blackmore → Blackmore Technology Group → ENTITY**
- `automatic_protocol_royalty_bps = 0`

The release remains intentionally fail-closed: post-freeze evidence may be added, but release-critical v3.4.2 artifacts are not rewritten after freeze.

## Blackmore Technology Data Universe

BTDU is ENTITY's bonded/atomic data architecture. Instead of treating every semantic relationship as a large duplicated representation, BTDU represents reusable information atoms, bonds and compounds and connects them to ENTITY's authority, provenance, rights and economic state.

The project is qualifying BTDU as a real-world knowledge/data substrate, not as a generic raw-file compression claim.

## Public cross-language reproducibility

BTG publishes controlled native implementations so developers can inspect and challenge cross-language reproducibility:

- [Rust](https://github.com/blackmore-technology-group/ENTITY-RUST-CLEANROOM)
- [TypeScript](https://github.com/blackmore-technology-group/ENTITY-TYPESCRIPT-CLEANROOM)
- [C# / .NET](https://github.com/blackmore-technology-group/ENTITY-CSHARP-CLEANROOM)
- [Go](https://github.com/blackmore-technology-group/ENTITY-GO-CLEANROOM)
- [Swift](https://github.com/blackmore-technology-group/ENTITY-SWIFT-CLEANROOM)
- [Java](https://github.com/blackmore-technology-group/ENTITY-JAVA-CLEANROOM)

These repositories are **BTG-controlled reproducibility evidence, not independent third-party validation**. The stronger milestone is an unrelated implementation built from the public specifications and sealed conformance material.

## Domain entry points

The same Global Passport architecture is packaged for:

- [Healthcare](https://github.com/blackmore-technology-group/ENTITY-HEALTHCARE)
- [Finance](https://github.com/blackmore-technology-group/ENTITY-FINANCE)
- [Manufacturing](https://github.com/blackmore-technology-group/ENTITY-MANUFACTURING)
- [AI](https://github.com/blackmore-technology-group/ENTITY-AI)
- [Robotics](https://github.com/blackmore-technology-group/ENTITY-ROBOTICS)
- [Defence / public-unclassified](https://github.com/blackmore-technology-group/ENTITY-DEFENCE)

Each package configures the **same ENTITY Global Passport**. They do not create separate sovereignty systems and do not redefine external standards.

## Developer challenge

You do not need to understand the entire protocol to contribute. Useful first contributions include:

- reproduce a sealed vector campaign;
- run the kit on a new platform;
- find a documentation or portability failure;
- challenge a security boundary;
- identify an ambiguous rule;
- build a narrow independent classifier;
- produce a counterexample that forces the protocol or documentation to improve.

A reproducible failure is useful evidence.

---

**Blackmore Technology Group Limited**  
Primary project: [ENTITY](https://github.com/blackmore-technology-group/ENTITY)  
Documentation: [ENTITY-DOCS](https://blackmore-technology-group.github.io/ENTITY-DOCS/)  
License: ENTITY is published under the Apache License 2.0.
