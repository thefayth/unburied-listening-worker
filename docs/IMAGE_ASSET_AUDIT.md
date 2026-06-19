# Image Asset Audit

This audit records candidate visuals discovered during the updated GitHubify
pass. Values and private content were not displayed.

## Summary

Existing visuals were found in the copied parent app and brand receipt folders.
Faith explicitly approved using the existing Big Stick, Unburied, and Fightback
visuals. The public repo now includes the existing public brand panels/marks and
continues to exclude private screenshots and runtime receipts.

## Candidate Images

| Source path | Image purpose | Recommended use | Alt text | Rating |
| --- | --- | --- | --- | --- |
| `local-full-app/bigstick/public/brand/unburied/hero-panel.svg` | Existing Unburied brand panel | Public repo gallery and WordPress visual gallery | Unburied archive intelligence artwork | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/unburied/logo-mark.svg` | Existing Unburied mark | Public repo gallery and project mark context | Unburied logo mark | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/desktop-icon.png` | Existing generated desktop icon | Public repo brand asset context | Big Stick desktop icon | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/icon-192.png` | Existing Big Stick icon | Public repo brand asset context | Big Stick icon | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/icon-512.png` | Existing Big Stick icon | Public repo brand asset context | Big Stick high-resolution icon | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/hero-panel.svg` | Existing Big Stick panel | Public repo gallery and ecosystem context | Big Stick command board artwork | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/logo-mark.svg` | Existing Big Stick mark | Public repo gallery and ecosystem context | Big Stick logo mark | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/fightback/hero-panel.svg` | Existing Fightback panel | Public repo gallery and ecosystem context | Fightback analog public record artwork | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/fightback/logo-mark.svg` | Existing Fightback mark | Public repo gallery and ecosystem context | Fightback logo mark | PUBLIC SAFE |
| `local-full-app/bigstick/docs/brand/auntie-ai/*/receipts/screenshots/*.png` | Brand implementation screenshots | Do not publish from worker repo; screenshots may reveal app state or private UX context | Private app screenshot | PRIVATE / DO NOT USE |
| `_github_public_export/assets/banners/repository-banner.svg` | Public repo banner | Use in README | Unburied Listening Worker abstract repository banner | PUBLIC SAFE |
| `_github_public_export/assets/social/social-preview.svg` | Social preview / WordPress featured image | Use as public social card or draft featured image | Social preview for protected listening infrastructure | PUBLIC SAFE |
| `_github_public_export/assets/diagrams/workflow-overview.svg` | Workflow diagram | Use in README and WordPress draft | Public-safe workflow overview for protected listening review | PUBLIC SAFE |
| `_github_public_export/assets/diagrams/public-private-boundary.svg` | Boundary diagram | Use in README and docs | Public/private boundary diagram | PUBLIC SAFE |
| `_github_public_export/assets/unburied-listening-worker-system-diagram.svg` | Abstract system diagram | Optional gallery/WordPress section image | Abstract diagram showing private intake, protected review, and mirror-safe export | PUBLIC SAFE |

## Decision

Existing public brand panels/marks were copied into `assets/brand/`. Private
screenshots and receipt images were not copied.

## Next Review

If Faith wants a stronger visual pass, the next step is to create a composed
hero/social image using these approved brand assets.
