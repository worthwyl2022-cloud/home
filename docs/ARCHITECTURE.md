# Cranium Command Architecture

## Canonical authority

`cranium-kernel` is the canonical authority source. It owns authority transitions, governance enforcement, receipts/evidence, replay/tamper handling, recovery, and conformance.

## Command surface

`cranium-ultra-platform/projects/cranium-os` is the Cranium Command operator UI. It exposes the Substrate Terminal, Canonical Ledger, and Authority Dashboard.

## Hardened Core

`cranium-ultra-platform/projects/cranium-core-hardened` is a hardened reference implementation used for operator integration and verification. It is not a replacement for the canonical Kernel.

## Supporting planes

- Synapse: bounded cognition/evidence/attestation interface.
- Cranium AI: cognition/application layer.
- WorthWyl Forge: creative/application surface.
- Metacognitive Mapper: metacognitive/operator support surface.
- Ultra Platform: integrated operator and verification monorepo.
- Provider Integrations: multi-provider proposal/gateway layer.
- Boot Drive: offline/commercial delivery appliance.
- Acquisition Demo Drive: buyer-facing offline demo and diligence surface.
- Diligence Workbench / Acquisition Template / Portfolio: evidence and acquisition surfaces.
- Canonlane Contracts: semantic and governance contract plane.
- Archive: provenance and historical material.

## Rule

No supporting surface may independently claim canonical authority. Cognition can be proposed by any approved source, but authority is granted only through the canonical authority boundary.
