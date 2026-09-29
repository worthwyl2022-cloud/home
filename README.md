# Cranium Command

**Finished infrastructure home for Convertible Cranium.**

> Cognition may come from anywhere. Authority comes only through Cranium.

Cranium Command is the operational control surface for the Cranium governance ecosystem. This repository is the integrated delivery and documentation home. The individual repositories remain the engineering sources of truth.

## Authority boundary

`cranium-kernel` is the canonical authority source. `cranium-synapse` is the bounded evidence and assessment interface. Cognitive/application surfaces may propose cognition, but authority is only effective through the Kernel authority boundary.

## Live Command surface

**https://worthwyl2022-cloud.github.io/home/**

The static Cranium Command surface is live through GitHub Pages. It is the deployable operator/demo surface; the authority bridge remains fail-closed until an authenticated Kernel service is attached.

## Current release state

- Cranium Command UI: production build verified locally.
- Cranium Core hardened reference: typecheck, unit tests, adversarial suite, build, and production dependency audit pass locally.
- Current open pull requests across the GitHub account: **0**.
- Static Command surface is deployable from `site/`.
- The browser adapter remains fail-closed until an authenticated transport to a running Kernel service is configured. The online UI must not be represented as a live authority service until that transport is verified.

## Architecture

See `docs/ARCHITECTURE.md` for the repository and authority topology, `docs/DEPLOYMENT.md` for the release boundary, and `docs/REPOSITORY-MAP.md` for the account-wide component map.

## Source repositories

Canonical and supporting implementations remain in their own repositories under `worthwyl2022-cloud`. This home repository is deliberately a delivery/integration surface, not a second copy of the authority implementation.
