# DreamTale Website

Static site — no build step, no dependencies.

- **Preview:** open `index.html` in a browser.
- **Deploy:** drag this folder into [Netlify Drop](https://app.netlify.com/drop),
  or `vercel deploy`, or any static host.
- **Waitlist backend:** fill in `window.DREAMTALE_CONFIG` at the bottom of
  `index.html` with your Supabase URL + anon key (safe to publish — the
  waitlist table is insert-only for the public). Until then, signups fall back
  to localStorage so the form still demos correctly.

Files: `index.html` (landing), `privacy.html`, `terms.html` (placeholders —
attorney review required), `assets/img/` (logo + app screens).

The sibling `../demo/index.html` is the interactive app prototype — link it
from campaigns or use it for investor/user demos.
