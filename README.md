# focusfolio

Chrome extension that tracks reading time per tab

Started as a weekend hack, grew on me.

## Features

- Popup shows today's total focus time
- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```
