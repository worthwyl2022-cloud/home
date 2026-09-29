# Deployment Readiness

## Verified tonight

The Cranium Command frontend was built from the current Ultra Platform source with Node 24. The local verification completed with:

- TypeScript typecheck: PASS
- UI tests: 2/2 PASS
- Vite production build: PASS
- Production dependency audit: 0 vulnerabilities
- Hardened Core unit tests: 6/6 PASS
- Hardened Core adversarial suite: 6/6 PASS
- Hardened Core TypeScript build: PASS
- Hardened Core production dependency audit: 0 vulnerabilities

## Explicit production boundary

The browser `AuthorityBridge` intentionally fails closed when no authenticated Kernel adapter is configured. It does not evaluate authority locally and cannot issue a receipt. This is deliberate.

Therefore a public static Command deployment is a deployable operator/demo surface, not a claim that a live remote authority service is already online.

For a true live authority deployment, the remaining release gate is an authenticated Kernel transport with request authentication, replay protection, receipt verification, authorization at the service boundary, structured audit export, and staging verification before owner-controlled production signing/deployment.
