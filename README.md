# walkthrough-assets

Orphan branch that hosts demo media referenced from pull requests. Not part of the product source.

## Contents

- `degraded-setup-walkthrough.mp4` — 45s HyperFrames walkthrough of the degraded Setup path (launcher refused → degraded notice → craft-floor must-read → DESIGN.md only after document.md), 1920x1080, for [pbakaus/impeccable#791](https://github.com/pbakaus/impeccable/pull/791).
- `degraded-setup-walkthrough.gif` — same walkthrough as a 960x540 12fps GIF for inline markdown embeds.
- `detect-dom-route-template-extensions.mp4` — 42s HyperFrames walkthrough of detect DOM routing for template/SFC extensions (main misses `.vue`; this PR matches `.html` / `.vue` / configured `.html.erb`), 1920x1080, for [pbakaus/impeccable#798](https://github.com/pbakaus/impeccable/pull/798).
- `detect-dom-route-template-extensions.gif` — same walkthrough as a 960x540 12fps GIF for inline markdown embeds.

The videos were composed as HTML and rendered deterministically with [HyperFrames](https://github.com/heygen-com/hyperframes) (`npx hyperframes render`). AI assistance was used to author the compositions.
