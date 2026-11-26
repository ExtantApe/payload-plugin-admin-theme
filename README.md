# payload-plugin-admin-theme

Admin theme for Payload: Bold or Quiet, light or dark, by swapping Payload's color variables, with every text and background pair checked for WCAG AA contrast. Coming soon.

> **Status: coming soon.** This repo holds the name, the license and the plan's first decisions. There's no code yet, so nothing has been tested, and nothing is on npm.

## What it will do

- Give the Payload admin one of four looks: Bold or Quiet, each in light and dark.
- Swap Payload's own color variables, so most of the admin follows without extra styling.
- Fix four places where Payload's dark mode puts text on a background that's too close in color.
- Keep the few component styles it needs in one file, checked against each Payload version it supports.
- Check every text and background pair for WCAG AA contrast with a script, and test it in a running admin before the first release.
- Work on its own, with optional pairing for apps that already have a color theme or role-based looks.

## License

[MIT](LICENSE). Copyright (c) 2026 EXTANT APE.
