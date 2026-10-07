# Perchmark — Marketing Site

The institutional-grade short-term rental intelligence platform. Calm at the top of the noise. Built for serious investors.

**Tagline:** Hear what your street already knows.

---

## Structure

Pure static HTML  — no build step, no framework. Open any file in your browser or deploy as-is to Vercel.

| Page | File | Purpose |
|------|------|---------|
| Homepage | `index.html` | Hero, dashboard preview, features, pricing, independence section |
| Philosophy | `philosophy.html` | Brand essay: perch-above-the-noise, voice principles, what-we-won't-do |
| Changelog | `changelog.html` | Release history from v1.0 → v2.7 |
| Privacy | `privacy.html` | Plain-English privacy policy |
| Terms | `terms.html` | Plain-English terms of service |

## Deploy to Vercel

1. [vercel.com/new](https://vercel.com/new) → Import Git Repository
2. Select this repo (`perchmark-web`)
3. Framework Preset: **Other** (uses the `vercel.json` already in the repo)
4. Click **Deploy**  — auto-deploys in ~10 seconds

Every push to `main` triggers a production rebuild.

## Design system

- Typography: Fraunces (display), Inter (body), JetBrains Mono (data)
- Palette: Coastal Clarity — Driftwood Ink `#0E2438`, Kingfisher Coral `#E76C4A`, Sandstone Cream `#F6F1E7`, Salt White `#FBFAF7`
- Animation: GSAP via CDN for the bird stage + dashboard transitions
- Charts: Inline SVG
- No framework, no build step, no dependencies installed locally

## Content

All pages are complete self-contained HTML files with inline CSS + JS. Google Fonts and GSAP are loaded from CDN. Nothing else is external.

---

© 2026 Perchmark ‘ Independent ‘ operator-grade ‘ regulation-aware

---

## More from this builder

[Bidcheck](https://bidcheck.co.za) — South African government-tender intelligence for SMMEs: live tender search across all nine provinces, eligibility checks (CSD, B-BBEE, CIDB, PSIRA), buyer payment-risk signals and AI bid drafting. Search free at [bidcheck.co.za](https://bidcheck.co.za).
