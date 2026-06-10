# getnote2obsidian

Sync GetNote notes into Obsidian.

This repository contains a packaged Obsidian plugin that can be installed manually by copying the plugin folder into an Obsidian vault.

## Plugin Info

- Plugin ID: `getnote-obsidian-sync`
- Display name: `getnote2obsidian`
- Version: `0.1.0`
- Minimum Obsidian version: `1.5.0`

## Features

- Sync recent GetNote notes into an Obsidian vault.
- Sync historical GetNote notes.
- Save notes as Markdown files.
- Keep sync history inside the plugin view.
- Configure GetNote API Key, Client ID, target folder, and sync interval locally.

## Installation

1. Download or clone this repository.
2. Copy the whole plugin folder:

```text
getnote-obsidian-sync
```

3. Paste it into your Obsidian vault plugin directory:

```text
YourVault/.obsidian/plugins/getnote-obsidian-sync
```

4. Make sure the final directory contains:

```text
YourVault/.obsidian/plugins/getnote-obsidian-sync/manifest.json
YourVault/.obsidian/plugins/getnote-obsidian-sync/main.js
YourVault/.obsidian/plugins/getnote-obsidian-sync/styles.css
```

5. Open Obsidian.
6. Go to `Settings -> Community plugins`.
7. Enable community plugins if needed.
8. Enable `getnote2obsidian`.
9. Open the plugin settings and enter your GetNote API Key and Client ID.

## Privacy

The plugin stores local settings in Obsidian's plugin data file:

```text
.obsidian/plugins/getnote-obsidian-sync/data.json
```

Do not publish or share `data.json`, because it may contain your personal GetNote API Key and Client ID.

This repository intentionally includes only the distributable plugin files:

- `manifest.json`
- `main.js`
- `styles.css`

## Manual Release

For GitHub Releases, package the `getnote-obsidian-sync` folder as a zip file and attach it to the release.

Suggested first release:

- Tag: `v0.1.0`
- Title: `getnote2obsidian v0.1.0`

## Chinese Installation Guide

See [README-安装说明.md](./README-%E5%AE%89%E8%A3%85%E8%AF%B4%E6%98%8E.md).
