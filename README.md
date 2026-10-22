# Central Texas FTC Guide

[![CI](https://github.com/kiriz/ftc/actions/workflows/ci.yml/badge.svg)](https://github.com/kiriz/ftc/actions/workflows/ci.yml)
[![Live site](https://img.shields.io/badge/live-kiriz.github.io%2Fftc-3b82f6)](https://kiriz.github.io/ftc/)

A plain-English guide to FIRST Tech Challenge and the 2026–27 BIOBUZZ season for families, students and coaches of Austin-area and Central Texas teams. Not an official FIRST site.

## How to edit a page

All pages are Markdown files in `docs/`.

1. On GitHub, open the file in `docs/` (for example `docs/calendar.md`) and click the pencil icon.
2. Make your change.
3. Update `last_updated:` at the top of the file to today's date (`YYYY-MM-DD`).
4. Click **Commit changes**.

## How to publish

Every commit to `main` publishes automatically. The live site updates in about a minute.

For bigger changes, add a line to `CHANGELOG.md` with a new version number, the date and a one-line summary.

## How to add a page

1. Create a new `.md` file in `docs/` starting with:

   ```markdown
   ---
   layout: page
   title: My Page
   last_updated: 2026-10-22
   ---
   ```

2. Add the file name to `header_pages` in `docs/_config.yml` to show it in the menu.

## Content rules

- Use only facts from official FIRST or FIRST Texas pages. Mark anything unconfirmed as "To be announced" or "(estimated)".
- End every page with a "Sources" list.
- No personal information: no names, phone numbers or personal email addresses.
- No logos or images from FIRST, FTC, BIOBUZZ, RTX or sponsors.
