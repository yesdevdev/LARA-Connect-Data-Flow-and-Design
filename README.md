# LARA Connect — Feature & Data-Flow Documentation

Interactive HTML reference document for **LARA Connect**, the collaboration layer of the LARA suite for architecture, engineering, and construction teams.

## View it

Open `index.html` in any modern browser, or deploy to any static host.

## Deploy

This is a single-file static site. No build step. No dependencies beyond Google Fonts (loaded via CDN).

### GitHub Pages
1. Push this repo to GitHub
2. Settings → Pages → Source: `main` branch, `/` root
3. Visit `https://<username>.github.io/<repo-name>/`

### Netlify
Drag the folder onto [app.netlify.com/drop](https://app.netlify.com/drop)

### Vercel
```bash
npx vercel
```

### Cloudflare Pages / Any static host
Upload `index.html`. Done.

## Features

- Sticky table of contents with scroll-spy
- Interactive channel architecture diagram (click tabs to inspect)
- Collapsible feature spec cards
- Clickable permission matrix (highlight by role)
- Tabbed flow viewers for auth/navigation/architecture
- Print-friendly stylesheet
- Fully responsive

## Scope

Document scope: code base at `repo/UI` as of 2026-05-18, including the Calendar feature and the per-channel AI tab.

## Stack

- Plain HTML/CSS/JS — no framework, no build
- Fraunces + JetBrains Mono + Inter Tight via Google Fonts
- ~89 KB total

## License

Internal reference — BluEnt.
