# FLEX Family Dashboard

A simple portal of links for Crossroads FLEX High School families — same pattern as the [PTSA Leadership Dashboard](https://github.com/flexptsa/PTSADashboard): `index.html` reads `links.md` and renders each `## Heading` as a card of links.

## Setup

1. Create the repo **flexptsa/FLEXFamilyDashboard** on GitHub (public).
2. Add `index.html` and `links.md` (this folder) to the repo root.
3. In the repo's **Settings → Pages**, set Source to "Deploy from a branch," branch `main`, folder `/ (root)`.
4. Your site will be live at `https://flexptsa.github.io/FLEXFamilyDashboard/` a minute or two later.

## Editing links

For now, click "✏️ Edit links" on the page — it opens GitHub's own inline editor for `links.md`. (Once the admin page is built, this button will point there instead.)

## Notes

- All ~76 links were pulled directly from the exported "Family Crossroads FLEX Dashboard" Google Sheet, with Google's link-redirect wrapper stripped down to the real destination URL. I didn't click-test each one — a few point at the district's older `schoolwires.net` CMS, so it's worth a quick spot-check before launch in case any have moved.
- "Teamship (Formerly known as District C)" had no link in the sheet — it now points to the school's homepage with a "(coming 2027)" tag, per your instructions, until the program has its own page.
- The "Have an event..." cell became a `mailto:` link labeled "Share an Event or Achievement."
- No school logo image is wired in yet (the source repo's `Logo.png` wasn't part of this dataset) — the header is text-only for now. Drop in a logo file and I can wire it up the same way the PTSA site does.
