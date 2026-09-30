# Blackmore Technology Group

### Open infrastructure for sovereign digital authority, verifiable provenance, data rights and interoperable economic state.

Our primary open-source project is **[ENTITY](https://github.com/blackmore-technology-group/ENTITY)** — an Apache-2.0 protocol and reference implementation for persistent identity, delegated authority, evidence, rights, portable recovery and data-economic infrastructure.

> **Build it. Verify it. Break it. Implement it independently.**

[**ENTITY v3.4.3**](https://github.com/blackmore-technology-group/ENTITY/releases/tag/v3.4.3) · [**5-minute developer paths**](https://github.com/blackmore-technology-group/ENTITY#developer-entry-points) · [**Good first issues**](https://github.com/blackmore-technology-group/ENTITY/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) · [**Discussions**](https://github.com/blackmore-technology-group/ENTITY/discussions) · [**Documentation**](https://blackmore-technology-group.github.io/ENTITY-DOCS/) · [**Protocol 1.0 Conformance Kit**](https://github.com/blackmore-technology-group/ENTITY-Protocol-1.0-Conformance-Kit)

---

## Start by building, not reading everything

You do **not** need to understand the entire ENTITY architecture before contributing.

Choose one path:

### 1. Build something in 5–30 minutes

- Create and verify an ENTITY provenance receipt.
- Build a tiny TypeScript or Python verifier.
- Turn a JSON event into an ENTITY evidence object.
- Add a GitHub Action that verifies an ENTITY receipt.
- Visualize a small lineage chain.

**Start here:** [open buildable good-first issues](https://github.com/blackmore-technology-group/ENTITY/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)

### 2. Reproduce a real engineering case

ENTITY is being exercised against real open-source engineering work. BTG contributions have already been merged upstream in projects including:

- [Memnox PR #86](https://github.com/Memnox/memnox/pull/86) — policy/time-window validation hardening.
- [Vector PR #26504](https://github.com/vectordotdev/vector/pull/26504) — ambiguous test-output failures converted from a panic into a normal configuration error.

The purpose is not to claim ownership of third-party code. The purpose is to make authorship, evidence, lineage, rights boundaries and later economic state reproducible.

### 3. Challenge ENTITY itself

- [15-minute first-run audit](https://github.com/blackmore-technology-group/ENTITY/issues/80)
- [External Verification Challenge](https://github.com/blackmore-technology-group/ENTITY/issues/55)
- [External Repository Qualification campaign](https://github.com/blackmore-technology-group/ENTITY/issues/78)
- [Interoperability Challenge](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/INTEROPERABILITY_CHALLENGE.md)

A reproducible failure, ambiguity, counterexample or portability problem is useful evidence.

---

## What ENTITY is trying to solve

```text
IDENTITY → AUTHORITY → RIGHT → EVENT → EVIDENCE → VALUE
```

ENTITY keeps several relationships separate that are often collapsed together:

- identity vs account;
- provenance vs truth;
- custody vs ownership;
- a valid signature vs an externally true claim;
- protocol origin vs ownership of downstream assets;
- usage vs realized economic value.

The current supported runtime is **ENTITY v3.4.3**. The **Blackmore Technology Data Universe (BTDU)** component remains version **3.4.2 unchanged** inside that release.

---

## Six public cross-language baselines

BTG publishes controlled reproducibility baselines in:

[Rust](https://github.com/blackmore-technology-group/ENTITY-RUST-CLEANROOM) · [TypeScript](https://github.com/blackmore-technology-group/ENTITY-TYPESCRIPT-CLEANROOM) · [C# / .NET](https://github.com/blackmore-technology-group/ENTITY-CSHARP-CLEANROOM) · [Go](https://github.com/blackmore-technology-group/ENTITY-GO-CLEANROOM) · [Swift](https://github.com/blackmore-technology-group/ENTITY-SWIFT-CLEANROOM) · [Java](https://github.com/blackmore-technology-group/ENTITY-JAVA-CLEANROOM)

These are BTG-controlled reproducibility baselines, **not independent third-party implementations**. The stronger interoperability milestone is an implementation independently authored and controlled by an unrelated engineer or organization from the public protocol and sealed conformance material.

---

## Join the developer conversation

Use [GitHub Discussions](https://github.com/blackmore-technology-group/ENTITY/discussions) for design questions, implementation ideas, evaluation results and show-and-tell work. Use Issues for reproducible defects and bounded tasks. Use Pull Requests for reviewable changes.

**Blackmore Technology Group Limited**  
Primary project: [ENTITY](https://github.com/blackmore-technology-group/ENTITY)  
Current runtime: [ENTITY v3.4.3](https://github.com/blackmore-technology-group/ENTITY/releases/tag/v3.4.3)  
License: Apache License 2.0
