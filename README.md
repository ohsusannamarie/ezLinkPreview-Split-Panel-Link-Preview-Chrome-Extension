# ezLinkPreview - Split-Panel Link Preview Chrome Extension

A lightweight Chrome extension for previewing links without losing your place.

ezLinkPreview opens the current tab into a split-panel browsing experience: links on the left, previews on the right. It was built for fast link triage, research workflows, sourcing, OSINT, and anyone who lives inside search results.

> Legacy extension archive: this repo contains ezLinkPreview v6.24 using Chrome Manifest V2.

---

## What it does

- Preview links in a right-side panel
- Keep your original page visible while reviewing results
- Move faster through search results, profiles, articles, and research lists
- Reduce tab overload during sourcing or investigation work
- Useful for recruiters, sourcers, researchers, OSINT analysts, and browser power users

---

## Why this matters

When you are sourcing or researching, the problem usually is not finding links.

The problem is opening 47 tabs, forgetting which one mattered, losing your original search context, and slowly becoming a browser goblin.

ezLinkPreview helps turn link review into a workflow instead of a tab explosion.

---

## Best use cases

- Reviewing Google search results
- Screening candidate profile links
- Checking company/team pages
- Researching sourcing targets
- Reviewing Boolean search output
- OSINT link triage
- Comparing pages without losing the source list

---

## Installation

Because this is a legacy unpacked Chrome extension, install it manually:

1. Download or clone this repo.
2. Open Chrome.
3. Go to `chrome://extensions/`.
4. Enable **Developer mode**.
5. Click **Load unpacked**.
6. Select the extension folder containing `manifest.json`.
7. Pin the extension if desired.

---

## Notes

This repo currently preserves the original v6.24 extension structure.

The extension uses:

- JavaScript
- HTML
- jQuery
- Chrome Manifest V2

Modern Chrome extension development now uses Manifest V3, so this project is best treated as:

- a useful legacy tool,
- a browser workflow artifact,
- or a starting point for a future MV3 rebuild.
