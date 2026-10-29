# CVC Cleaning website

A five-page React website built with Vite.

## Run locally

1. Install Node.js (18 or newer).
2. In this folder, run `npm install`.
3. Run `npm run dev` and open the local URL printed in the terminal.
4. Run `npm run build` to create the production site in `dist/`.

## Pages

- `/` — Home
- `/services/` — Services and service area
- `/about/` — About CVC Cleaning
- `/videos/` — Illustrative carpet and sofa cleaning clips
- `/contact/` — Quote enquiry form

## Project files

- `src/main.jsx` — React components, page content, chatbot and form behavior
- `src/styles.css` — Responsive layout and visual styling
- `index.html` and each page folder's `index.html` — Page metadata and entry points
- `public/images/` — Local image assets
- `public/videos/` — Local video assets
- `public/favicon.svg` — Site icon
- `vite.config.js` — Multi-page Vite configuration
- `package.json` and `package-lock.json` — Dependencies and scripts
- `dist/` — Production build output

## Contact form and chatbot

The quote form validates the required fields and opens a prefilled email draft addressed to CVC. It does not submit directly or store form entries. Direct delivery requires an email service or server endpoint.

The chatbot uses preset answers in the browser. It does not call an AI service or require API credentials.

## Media credits

The two video clips are illustrative Pexels stock footage by Michaelangelo Buonarroti. They are not CVC customer work. The image assets are illustrative stock photos downloaded from Unsplash and Pexels.
