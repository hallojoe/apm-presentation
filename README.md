# APM — Like npm for agentic things

A KMD-branded, 16-slide web presentation about Microsoft Agent Package Manager. Designed for an 19-minute team session, including discussion. The final slide is an untimed resource appendix.

The opening explains APM through the npm analogy (manifest, install command, lockfile). The six capability slides use concrete house-rules, saved-request, recipe, reviewer-hat, connection and toolkit examples. Slides 3 and 11 make `apm.yml` the narrative anchor: a complete manifest, field-by-field explanation, and a mapping to all six capabilities. Download the example from slide 3 or use `assets/example-apm.yml`. It is an illustrative configuration referencing real packages, not an existing KMD setup.

## Present

- Arrow keys / Space / Page Down: next; Left / Page Up: previous.
- Home / End: first / last slide.
- O: slide overview. N: speaker notes. F: fullscreen. Escape: close notes or overview.
- Notes appear on the current screen: hide them before sharing your screen.
- Buttons, touch swipes and direct slide links (`#5`) are supported.
- Slide 12 has a four-step, copyable walkthrough. It does not execute commands.
- Browser printing produces a landscape handout.

The talk totals 19 minutes. Speaker notes include suggested time and elapsed starting time. All examples of team policies, the review agent, and the finding are illustrative, not existing KMD policy or a real audit. APM commands are documentation-checked examples and have not been integration-tested by installing packages.

## Develop and deploy

Buildless HTML/CSS/JavaScript; no runtime dependencies, analytics or external fonts. Serve the repository with any static server. Edit content and notes in `slides.js`, styling in `style.css`, controls in `app.js`.

Push to `main` to run `.github/workflows/pages.yml`. The workflow syntax-checks JavaScript, stages only presentation assets and deploys through GitHub Pages Actions. Pages must be configured with source **GitHub Actions**.

## Sources

- [User's starting guide](https://gist.github.com/hallojoe/309e0f28c4d4a2119fa9c6fb12766454)
- [Microsoft APM](https://github.com/microsoft/apm)
- [Quickstart](https://microsoft.github.io/apm/quickstart/)
- [Primitive authoring](https://microsoft.github.io/apm/producer/write-primitives/)
- [Plugin packaging](https://microsoft.github.io/apm/producer/build-a-plugin/)
- [Sample package](https://github.com/microsoft/apm-sample-package)
- [KMD official press assets](https://www.kmd.dk/presse/pressefotos): original white SVG logo, © KMD. The logo is not modified.

Prepared 26 November 2026. Target support and CLI behavior evolve; check current documentation and the installed version.
