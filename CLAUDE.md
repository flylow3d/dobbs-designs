# Dobbs Designs & Collectibles — Spec Website (build #15, FAMILY build)

> Part of It's Already Done Web Co. New builds: read
> `C:\Users\flylo\Documents\Website Business\PLAYBOOK-building-client-sites.md` first.

## What this is

Website for **Dobbs Designs & Collectibles** — a home-based 3D-printing and
hand-painting shop in **Marion, Indiana**, run by **Melissa Dobbs** — the
CLIENT'S SISTER (Joseph's sister). Built from public info like every spec
build, with the concept-preview disclaimer until Melissa reviews it — but
unlike cold pitches, she can supply corrections/photos/prices directly.

## Verified facts (sources: her Facebook posts via OG meta, Instagram testimonial, market/venue pages)

- Facebook: facebook.com/DobbsDazzlingDesigns (page name: "Dobbs Designs &
  Collectibles"; handle differs — possibly a former name, unconfirmed)
- Page intro (verbatim): "3d printed, with hand painted designs. Available
  at markets or by order."
- Owner: Melissa Dobbs (self-named publicly in her Sept 2024 giveaway post)
- Location: **Marion, Indiana** — home-based; offers "North Marion" local
  pickup. CITY-LEVEL ONLY on the site — never a street address
- Products w/ dated example prices (one-off 2024 FB sale posts, NOT a
  standing price list — label as examples):
  - Glow-in-the-dark frogs $6 · glow skeleton keychains $3 · standing
    skeleton glow toy ("kid durable") $5 · glow skeletons $7 (Oct–Dec 2024)
  - Articulated fan-art figure $15 (Dec 2024) — see IP rule below
  - Fan-art spheres/display brackets (Feb 2026 posts) — see IP rule below
  - Custom & memorial prints (customer pet-memorial testimonial, May 2024,
    Instagram @itsmellieeeee: "Found someone who does 3D printing and asked
    if they could replicate Maui... I love it! Thanks to Dobbs Designs &
    Collectibles ❤️")
  - Collab: 3D printed tree w/ wire-wrapped ornaments with Wire and Ice
    Studio (Swayzee, IN)
- Verified market appearances (2024–2026): Red Rooster Fall Market
  (Converse), Fall Festival at Matter Park (Marion), Mama Pearson's
  Soaporium Spring Market (Gas City); in the local maker circle around
  The Hive / Hive Mind Market (Marion) — Hive vendor status UNCONFIRMED
- Ordering: Facebook messages; North Marion pickup for local orders
- Active April 2024 – February 2026 (page posts)

## WORDING RULES (do NOT violate)

- **IP SAFETY (critical): never name Groot, Marvel, Pokémon, Pokéball, or
  any trademarked character/brand on the site.** Her documented bestsellers
  are fan-art prints of licensed characters; a public site advertising them
  by name creates legal exposure a craft booth doesn't. Use "fan-art
  favorites — ask at the booth," "articulated figures," "collector spheres."
  FLAG THIS TO MELISSA — it's her risk decision, not ours.
- No street address, ever (home-based). "Marion, Indiana" + "North Marion
  pickup" is the maximum. No phone/email (none public) — Facebook links only
- Prices shown are labeled as dated examples from past sale posts
- Don't assert: founding date, "Dobbs Dazzling Designs" as former name,
  Hive vendor status, dragons/flexis/planters/geodes (unverified), printer
  brands/materials, follower counts
- Don't link Instagram @dobbsdesignsllc (likely a different business)
- Melissa's name appears (her own public post) but nothing else personal
- "Handmade" → phrase as "3D printed, then hand-painted" (her own framing)
- Generated imagery = PLACEHOLDERS with an explicit note that her real
  print photos replace them (same rule as Regal Photography). Never generate
  trademarked characters in imagery

## Design language

- **Glow-lab maker studio.** The signature is GLOW — her glow-in-the-dark
  line is the most documented original work. Palette: deep space-indigo
  `#221a35`, glow lime `#b8f34c`, filament magenta `#e055b8`, cyan `#4fd6e0`,
  soft lavender-paper light sections. Dark-first but vivid — distinct from
  Leo Barber (near-black/brass) and TLC (black/electric blue).
- Display: **Bungee** (chunky, playful, maker-toy feel; uppercase-only face)
  + body **Rubik**.
- Signature motifs: **layer lines** (thin repeating horizontal stripes, like
  FDM print layers) as section dividers/texture; **filament-spool roundel**
  brand mark (CSS ring with a center hole); glow-dot accents.
- Structure: proven skeleton re-skinned.

## Pages

```
index.html      Home — hero, what she makes, glow line, custom/memorial, markets teaser
prints.html     The print shelf — glow line, figures, spheres/brackets, customs (example prices, dated)
find.html       Find & order — market appearances, Facebook ordering, North Marion pickup, custom process
css/style.css   single stylesheet
assets/         Gemini PLACEHOLDER imagery (.prompt.txt sidecars gitignored)
```

- GoatCounter analytics on every page (flylow3d.goatcounter.com)
- Relative links only. Repo: flylow3d/dobbs-designs ·
  Live: https://flylow3d.github.io/dobbs-designs/

## Domains (RDAP July 11, 2026)

dobbscollectibles.com, dobbs3d.com, dobbs3dprints.com,
dobbsdazzlingdesigns.com, dobbsdesignsandcollectibles.com ALL AVAILABLE;
dobbsdesigns.com taken. Collision warning: dobbsdesignco.com is an
unrelated scroll-saw woodworking business — prefer a domain with
"collectibles"/"3d" in it to avoid confusion.

## Footer disclaimer (every page)

"**Concept preview.** This is a demonstration website built by It's Already
Done Web Co. to show what Dobbs Designs & Collectibles could look like
online. Melissa hasn't reviewed it yet — details are drawn from public posts
and may be out of date. Product photos are placeholders awaiting photos of
the real prints. Message the shop on Facebook for current items and prices."
