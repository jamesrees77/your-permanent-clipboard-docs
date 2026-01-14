## Your Permanent Clipboard

A Chrome extension that keeps a searchable clipboard history and lets you save reusable snippets (with templates like `{{date}}`) so you can paste faster—every day.

> **Docs-only repo:** This repository is for documentation and user help. **The extension source code is private.**

---

## What you can do with it

- **Clipboard history**: Automatically keeps recent clipboard items (stored locally on your device)
- **Saved snippets**: Save reusable text you paste often (syncs via Chrome Sync)
- **Categories + tags**: Organize your snippets so they’re easy to find later
- **Fast search**: Search by name, content, category, or tags
- **Right‑click paste**: Paste directly from the context menu
- **Keyboard shortcuts**: Open the manager + paste pinned items instantly
- **Templates**: Insert dynamic values like date/time when you paste

---

## How it works (quick tour)

### 1) Clipboard history
Copy text as normal. The extension captures it and makes it searchable in the popup.

### 2) Save a snippet
Open the popup → create a new clip → optionally add category/tags → save.

### 3) Paste anywhere
- **Popup**: search and paste
- **Right‑click menu**: pick from Recent / Pinned / Categories
- **Shortcuts**: paste pinned items quickly

---

## Templates (dynamic variables)

You can use these in snippet content:

- `{{date}}` – Current date (e.g., “Jan 14, 2026”)
- `{{time}}` – Current time
- `{{datetime}}` – Full date + time
- `{{day}}` – Day of week (e.g., “Wednesday”)
- `{{clipboard}}` – Current clipboard content
- `{{cursor}}` – Cursor position after paste

Example:

Meeting Notes — {{date}}

Attendees:
- 

Notes:
{{cursor}}
