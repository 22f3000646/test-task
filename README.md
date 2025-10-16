# Test Brief App

## Overview
Test Brief App is a compact, self‑contained web app showcasing a polished UI and common front‑end patterns:
- To‑Do list with add, reorder, filter (All/Active/Done), clear completed, and localStorage persistence.
- Text Tools with transformations (upper, lower, title case, reverse, trim/clean), live metrics (characters, words, lines, read time), and clipboard copy.
- Accessible tab navigation and keyboard support.
- Light/Dark theme with persistence and a quick stats summary.

Everything runs in a single HTML file with inline CSS/JS and no external dependencies.

## Setup
- No build tools required.
- Download the repository contents or save the provided index.html locally.

Open index.html in any modern browser (Chrome, Edge, Firefox, Safari).

## Usage
- Theme:
  - Click the Theme button to toggle Light/Dark. Preference is saved.
- Tabs:
  - Use the tab buttons or Arrow Left/Right keys to switch between sections.
- To‑Do:
  - Enter a task and press Add or hit Enter.
  - Toggle completion by clicking the square on each item.
  - Reorder with ↑ and ↓ buttons.
  - Filter tasks (All/Active/Done) using the filter buttons.
  - Clear Done removes all completed tasks at once.
  - Tasks persist in your browser’s localStorage.
- Text Tools:
  - Type or paste text in the textarea.
  - Use the buttons to transform: UPPERCASE, lowercase, Title Case, Reverse, Trim & Clean.
  - Copy copies the current text to the clipboard.
  - Metrics update live: characters, words, lines, and estimated read time.
  - The text is also saved locally and restored on reload.
- About:
  - Quick summary of features.

Data stays in your browser; no network requests or tracking.