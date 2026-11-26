# Decisions

Dated decisions for this repo, newest last.

- 2026-11-26: created from the ops starter kit, area `co-plugins`.
- 2026-11-26 (Garfunkel, bottle 205, relayed by Simon): a reusable admin theme plugin (D5257) with four modes, Bold or Quiet in light or dark, and optional pairing with color-theory and roles (D5258). The owner chose the direction on Captive Origins' side (D5377): Bold by default, a brown side menu with an orange rule, warm paper #fdfaf7. Garfunkel builds it through pull requests on co/ branches; only the owner merges.
- 2026-11-26 (Simon): created like payload-plugin-stats. Public from the start under the weekly grant for going public after a clean audit, with a coming-soon README, MIT, Copyright (c) 2026 EXTANT APE, and D256 access (the garfunkel-contributors team can push branches, the default branch is owner-only, v* and desktop-v* tags are owner-only).
- 2026-11-26: `package.json` is the single source for the description and keywords. It says `"private": true` and version 0.0.0 until the first release is planned, so nothing can be published to npm by accident. Removing it is part of that release, and publishing stays the owner's.
