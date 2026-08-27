# skimly

Chrome extension that summarizes the current page with an LLM

## Install

```bash
# chrome://extensions -> load unpacked -> select this folder
# set your API base + key on the options page
```

## What it does

- Options page for API base and key
- Reads the page, extracts main text, sends to your endpoint
- Popup shows a 5-bullet summary
- Manifest V3 service worker, no build step

## Examples

```bash
# open any article, click the icon, get a 5-bullet summary
```

## Project structure

```text
├── .github/
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── options.html
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## License

MIT licensed, see LICENSE.
