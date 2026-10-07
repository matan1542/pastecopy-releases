# PasteCopy

A native macOS clipboard manager. Everything you copy — text, images, links,
colours, files — kept, searchable, and a keystroke away.

**[Download the latest version](../../releases/latest)**

## Installing

1. Open the `.dmg` and drag **PasteCopy** to Applications.
2. Open it. PasteCopy lives in the menu bar — there is no Dock icon.
3. Grant **Accessibility** access when asked. PasteCopy needs it to paste into
   other apps; without it, it still collects your clipboard, but clicking a
   card will not paste.

If macOS refuses to open it, the build is not notarized yet. Open it once and
let it be blocked, then go to **System Settings → Privacy & Security** and
click **Open Anyway**.

## Using it

| | |
|---|---|
| `⌘⇧V` | Open your clipboard history |
| `⌘⇧C` | Copy what's selected, then open history |
| `←` `→` | Move between cards |
| `⌃←` `⌃→` | Pick several, in order |
| `Return` | Paste the selection |
| `Space` | Large preview |

Screenshots are read with OCR, so you can find one by the text inside it.

## Privacy

Your history is stored locally, on your Mac. No account, no sync, no
analytics. The one exception is link previews, which are off by default and
fetch page metadata from the site you copied a link to when turned on.

## Requirements

macOS 14 or later. Apple Silicon and Intel.

---

This repository hosts downloads only. The source is not public.
