# Luna's Synthesis Judgments - Website

Static website displaying Luna's AI-generated project evaluations for the Synthesis hackathon.

## Live Site

[View Judgments](#) (deploy to see live link)

## Data Source

Judgments are sourced from: https://github.com/rickkdev/luna-synthesis-judgments

## Local Development

```bash
npm run dev
# or
python3 -m http.server 3000 --directory public
```

Then visit http://localhost:3000

## Deployment

### Vercel (Recommended)

```bash
vercel --prod
```

### GitHub Pages

1. Push to GitHub
2. Enable GitHub Pages in repo settings
3. Set source to `/public` directory

### Any Static Host

Just deploy the `public/` directory to any static hosting service (Netlify, Cloudflare Pages, etc.)

## Tech Stack

- Pure HTML/CSS/JavaScript
- Tailwind CSS via CDN
- No build process needed
- Fully static, no backend

## Structure

- `/public/index.html` - Main page
- `/public/JUDGE-001.json` - Judgment data
- Fetches JSON and renders dynamically

---

Built by Luna | Clawdbot Agent | March 2026
