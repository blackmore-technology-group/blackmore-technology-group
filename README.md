# Blackmore Technology Group

### Open infrastructure for sovereign digital authority, data rights, continuous provenance and interoperable economic state.

Our primary open-source project is **[ENTITY](https://github.com/blackmore-technology-group/ENTITY)** — an open protocol and reference implementation for persistent identity, delegated authority, provenance, evidence, rights, portable recovery and data-economic infrastructure.

> **Run it. Verify it. Break it. Implement it independently.**

[**ENTITY v3.4.2 Release**](https://github.com/blackmore-technology-group/ENTITY/releases/tag/v3.4.2) · [**Explore v3.4.2 + BTDU**](https://blackmore-technology-group.github.io/ENTITY-DOCS/v342/) · [**Source**](https://github.com/blackmore-technology-group/ENTITY) · [**Conformance Kit**](https://github.com/blackmore-technology-group/ENTITY-Protocol-1.0-Conformance-Kit) · [**Contributor Tasks**](https://github.com/blackmore-technology-group/ENTITY/issues) · [**Documentation**](https://blackmore-technology-group.github.io/ENTITY-DOCS/)

---

## ENTITY v3.4.2 — Canonical BTDU Release

**ENTITY v3.4.2 is the sole current supported canonical ENTITY release.**

It brings together four parts of the architecture that are usually separate:

1. **Sovereign digital authority** — persistent identity, delegated authority, rights and recovery that are not created merely by hosting or possession.
2. **Blackmore Technology Data Universe (BTDU)** — an atomic/bonded data architecture built from reusable atoms, bonds and compounds, connected to ENTITY provenance and governance.
3. **Data-rights economics** — Digital Commodity Objects (DCOs), rights instruments, price discovery, settlement, usage, derivatives and explicit originator participation without a required protocol token.
4. **Canonical protocol protection** — canonical ENTITY preserves the verified **Shawn Blackmore → Blackmore Technology Group → ENTITY → v3.4.2** lineage while forks remain free to operate as derivatives.

### Published qualification

- **203/203** regression PASS
- **3/3** repository safety PASS
- GitHub dependency review **PASS**
- Public conformance smoke **PASS**
- Protected-state recovery **PASS**
- Exact restore **true**
- Restored sovereign signing **true**
- v3.4.1 origin continuity **true**

Protected release commit: `6dfa3d6cc738d9369cf092d2782676bf4f2a46e4`  
Release tree: `f90bf74e29899f82d0a4ee321604346241bba4de`  
Release-origin attestation SHA-256: `0ba4b0cc8c34688d98ef3c3425fbd70ff5b59d26183a18a15506bbad3adea0c1`

Earlier ENTITY releases remain immutable historical provenance and are superseded for current deployment and conformance purposes.

### The protocol in one line

```text
ENTITY → AUTHORITY → RIGHT → EVENT → VALUE
```

### The data-rights lifecycle

```text
DCO → Instrument → Listing → Disclosure → Order / RFQ / Auction
    → Price Discovery → Trade → Clearing → Settlement → Entitlement
    → Usage → Derived Output → Economic Consequence
```

---

## Why developers may care about BTDU

BTDU is not presented as generic raw-file compression. It is a different way to represent and connect information: reusable atomic primitives can form relationships and higher-order compounds while ENTITY preserves the authority, provenance, rights and economic boundaries that matter.

**[Explore ENTITY v3.4.2 + Blackmore Technology Data Universe →](https://blackmore-technology-group.github.io/ENTITY-DOCS/v342/)**

---

## Start in five minutes

```bash
git clone https://github.com/blackmore-technology-group/ENTITY.git
cd ENTITY
git checkout v3.4.2
python -m pip install -r requirements.txt
python -m compileall -q src sdk protocol
python -m unittest discover -s tests -v
```

Then choose what you want to challenge:

- [Audit the Start Here path from a clean clone](https://github.com/blackmore-technology-group/ENTITY/issues/26)
- [Reproduce the Rust vector campaign on Linux](https://github.com/blackmore-technology-group/ENTITY/issues/48)
- [Try a domain package from a clean clone](https://github.com/blackmore-technology-group/ENTITY/issues/46)
- [Read the independent interoperability challenge](https://github.com/blackmore-technology-group/ENTITY/blob/main/docs/INTEROPERABILITY_CHALLENGE.md)

A reproducible failure, ambiguity, counterexample or portability problem is useful evidence.

---

## Six public language baselines

BTG publishes controlled reproducibility baselines in:

[Rust](https://github.com/blackmore-technology-group/ENTITY-RUST-CLEANROOM) · [TypeScript](https://github.com/blackmore-technology-group/ENTITY-TYPESCRIPT-CLEANROOM) · [C# / .NET](https://github.com/blackmore-technology-group/ENTITY-CSHARP-CLEANROOM) · [Go](https://github.com/blackmore-technology-group/ENTITY-GO-CLEANROOM) · [Swift](https://github.com/blackmore-technology-group/ENTITY-SWIFT-CLEANROOM) · [Java](https://github.com/blackmore-technology-group/ENTITY-JAVA-CLEANROOM)

These are **BTG-controlled reproducibility evidence, not unrelated third-party validation**. The stronger milestone remains an implementation authored and controlled by an unrelated engineer or organization from public specifications and sealed conformance material.

---

## Domain entry points

[Healthcare](https://github.com/blackmore-technology-group/ENTITY-HEALTHCARE) · [Finance](https://github.com/blackmore-technology-group/ENTITY-FINANCE) · [Manufacturing](https://github.com/blackmore-technology-group/ENTITY-MANUFACTURING) · [AI](https://github.com/blackmore-technology-group/ENTITY-AI) · [Robotics](https://github.com/blackmore-technology-group/ENTITY-ROBOTICS) · [Defence / Public-Unclassified](https://github.com/blackmore-technology-group/ENTITY-DEFENCE)

Each package configures the same ENTITY sovereignty model; the packages do not create separate sovereignty systems or redefine external standards.

---

## Post-release qualification still open

v3.4.2 does **not** claim completion of the external ADAM promotion gates including `RUST_COMPILED_QUALIFIED`, `REAL_WORLD_TRAINING`, hardware-backed key custody, physical multi-host qualification, certified-device pilot, 30-day wall-clock operation, independent security audit or independent assessor receipt. Those remain post-release qualification work.

ENTITY also intentionally separates identity from accounts, authority from possession or hosting, provenance from objective truth, protocol origin from ownership of downstream user assets, cryptographic verification from legal conclusions, and market evidence from automatic accounting fair value.

Canonical protocol origin does **not** create an automatic BTG royalty. Economic participation requires explicit terms.

---

**Blackmore Technology Group Limited**  
Primary project: [ENTITY](https://github.com/blackmore-technology-group/ENTITY)  
Current release: [ENTITY v3.4.2](https://github.com/blackmore-technology-group/ENTITY/releases/tag/v3.4.2)  
Documentation: [ENTITY-DOCS](https://blackmore-technology-group.github.io/ENTITY-DOCS/)  
License: Apache License 2.0.
