# Changelog

Documentation changelog for IRL Engine public docs.
Follows [Semantic Versioning](https://semver.org/) in sync with the IRL Engine release cycle.

---

## [2.0.0] — 2026-10-05

### Changed
- **IRL is free.** Per-agent pricing and paid editions are withdrawn; `pricing.md` is now
  "Free & open" (FSL-1.1-ALv2 engine, MIT gateway, SDKs and verifier).
- **Whitepaper v5.0** (synced from the engine): standalone `MTA_MODE=none`, asset and venue
  mandates, Layer 2 v2 regime binding, licensing, corrected roadmap, and a new section on the
  IRL Gateway (MCP).
- Getting started and developer guide replaced with the engine's maintained versions.
- The service-levels page no longer promises uptime credits for a paid service that doesn't exist.
- All repository links moved to the `macropulse-lab` organisation; the public engine is
  [macropulse-lab/irl](https://github.com/macropulse-lab/irl) (`IRL-engine-AX` is retired).
- README: licence badge corrected to CC BY-SA 4.0 (the actual licence of these docs); the
  ecosystem table adds irl-gateway and irl-verify and no longer links a private repository.

---

## [1.2.0] — 2026-04-14

### Added
- TypeScript SDK documentation and quick-start examples
- `MTA_MODE=none` configuration guide in getting-started.md
- Shadow mode usage and evaluation guide in developer-guide.md
- Evidence export workflow for CFTC/SEC audit package generation

### Updated
- Getting started guide updated for Docker standalone (no MacroPulse account required for local dev)
- Developer guide expanded with full bindExecution() examples in Python and TypeScript
- Compliance guide updated with EU AI Act Article 9 mapping

---

## [1.1.0] — 2026-03-15

### Added
- Layer 2 documentation: heartbeat mechanism, mta_ref verification, anti-replay sequence IDs
- Python SDK documentation (pip install irl-sdk)
- Merkle anchoring explainer in whitepaper.md
- GDPR data deletion guide
- Exchange integration guide: FIX protocol tags, REST order metadata, venue-specific notes
- Operations guide: incident response runbook, SLA, performance benchmarks
- Architecture diagrams (Mermaid source + PNG)

---

## [1.0.0] — 2026-02-01

### Added
- Initial public documentation release
- Whitepaper: full IRL protocol specification, cryptographic design, bitemporal model
- Getting started guide: L1 setup, Docker, environment variables
- Developer guide: API reference, error codes
- Case studies: equity fund, prop desk, quant fund deployment examples
- Pricing: L1/L2/L3 editions, per-agent pricing
- Compliance guide: MiFID II, EU AI Act, SEC 15c3-5, DORA regulatory mapping
- SLA document: uptime commitments, support tiers

[1.2.0]: https://github.com/macropulse-lab/irl-public-docs/releases/tag/v1.2.0
[1.1.0]: https://github.com/macropulse-lab/irl-public-docs/releases/tag/v1.1.0
[1.0.0]: https://github.com/macropulse-lab/irl-public-docs/releases/tag/v1.0.0
