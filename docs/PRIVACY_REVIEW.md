# Privacy Review

This file is the public-repo privacy review. A longer safety review also exists
at `docs/PRIVACY_AND_SAFETY_REVIEW.md`.

## Files Inspected

- Top-level project listing.
- `README.md`
- `package.json`
- `docs/CODEX_PLAN.md`
- `docs/AUTONOMOUS_BUILD_STATUS.md`
- `docs/FULL_APP_FINISH_AUDIT_20260617.md`
- Path-only sensitive-category scan.
- Existing visual-asset locations from the updated brief, including copied
  parent `public/brand` assets and brand receipt screenshot folders.

## Sensitive Categories Found

- Environment/config material.
- Local passcode and worker-token runtime files.
- Protected storage, transcripts, uploads, and analysis artifacts.
- Deployment, backup, service, and optional web-server materials.
- Private receipts and release manifests.
- Legal/admin/evidence-adjacent project language.

No secret values are displayed here.

## Files Excluded

- `.env`
- `src/`
- `scripts/`
- `storage/`
- `deploy/`
- `release/`
- `local-full-app/`
- `node_modules/`
- `.venv/`
- logs, runtime files, shortcuts, private receipts

## Public-Safe Claims Used

- This is a protected companion worker for Big Stick/Unburied listening review.
- It is private infrastructure, not a public app.
- It separates raw intake from mirror-safe review data.
- Public materials are docs-only.

## Claims Avoided

- No claim that the worker is publicly available.
- No claim that source is open.
- No claim about legal outcomes, customers, cases, or live production status.
- No claim that a WordPress page has been published.

## Image Safety

Safe: abstract diagrams and generated visuals with no private data.

Not safe: private screenshots, transcripts, recordings, logs, storage records,
case details, names, addresses, tokens, or dashboard captures.

Image audit: `docs/IMAGE_ASSET_AUDIT.md`.

## Workflow Safety

Workflow diagrams are intentionally abstract and do not reveal endpoint names,
service credentials, server paths, deployment topology, or private review logic.

## Rating

READY AFTER FAITH REVIEW
