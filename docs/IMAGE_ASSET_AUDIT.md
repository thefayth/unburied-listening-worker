# Image Asset Audit

This audit records candidate visuals discovered during the updated GitHubify
pass. Values and private content were not displayed.

## Summary

Existing visuals were found in the copied parent app and brand receipt folders.
Because this worker is private infrastructure, most screenshots and runtime
brand receipts need Faith review before any public use. The GitHub repository
therefore uses only original abstract SVG assets created for this public
surface.

## Candidate Images

| Source path | Image purpose | Recommended use | Alt text | Rating |
| --- | --- | --- | --- | --- |
| `local-full-app/bigstick/public/brand/unburied/hero-panel.svg` | Existing Unburied brand panel | Possible future WordPress section art after Faith review | Abstract Unburied brand panel | NEEDS FAITH REVIEW |
| `local-full-app/bigstick/public/brand/unburied/logo-mark.svg` | Existing Unburied mark | Possible future project mark if Faith approves name/brand use | Unburied logo mark | NEEDS FAITH REVIEW |
| `local-full-app/bigstick/public/brand/bigstick/desktop-icon.png` | Existing generated desktop icon | Do not use for this worker-specific repo unless Big Stick umbrella branding is approved | Big Stick desktop icon | NEEDS FAITH REVIEW |
| `local-full-app/bigstick/public/brand/bigstick/hero-panel.svg` | Existing Big Stick panel | Possible umbrella ecosystem visual, not worker-specific | Big Stick hero panel | NEEDS FAITH REVIEW |
| `local-full-app/bigstick/public/brand/fightback/hero-panel.svg` | Existing Fightback panel | Do not use for this worker surface unless folded into Fightback page | Fightback hero panel | NEEDS FAITH REVIEW |
| `local-full-app/bigstick/docs/brand/auntie-ai/*/receipts/screenshots/*.png` | Brand implementation screenshots | Do not publish from worker repo; screenshots may reveal app state or private UX context | Private app screenshot | PRIVATE / DO NOT USE |
| `_github_public_export/assets/banners/repository-banner.svg` | Public repo banner | Use in README | Unburied Listening Worker abstract repository banner | PUBLIC SAFE |
| `_github_public_export/assets/social/social-preview.svg` | Social preview / WordPress featured image | Use as public social card or draft featured image | Social preview for protected listening infrastructure | PUBLIC SAFE |
| `_github_public_export/assets/diagrams/workflow-overview.svg` | Workflow diagram | Use in README and WordPress draft | Public-safe workflow overview for protected listening review | PUBLIC SAFE |
| `_github_public_export/assets/diagrams/public-private-boundary.svg` | Boundary diagram | Use in README and docs | Public/private boundary diagram | PUBLIC SAFE |
| `_github_public_export/assets/unburied-listening-worker-system-diagram.svg` | Abstract system diagram | Optional gallery/WordPress section image | Abstract diagram showing private intake, protected review, and mirror-safe export | PUBLIC SAFE |

## Decision

No discovered private-project images were copied into GitHub. The repository
uses public-safe abstract SVG assets only.

## Next Review

If Faith wants the public page to carry stronger Big Stick / Unburied branding,
review the existing `public/brand` SVGs and approve which ones may be copied
into the public repo.
