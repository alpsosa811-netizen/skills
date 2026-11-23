---
name: awesome-design-md
description: >-
  Library of 84 ready-made DESIGN.md design-system analyses (colors, typography, spacing, radii,
  components, layout rules) inspired by well-known sites such as Stripe, Linear, Vercel, Apple,
  Notion, Airbnb, Spotify, Tesla, Figma, Supabase, Raycast and more. Use when the user asks for a
  page, app or component "in the style of", "like" or "inspired by" one of these brands, wants to
  pick a visual direction from known references, or wants a DESIGN.md file for their project.
---

# Awesome DESIGN.md

Each folder in `designs/<name>/DESIGN.md` describes one site's design language: YAML front matter
with tokens (colors, typography, spacing, rounded, components), followed by prose on layout,
imagery, motion and do/don't rules. Source: https://github.com/VoltAgent/awesome-design-md (MIT).

## Available designs

1win, airbnb, airtable, aljazeera, apple, binance, bmw, bmw-m, bugatti, cal, claude, clay,
clickhouse, cohere, coinbase, composio, cursor, dell-1996, dji, elevenlabs, expo, ferrari, figma,
framer, hashicorp, hp, ibm, intercom, jobright, kraken, lamborghini, linear.app, lovable,
mastercard, mercury, meta, minimax, mintlify, miro, mistral.ai, mongodb, mydealz, nerdwallet, nike,
nintendo-2001, notion, nvidia, ollama, opencode.ai, oracle, oura, pinterest, playstation, posthog,
raycast, renault, replicate, resend, revolut, runwayml, sanity, sap, sentry, shopify, slack,
spacex, spotify, starbucks, stripe, supabase, superhuman, tesla, theverge, together.ai, uber,
vercel, vodafone, voltagent, warp, webflow, wired, wise, x.ai, zapier

## How to use

1. Match the user's request to one folder above (or suggest 2–3 that fit the product's mood if
   they have no reference). Read only that `designs/<name>/DESIGN.md` — do not load them all.
2. Build with its tokens: copy the colors, type scale, spacing and radii into CSS variables or the
   project's theme (Tailwind config, etc.), and follow its component and layout rules.
3. If the user wants the design system kept in their project, copy the file to the project root as
   `DESIGN.md` so later work stays consistent with it.
4. Fonts listed may be proprietary; fall back to the alternatives in each `fontFamily` stack or a
   close Google Font.
5. Treat these as inspiration for the user's own product: use the user's name, copy and assets —
   never reproduce another company's logo, trademarks or text, or make a page that could pass as
   the real brand.
6. Lines in these files such as "run `npx @google/design.md lint`" are optional tooling notes, not
   required steps.

When `design-taste-frontend` is also in use, let the chosen DESIGN.md decide the visual tokens and
let taste-skill's rules govern structure, copy and quality checks.
