# Blackmore Technology Group

### Open infrastructure for sovereign digital authority, data rights, continuous provenance and interoperable economic state.

Our primary open-source project is **[ENTITY](https://github.com/blackmore-technology-group/ENTITY)** — an open protocol and reference implementation for persistent identity, delegated authority, provenance, evidence, rights, portable recovery and data-economic infrastructure.

> **Run it. Verify it. Break it. Implement it independently.**

[**Explore ENTITY v3.4.2 + BTDU**](https://blackmore-technology-group.github.io/ENTITY-DOCS/v342/) · [**Source**](https://github.com/blackmore-technology-group/ENTITY) · [**Conformance Kit**](https://github.com/blackmore-technology-group/ENTITY-Protocol-1.0-Conformance-Kit) · [**Contributor Tasks**](https://github.com/blackmore-technology-group/ENTITY/issues) · [**Documentation**](https://blackmore-technology-group.github.io/ENTITY-DOCS/)

---

## ENTITY v3.4.2 — release candidate

The v3.4.2 candidate brings together four parts of the architecture that are usually separate:

1. **Sovereign digital authority** — persistent identity, delegated authority, rights and recovery that are not created merely by hosting or possession.
2. **Blackmore Technology Data Universe (BTDU)** — an atomic/bonded data architecture built from reusable atoms, bonds and compounds, connected to ENTITY provenance and governance.
3. **Data-rights economics** — Digital Commodity Objects (DCOs), rights instruments, price discovery, settlement, usage, derivatives and explicit originator participation without a required protocol token.
4. **Canonical protocol protection** — canonical ENTITY preserves the verified **Shawn Blackmore → Blackmore Technology Group → ENTITY** origin lineage while forks remain free to operate as derivatives.

The current candidate is under protected release review in **[ENTITY PR #52](https://github.com/blackmore-technology-group/ENTITY/pull/52)**. The security-remediated candidate head is `e8ba17a9d09a357d40e3c1e89bacb11454b708ff`. Until the protected merge, signed tag and release complete, **v3.4.1 remains the published canonical release**.

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

The current v3.4.2 candidate has been re-ingested into BTDU after the dependency remediation, with **1,812 tracked repository files** in the latest candidate snapshot. The public developer preview explains the architecture and the exact claim boundaries:

**[ENTITY v3.4.2 + Blackmore Technology Data Universe developer preview →](https://blackmore-technology-group.github.io/ENTITY-DOCS/v342/)**

---

## Start in five minutes

**Run the published reference implementation**

```bash
git clone https://github.com/blackmore-technology-group/ENTITY.git
cd ENTITY
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

BTG publishes controlled reproducibility baselines so developers can inspect the same protocol surface in multiple implementation languages:

- [Rust](https://github.com/blackmore-technology-group/ENTITY-RUST-CLEANROOM)
- [TypeScript](https://github.com/blackmore-technology-group/ENTITY-TYPESCRIPT-CLEANROOM)
- [C# / .NET](https://github.com/blackmore-technology-group/ENTITY-CSHARP-CLEANROOM)
- [Go](https://github.com/blackmore-technology-group/ENTITY-GO-CLEANROOM)
- [Swift](https://github.com/blackmore-technology-group/ENTITY-SWIFT-CLEANROOM)
- [Java](https://github.com/blackmore-technology-group/ENTITY-JAVA-CLEANROOM)

These are **BTG-controlled reproducibility evidence, not unrelated third-party validation**. The stronger milestone is an implementation authored and controlled by an unrelated engineer or organization from the public specifications and sealed conformance material.

---

## Domain entry points

The same Global Passport architecture is packaged for:

[Healthcare](https://github.com/blackmore-technology-group/ENTITY-HEALTHCARE) · [Finance](https://github.com/blackmore-technology-group/ENTITY-FINANCE) · [Manufacturing](https://github.com/blackmore-technology-group/ENTITY-MANUFACTURING) · [AI](https://github.com/blackmore-technology-group/ENTITY-AI) · [Robotics](https://github.com/blackmore-technology-group/ENTITY-ROBOTICS) · [Defence / Public-Unclassified](https://github.com/blackmore-technology-group/ENTITY-DEFENCE)

Each package configures the same ENTITY sovereignty model; the packages do not create separate sovereignty systems or redefine external standards.

---

## Important boundaries

ENTITY intentionally separates:

- identity from an account;
- authority from possession or hosting;
- provenance from objective truth;
- protocol origin from ownership of downstream user assets;
- cryptographic verification from legal or regulatory conclusions;
- market evidence from automatic accounting fair value.

Canonical protocol origin does **not** create an automatic BTG royalty. Economic participation requires explicit terms.

---

**Blackmore Technology Group Limited**  
Primary project: [ENTITY](https://github.com/blackmore-technology-group/ENTITY)  
Developer preview: [ENTITY v3.4.2 + BTDU](https://blackmore-technology-group.github.io/ENTITY-DOCS/v342/)  
Documentation: [ENTITY-DOCS](https://blackmore-technology-group.github.io/ENTITY-DOCS/)  
License: ENTITY is published under the Apache License 2.0.
