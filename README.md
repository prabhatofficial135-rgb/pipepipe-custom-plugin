# pipepipe-custom-plugin

PipePipe plugin repository hosting the **Internet Archive** plugin.

## Contents

| File | Description |
|---|---|
| `index.json` | Plugin repository index (format v1) listing the plugin package, signature, and SHA-256 checksum |
| `internet-archive-1.ppp` | Plugin package v1.0.0 (`org.pipepipe.plugin.internetarchive`) — discover, search, browse collections, and stream public-domain videos from archive.org |

## Usage

In PipePipe, add this repository via its hosted `index.json` URL (e.g. the GitHub Pages / raw URL of this repo). The app validates `internet-archive-1.ppp` against the `sha256` recorded in `index.json` (`2ea183b80e3fba876657fb633e698505dce5096cbdb9cf55d2bf6196e3a90cff`).
