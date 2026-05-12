# Mohammed Ali Salim — Portfolio

> **Live site:** **<https://mhmdali98.github.io/testp/>**

A futuristic, fully responsive portfolio for **Mohammed Ali Salim** —
Senior Frontend Engineer · Full-Stack Web Developer · AI Engineer.
Built as a single static `index.html` so it can be hosted on GitHub
Pages with zero build tooling.

---

## Highlights

- **Bilingual** (English ↔ Arabic) with full RTL support and persistent
  language preference
- **Light / Dark theme** with smooth cross-fade
- **Animated hero** with typewriter role rotation (Frontend → Full-Stack
  → AI Engineer → …), floating profile photo with dual rotating rings,
  orbital tech tags, and animated stat counters
- **Sticky top nav** with active-section pill, scroll progress bar, and
  full-screen mobile drawer
- **Live background**: animated grid, blurred orbs, floating particles,
  and a cursor-following glow
- **Skills cards** for Frontend, Backend, AI · ML · Data, Mobile,
  Databases and Tools — long lists collapsed behind a `+N more` toggle
- **Interactive timeline** with eight roles (Dot Tech → Enjaz LLC),
  accurate dates, durations and locations
- **Featured Projects**: 8 rich cards with descriptions, tech stacks
  and live URLs — including AI work (RAG, NLP, KNN, Computer Vision)
- **Tech Pulse**: live news feed pulled from Hacker News, sorted
  newest-first, with three tabs (Tech / AI / Research)
- **AI guide bot** that appears on scroll, narrates each section in
  context, and briefly spotlights the active title
- **RAG-style chat** that answers strictly from a curated, on-device
  knowledge base — no API key, no hallucinations, just facts from
  the site itself
- **Visitor counter** in the footer
- **Printable HTML CV** at `cv.html` with a Print/Save-as-PDF button
- **Mobile-first**: optimised touch sizes, full-screen chat panel,
  100dvh-aware, respects `prefers-reduced-motion`

## Tech stack

Static HTML/CSS/JS — no framework, no build step:

- `Inter`, `Space Grotesk`, `JetBrains Mono`, `Noto Sans Arabic` via
  Google Fonts
- Pure CSS animations + IntersectionObserver for scroll behaviour
- Hacker News Algolia API for the news feed
- Abacus / counterapi.dev (with fallback) for visitor counter
- SVG icons inlined

## Files

| File | Purpose |
|------|---------|
| `index.html` | The portfolio (all CSS + JS inline) |
| `cv.html` | Printable HTML CV (A4, ATS-friendly) |
| `Mohammed-Ali-Salim-CV.pdf` | Original PDF resume |
| `profile.jpg` | Profile photo |
| `.github/workflows/` | GitHub Pages deploy on push to `main` |

## Local preview

```bash
git clone https://github.com/mhmdali98/testp.git
cd testp
python3 -m http.server 8000
# open http://localhost:8000
```

A simple HTTP server is needed (rather than `file://`) so the news
feed, visitor counter and `localStorage`/`sessionStorage` features
all work correctly.

## Contact

- 📧 [salamali731@gmail.com](mailto:salamali731@gmail.com)
- 📱 [+964 782 218 1094](tel:+9647822181094)
- 💼 [LinkedIn](https://www.linkedin.com/in/mohammed-ali-almaliky-177568157)
- 👨‍💻 [GitHub @mhmdali98](https://github.com/mhmdali98)
- 📍 Karbala, Iraq

## License

Personal portfolio — content (text, photos, CV) © 2026 Mohammed Ali
Salim. Reuse with attribution is welcome for the structural code.
