# AGENTS.md — jonathanmccallum-ml (Malayalam mirror of jonathanmccallum.com)

Malayalam mirror site. Same theme and design as the main site (Paper Light),
content translated into Malayalam, meaning-first. Repo: streamjonathan/jonathanmccallum-ml.
Live: jonathanmccallum-ml.pages.dev (Jonathan approved all 50 mirrors live, 22 Nov 2026).
Custom subdomain ml.jonathanmccallum.com comes later, via the dashboard.

## Mission

Mirror jonathanmccallum.com in Malayalam — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## Publishing

Jonathan approved all 50 language mirrors live (22 Nov 2026), so this mirror
goes live on jonathanmccallum-ml.pages.dev with its 5 proof articles.
The custom subdomain ml.jonathanmccallum.com is a later dashboard step. New articles stay drafts
until he approves them.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: respectful plain Malayalam, reader addressed as നിങ്ങൾ (ningal,
  respectful "you"). FLAG for Jonathan: warmer നീ (nee) would change every
  നിങ്ങൾ / നിങ്ങളുടെ form. Jonathan's name is rendered ജോനാഥൻ throughout.
- Names (never vary): Jesus യേശു, God ദൈവം, Christ ക്രിസ്തു, Aslan അസ്ലാൻ,
  Narnia നാർണിയ, Lucy ലൂസി, Digory ഡിഗോരി, Tirian ടിറിയൻ, Adam and Eve
  ആദാം, ഹവ്വാ (Malayalam Bible names), Lewis ലൂയിസ്. Book titles are
  meaning-first Malayalam (നാർണിയയുടെ കഥകൾ, മാന്ത്രികന്റെ മരുമകൻ,
  വലിയ വേർപാട്, ബഹിരാകാശ ത്രയം, അവസാന യുദ്ധം) — no published Malayalam titles
  found, flagged for Jonathan.
- Bible: bread/water of life use the standard Malayalam Bible terms ജീവന്റെ
  അപ്പം / ജീവന്റെ വെള്ളം. "Free will" = സ്വതന്ത്ര ഇച്ഛാശക്തി, flagged
  (alternative സ്വേച്ഛ). "French horn" = ഫ്രഞ്ച് ഹോൺ, flagged.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
