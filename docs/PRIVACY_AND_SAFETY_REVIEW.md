# Privacy And Safety Review

## Files Inspected

- Top-level project listing.
- `README.md`
- `package.json`
- `docs/CODEX_PLAN.md`
- `docs/AUTONOMOUS_BUILD_STATUS.md`
- `docs/FULL_APP_FINISH_AUDIT_20260617.md`
- Path-only sensitive scan across the project, excluding large dependency and
  release noise where practical.

## Files Created

Public-safe staging files under:

`_public_surface/unburied-listening-worker/`

## Sensitive Categories Found

Potential sensitive categories were found by path/category only. Values were
not displayed.

- Environment/config material: `.env`, env examples, deploy env examples.
- Credentials/runtime secrets: local passcode and worker token runtime files.
- Protected data: `storage/`, transcripts, uploads, analysis artifacts, and
  social-store records.
- Deployment/operations: service units, backup scripts, Apache optional config,
  production handoff materials.
- Legal/admin/family/evidence-adjacent language: Big Stick, Unburied,
  Fightback, court, disability, evidence, protected review.
- Private receipts: local runtime receipts, canonical handoffs, release
  manifests, full-app status receipts.

## Sensitive Files Excluded

- `.env`
- `storage/`
- `local-full-app/runtime/`
- `local-full-app/bigstick/storage/`
- `deploy/`
- `release/`
- `src/`
- `scripts/`
- `node_modules/`
- `.venv/`
- local logs and shortcut/runtime files

## Potential Secret Locations

Potential secret found in `.env`, category environment value. Value not
displayed.

Potential secret found in `local-full-app/runtime/local-admin-passcode.txt`,
category passcode. Value not displayed.

Potential secret found in `local-full-app/runtime/local-worker-token.txt`,
category token. Value not displayed.

## Public-Safe Claims Used

- The worker is a protected companion service for Big Stick/Unburied listening
  workflows.
- It is private/local infrastructure, not a public app.
- It processes controlled intake and returns mirror-safe review data.
- Inspected docs report local smoke and verification receipts.

## Claims Avoided

- No claim that the service is publicly available.
- No claim that a WordPress page or GitHub repo has been published.
- No claim about customers, cases, legal outcomes, or production state.
- No claim that source code is open.

## Images Safe / Not Safe

Safe: abstract diagrams, generated visuals, prompt-pack concepts.

Not safe: screenshots, transcripts, recordings, storage records, logs, private
dashboards, personal records, or deployment details.

## WordPress Safe / Not Safe

Safe after Faith review as a protected project note.

Not safe as a product page, public API page, sales page, or download page.

## GitHub Safe / Not Safe

Safe after Faith review as docs-only.

Not safe if source, storage, runtime, deployment, or receipt folders are pushed.

## Final Rating

PUBLIC SURFACE READINESS: READY AFTER FAITH REVIEW
