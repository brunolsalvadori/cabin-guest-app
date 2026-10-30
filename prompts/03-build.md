# 03 — Build

> Reconstructed from my project notes and the production guide. The prompt is summarized, not verbatim.

## Goal
Ship a first version guests can open on a phone, on a slow rural connection, with nothing to install.

## Prompt
*Summary:* Build the guide as a static website: a landing page with one icon per section, one page per section, and the tourist guide one tap away. It must read well on a phone.

## What came back
A static site with a shared stylesheet, a landing page with an icon grid and one page per section, plus a tourist guide page with category filters, search and a card per place.

## What I kept, changed or rejected
- **Kept — static HTML, CSS and vanilla JavaScript.** No backend and no app builder: zero running cost, fast on mobile data, nothing to maintain.
- **Kept — one link for everything.** The hospitality guide is the landing page and the tourist guide is one of its icons, so the host sends a single link in the booking message.
- **Kept — actions on every place card.** Route from the cabin, view on Maps and WhatsApp, so guests act from the card instead of copying addresses.
- **Kept — hosting on Netlify.**
