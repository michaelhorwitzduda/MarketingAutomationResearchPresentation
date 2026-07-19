# Marketing Automation — Launch Brief (encrypted)

Password-protected presentation, served via GitHub Pages. Open the page and
enter the password to view — nothing on this repo is readable without it
(`index.html` is AES-GCM encrypted client-side via PageCrypt, PBKDF2 2M iterations).

- **Source of truth:** the private research repo
  [`marketingautomationresearch`](https://github.com/michaelhorwitzduda/marketingautomationresearch) —
  deck source, datasets, and analysis pipelines live there.
- **Provenance:** [`deck-provenance.json`](deck-provenance.json) records the exact
  research-repo commit each published version was built from. Publishing happens
  only through the research repo's `publish-deck.mjs` (encrypt → decrypt-verify →
  provenance → push).
- The supporting data kit is distributed separately via private Google Drive
  (never committed here).
