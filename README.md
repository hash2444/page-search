<div align="center">

# Page Search

**A browser add-on that highlights every match of a word on the page and jumps between them.**

[![Download](https://img.shields.io/badge/Download-latest%20build-e94560?style=for-the-badge&logo=github&logoColor=white)](../../releases/latest)

</div>

---

Like `Ctrl+F`, but with an overview: type a word and every hit is highlighted right away, the current hit gets its own colour. Works in Chrome, Edge, Opera and other Chromium browsers.

## What it does

- Live search while you type, all hits highlighted, current hit in cyan
- Counter `current/total` (for example `3/12`)
- `Enter` / down arrow for the next hit, `Shift+Enter` / up arrow for the previous one (wraps around)
- Options: match case, whole word only
- Remembers the last search word
- Uses the CSS Custom Highlight API - the page content is never modified

## Download

Download **`Page-Search.zip`** from the [releases page](../../releases) or straight from this repository, unzip it, and load the `page-search` folder as an unpacked extension (details in the setup help).

New to this? Follow **[SETUP-HELP.md](SETUP-HELP.md)** - it walks you through installing and starting it.

## Notes

- Browsers do not allow add-ons on internal pages (`chrome://...`, the extension store, the new-tab page) - a hint is shown there instead.
- Content inside foreign embedded frames (some ads) is not searched.

<div align="center">

<img src="page-search.png" alt="Page Search" width="760">

</div>
---

Made by **dev:#2444** - [github.com/hash2444](https://github.com/hash2444) - [page-search](https://github.com/hash2444/page-search)
