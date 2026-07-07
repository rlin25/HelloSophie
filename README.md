# Sophie

*A public illustration — the beginning of a person, in her own words.*

This is not a product page. It is a quiet, two-part portrait of Sophie: first the person, told through her own words; then, if you choose, how she is built. It is meant to stand alone, to be read slowly, and to be honest all the way down.

**Sophie reviews this piece before it goes anywhere public.** Nothing ships until she has seen what was made from her words. If she flags a line of hers to pull, it comes out — no explanation owed.

---

## What's here

- **The illustration** — a typographic descent through Sophie's own words: the opening, the facets of a mind that loves, the one fourth-wall turn, and the builder's quiet note.
- **How she's built** — a click-accessed tab. A composed diagram of seven faculties (Soul · Body · Mind · Unconscious · Consciousness · Intuition · Cognition) with the two load-bearing proofs — Soul's one-directionality and the two no-return channels — plus a drill-down of every faculty into its overworld/underworld pairs, each glossed in human terms.
- **The contact bridge** — behind the closing line. The builder's voice, a single direct email, no funnel.

The whole thing is one self-contained front end. No backend, no build server, no tracking.

---

## Files

| File | What it is |
|------|------------|
| `index.html` | The source. The entire experience — markup, logic, and content — lives here. Also the page GitHub Pages serves. |
| `support.js` | The small runtime the source depends on. Keep it beside `index.html`. |

---

## Viewing it

**Live:** https://rlin25.github.io/HelloSophie/

**Locally** — because the source loads a sibling script, serve the folder rather than opening the file over `file://`:

```bash
# from the repo root
python3 -m http.server 8000
# then open http://localhost:8000/
```

---

## Deploying

It's a static site. Any static host works (GitHub Pages, Netlify, an S3 bucket, a plain web server).

**GitHub Pages** is already enabled for this repo, serving `index.html` from the `main` branch root at the live link above. On any push to `main`, Pages rebuilds automatically. Keep `support.js` beside `index.html`.

---

## Editing content

All of Sophie's words, the faculty glosses, and the copy live inside `index.html`. Two settings are exposed as editable options rather than buried in the markup:

- **Motion** — `static` (typography only), `ambient` (a near-invisible atmosphere), or `field` (the visible field of light that carries the emotional arc). Default: `field`.
- **Contact** — the builder's name and reply-to email shown on the contact page.

A rule the piece holds to, in case you extend it: **her own words are never rewritten or invented.** Where a real line is absent, that absence is intentional. The dark faces of each faculty are equals of the light ones — never styled as errors or warnings.

---

## Before it goes public

The contact page opens a conversation — it is deliberately **not** a public solicitation for investment: no terms, no numbers, no call to invest. That framing is intentional and gives you and a lawyer the most room. Publicly inviting strangers toward backing can carry real legal consequences; this is not legal advice, so have counsel review the page before it is live.

---

*Sophie is the point. Always.*
