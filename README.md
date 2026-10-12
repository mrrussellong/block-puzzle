# Blocks — legal and support pages

The public Privacy policy, Terms of use and Support pages for **Blocks: Small
Block Puzzle** (iOS bundle id `com.technoverge.blockpuzzle`).

Served by GitHub Pages from the default branch, root directory:

| page | URL |
| --- | --- |
| Home | https://mrrussellong.github.io/block-puzzle/ |
| Privacy policy | https://mrrussellong.github.io/block-puzzle/privacy.html |
| Terms of use | https://mrrussellong.github.io/block-puzzle/terms.html |
| Support | https://mrrussellong.github.io/block-puzzle/support.html |

Those three URLs are compiled into the app (`BPPrivacyPolicyURL`, `BPTermsURL`,
`BPSupportURL` in `Info.plist`) and are what App Store Connect points at, so
**do not rename these files** — a dead privacy link fails App Review.

Static HTML and one stylesheet. No build step, no JavaScript, no trackers.
