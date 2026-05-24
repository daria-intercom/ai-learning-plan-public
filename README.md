# AI Learning Plan for Product Designers

A curated, ruthlessly filtered curriculum for product designers moving into AI work — built around the question *"what do I actually need to know to be a Staff-level AI designer?"*

Live at **[ai-learning-plan-public.vercel.app](https://ai-learning-plan-public.vercel.app/)** (or whatever URL you've deployed it to).

## What's in it

Five stages plus a "listen while you walk" bucket for podcasts:

- **Listen while you walk / run** — commute-friendly podcast picks
- **Stage 1: Foundations** (~9h) — LLM internals, retrieval/RAG, agent architecture & harnesses
- **Stage 2: How practitioners think** (~8.5h) — eval discipline, building patterns, AI product sense
- **Stage 4: Practice** (~3h) — a mock AI design exercise + writing your own design philosophy doc
- **Stage 5: Long-term** (weeks) — textbook, deeper video courses, ongoing newsletters

(Stage 3 in the original personal version was "voices from inside the team" — internal docs only available to people at one specific company. Removed here, so numbering jumps.)

## Curation principle

Every item earns its slot. The filter is **high information density per minute, weighted toward content that teaches you something you wouldn't pick up just by working in the field**. That means:

- No outside-in VC analyst takes on companies you already track
- No founder-promo / podcast self-brag
- Pre-2024 tactical AI content treated as suspect (the market moves too fast)
- Prefer technical depth over GTM commentary
- Mixed modality on purpose — long-reads, video lectures, visual essays, podcasts — matched to what suits the topic

## How to use it

1. Open the site. Work top to bottom — the stages are roughly sequenced by foundation → applied → practice → long-term.
2. Check items off as you finish them. Progress is stored in your browser's `localStorage`, so it persists per-device but doesn't sync across machines.
3. Click any stage heading to collapse/expand the section.
4. There's a reset button at the bottom if you want to start over.

No accounts, no tracking, no backend.

## Running locally

It's a static HTML file. Open `index.html` in your browser, or serve it:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying your own copy

The repo is wired for Vercel out of the box:

```bash
vercel --prod
```

Or drop the files on any static host (GitHub Pages, Netlify, Cloudflare Pages, etc.).

## Sources

Every item links to the original author. Credit goes to them. If something's broken or stale, open an issue.

## License

[MIT](LICENSE) — fork it, edit it, share it.
