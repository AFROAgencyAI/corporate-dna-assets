# corporate-dna-assets

Public static assets for Nutrigene Corporate DNA landing pages (GHL paste, etc).

## 815 Know Your Genes

Pages base:

```
https://afroagencyai.github.io/corporate-dna-assets/815
```

All page images are **WebP**.

| Path | Use |
|------|-----|
| `images/to-wire/*.webp` | Hero, why, genes, productivity |
| `images/caffeine-vs-cardiovascular.webp` | Graph |
| `poster/*.webp` | Career Talent cover, PLANET mockup |
| `quiz/index.html?embed=1` | Stress quiz lightbox iframe |

## LLM activity posters (Little Life Moment)

```
https://cdn.jsdelivr.net/gh/AFROAgencyAI/corporate-dna-assets@main/llm-activities/
```

23 programmes · 43 WebP posters · RIASEC-tagged catalogue in [`llm-activities/README.md`](llm-activities/README.md).

Use each folder’s `cover.webp` as the main event card image.

## 816 PaMaMe Connect Day

Pages base:

```
https://afroagencyai.github.io/corporate-dna-assets/816
```

jsDelivr:

```
https://cdn.jsdelivr.net/gh/AFROAgencyAI/corporate-dna-assets@main/816/{path}
```

| Path | Use |
|------|-----|
| `logo/pamame-logo.webp` | PaMaMe mark for the nav lockup (288x120, alpha) |
| `poster/review-belle.webp` | Poster frame, review video 1 (swimming) |
| `poster/review-joyce.webp` | Poster frame, review video 2 (outdoor / parkour) |
| `poster/review-amanda.webp` | Poster frame, review video 3 (piano to dance) |

Review videos themselves stay on the GHL filesafe CDN. Posters live here so the
video elements can run `preload="none"` and download nothing until tapped.

Activity posters for this page come from `llm-activities/{folder}/cover.webp`.
