# Mīnā

Arabic launcher page for 17 tools. Each tool opens on its own site.

## What it does

- Lists the tools in four views: All, Core, Tools and Lab.
- Searches with Ctrl+K or ⌘K, and Esc clears the search.
- Remembers recently opened tools, and the chosen variant for tools that have more than one.
- Marks tools as new or temporarily closed, and copies a tool's link.
- Switches between Arabic and English and between system, light and dark themes.

## What it does not do

- It does not embed the tools. Each card is a link to another site.
- The tool list is fixed in `index.html`. There is no way to add a tool from the page.
- It has no accounts or sync. Theme, language, view, recents and variants are kept in `localStorage` under `mina:v3`.

## Network and install

Loads Google Fonts. It makes no other requests until you open a tool, which loads that tool's own site. Not installable; no service worker.

## Built with

One HTML file, with no build step and no framework.

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server.
