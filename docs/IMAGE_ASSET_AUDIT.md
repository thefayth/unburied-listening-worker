# Image Asset Audit

This audit records candidate visuals discovered during the updated GitHubify
pass. Values and private content were not displayed.

## Summary

Existing visuals were found in the copied parent app and brand receipt folders.
Faith explicitly approved using the existing Big Stick, Unburied, and Fightback
visuals. The public repo now includes the existing public brand panels/marks and
continues to exclude private screenshots and runtime receipts.

## Candidate And Selected Images

| Source path | Destination path | Purpose | Alt text | Safety rating |
| --- | --- | --- | --- | --- |
| `local-full-app/bigstick/public/brand/unburied/hero-panel.svg` | `assets/hero/hero-image.svg`; `assets/gallery/unburied-hero-panel.svg`; `assets/brand/unburied/hero-panel.svg` | Existing Unburied hero / WordPress visual | Unburied archive intelligence artwork | PUBLIC SAFE |
| `generated from approved brand direction` | `assets/hero/hero-image.png` | README hero and WordPress hero candidate | Public-safe hero for Unburied Listening Worker | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/unburied/logo-mark.svg` | `assets/gallery/unburied-logo-mark.svg`; `assets/brand/unburied/logo-mark.svg` | Existing Unburied mark | Unburied logo mark | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/desktop-icon.png` | `assets/icons/project-icon.png`; `assets/brand/bigstick/desktop-icon.png` | Project icon and ecosystem marker | Big Stick desktop icon | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/icon-192.png` | `assets/brand/bigstick/icon-192.png` | Existing Big Stick icon | Big Stick icon | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/icon-512.png` | `assets/brand/bigstick/icon-512.png` | Existing Big Stick icon | Big Stick high-resolution icon | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/hero-panel.svg` | `assets/gallery/bigstick-hero-panel.svg`; `assets/brand/bigstick/hero-panel.svg` | Existing Big Stick ecosystem panel | Big Stick command board artwork | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/bigstick/logo-mark.svg` | `assets/gallery/bigstick-logo-mark.svg`; `assets/brand/bigstick/logo-mark.svg` | Existing Big Stick mark | Big Stick logo mark | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/fightback/hero-panel.svg` | `assets/gallery/fightback-hero-panel.svg`; `assets/brand/fightback/hero-panel.svg` | Existing Fightback ecosystem panel | Fightback analog public record artwork | PUBLIC SAFE |
| `local-full-app/bigstick/public/brand/fightback/logo-mark.svg` | `assets/gallery/fightback-logo-mark.svg`; `assets/brand/fightback/logo-mark.svg` | Existing Fightback mark | Fightback logo mark | PUBLIC SAFE |
| `generated from approved brand direction` | `assets/banners/github-banner.png` | GitHub README banner | GitHub banner for Unburied Listening Worker | PUBLIC SAFE |
| `_github_public_export/assets/banners/repository-banner.svg` | `assets/banners/repository-banner.svg` | Abstract repository banner | Unburied Listening Worker abstract repository banner | PUBLIC SAFE |
| `generated from approved brand direction` | `assets/social/social-card.png` | Social preview card | Social card for Unburied Listening Worker | PUBLIC SAFE |
| `_github_public_export/assets/social/social-preview.svg` | `assets/social/social-preview.svg` | Social preview / WordPress feature fallback | Social preview for protected listening infrastructure | PUBLIC SAFE |
| `_github_public_export/assets/diagrams/workflow-overview.svg` | `assets/diagrams/workflow-overview.svg` | Workflow diagram | Public-safe workflow overview for protected listening review | PUBLIC SAFE |
| `_github_public_export/assets/diagrams/public-private-boundary.svg` | `assets/diagrams/public-private-boundary.svg` | Boundary diagram | Public/private boundary diagram | PUBLIC SAFE |
| `_github_public_export/assets/unburied-listening-worker-system-diagram.svg` | `assets/unburied-listening-worker-system-diagram.svg` | Abstract system diagram | Abstract diagram showing private intake, protected review, and mirror-safe export | PUBLIC SAFE |
| `local-full-app/bigstick/docs/brand/auntie-ai/*/receipts/screenshots/*.png` | Not copied | Brand implementation screenshots | Private app screenshot | PRIVATE / DO NOT USE |

## Decision

Existing public brand panels/marks were copied into `assets/brand/` and
selected images were copied into `assets/hero/`, `assets/gallery/`,
`assets/icons/`, `assets/banners/`, and `assets/social/`. Private screenshots
and receipt images were not copied.

## Next Review

If Faith wants a stronger visual pass, the next step is to create a composed
hero/social image using these approved brand assets.
