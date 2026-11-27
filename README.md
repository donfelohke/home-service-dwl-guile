# home-service-dwl-guile

A GNU Guix Home service for configuring the dwl Wayland compositor with GNU Guile Scheme.

**Maintainer:** Felix Lwova · Don Feloh · [@donfelohke](https://github.com/donfelohke)  
**Ecosystem role:** Supporting WARENA integration project.

This repository packages a Guix Home integration for dwl-guile. It is a supporting configuration/service layer, not a separate desktop distribution, commercial service or practice domain.

## Read before installing

Start with the [Org-mode implementation and installation guide](README.org). It describes the service interface, configuration and upstream relationship.

This repository is a WARENA-maintained fork/integration related to [engstrand-config/home-service-dwl-guile](https://github.com/engstrand-config/home-service-dwl-guile). Preserve upstream attribution and licence obligations. The upstream channel example and fingerprint in the notes refer to upstream; they are not this fork's channel declaration. Do not copy them as this fork's fingerprint or invent a replacement.

Inspect the current source, Guix channel history and package definitions before applying the service to a host.

## Validation requirements

A documentation example is not proof of a successful installation. Before reporting a validated setup, record:

- this repository's exact commit and the upstream base/revision;
- Guix version and channel commits, including the source of every channel fingerprint;
- target system architecture and relevant package revisions;
- Guix evaluation/build result and complete logs;
- generated Home configuration and activation result;
- compositor launch, display/input behavior and Guile configuration outcome;
- rollback and recovery behavior;
- known incompatibilities and untested configurations.

Keep evaluation, build, activation and runtime checks as separate results. A successful Guix evaluation does not establish a working compositor session.

## Relationship to dwl-guile and WARENA

- [dwl-guile](https://github.com/donfelohke/dwl-guile) — the related Guile-configurable compositor project.
- [WARENA](https://github.com/donfelohke/WARENA) — CAPABILITY systems engineering, native-first and libre-first policy, reproducibility and technical provenance.
- [FELOH Corpus](https://github.com/donfelohke/feloh-corpus) — shared identity and evidence governance.

This repository is a supporting WARENA engineering artefact, not a parent project or separate practice. **ONLY NAKEBUSEN TRANSACTS.**

## Documentation and stewardship

- [Implementation guide](README.org).
- [Documentation index](docs/README.md).
- [Configuration provenance](docs/ASSET-AND-CONFIGURATION-PROVENANCE-2026-11-24.md).

Prefer small, reviewable configuration changes. Preserve upstream source identity, document the local delta and keep channel provenance explicit.

---

**WARENA · CAPABILITY · GRIT**  
**Freedom Is a System.**

## Canonical alignment · 27 November 2026

See [WARENA ecosystem alignment](docs/FELOH-WARENA-ECOSYSTEM-ALIGNMENT-2026-11-27.md) for the dated cross-project definitions, evidence boundaries and repository-specific responsibilities.


## African and Black intellectual research

The [FELOH Corpus — THE AFRI-CAN INTELLECTUAL ATLAS](https://github.com/donfelohke/feloh-corpus/blob/research/canonical-synthesis-2026-11-27/docs/THE-AFRI-CAN-INTELLECTUAL-ATLAS-2026-11-27.md) is the shared research index for Africanisms, African philosophies, Black/Africana thought, Pan-African and diasporic movements, and indigenous knowledge. This repository links to that shared taxonomy; its own specialist records remain authoritative for its domain. The atlas is initial research, not a verified dictionary or implementation specification.
