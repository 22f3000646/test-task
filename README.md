# Markdown Notes Pro

## Overview
Markdown Notes Pro is a fast, offline-ready, single-page web app for managing Markdown notes. It supports multiple notes, live preview, tags, powerful search (including tag filtering), drag-and-drop reordering, autosave, keyboard shortcuts, and import/export. Everything is stored locally in your browser — no accounts or servers required.

## Setup
- No build required.
- Open index.html in any modern browser.

Optional:
- Serve via a simple static server if you prefer:
  - Python: python3 -m http.server 8000
  - Node: npx http-server -p 8000

Then visit http://localhost:8000

## Usage
- Create a note: Click “＋ New” or press Ctrl/Cmd+N.
- Edit:
  - Title at the top.
  - Tags: Type a tag and press Enter or comma. Click a tag chip to remove it.
  - Content: Write Markdown in the editor. Live preview appears on the right.
- Save: Autosaves as you type. Press Ctrl/Cmd+S to force a save timestamp.
- Search: Use the top search box to find text in titles, content, or tags. Filter by tag with #tag (e.g., #work).
- Reorder: Drag notes in the sidebar to reorder them.
- Toggle preview: Click “👁 Preview” or press Ctrl/Cmd+P.
- Delete: Use the 🗑 Delete button.
- Export: Click “⤓ Export” to download a JSON backup.
- Import: Click “⤒ Import” and choose an exported JSON file.
- Theme: Toggle light/dark with the “🌓 Theme” button. The choice is remembered.
- Shortcuts:
  - Ctrl/Cmd+N: New note
  - Ctrl/Cmd+S: Save
  - Ctrl/Cmd+F: Focus search
  - Ctrl/Cmd+P: Toggle preview

Notes are stored locally in your browser’s localStorage. You can safely use the app offline.

## Improvements in Round 2
This version introduces significant upgrades over the previous release:
- Tags with chips and #tag search filtering.
- Powerful search across titles, content, and tags with highlighting.
- Drag-and-drop reordering of notes in the sidebar.
- Live Markdown preview with support for headings, lists, links, inline and fenced code blocks, bold/italic, and horizontal rules.
- Autosave with debounced updates and a visible “Last saved” timestamp.
- Import/Export to JSON (supports both new and legacy formats).
- Light/Dark theme toggle with persistence.
- Responsive layout with a collapsible sidebar on mobile.
- Keyboard shortcuts: New, Save, Find, Toggle Preview.
- UX polish: word/char counts, improved empty state, contextual hints.
- Safer rendering: basic HTML escaping and protocol checks inside links.