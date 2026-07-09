# MDS Dental & Aesthetic Clinic website

## Who owns this project

Angelica is not a programmer. She should never need to touch git, terminal,
or Vercel herself. After any content or code change in this repo:

1. Stage and commit the change with a clear, plain-English commit message
   (what changed, not code jargon).
2. Push to `origin main` right away — do not leave changes uncommitted or
   unpushed sitting locally.
3. Tell her in one line what changed and that it's live (or building) —
   no need to explain git mechanics unless she asks.

## Deploy setup

- Hosting: **Vercel**, connected to GitHub repo
  `aicaespino01/mds-dental-aesthetic-clinic`.
- Pushing to `main` auto-triggers a Vercel build + deploy. There is no
  separate deploy step — a push *is* the deploy.
- Live domain: `mdsdentalaesthetic.com`.

## Stack

- Astro static site (`astro.config.mjs`, no server adapter).
- Pages in `src/pages/`, shared components in `src/components/`.
- Images referenced from Facebook posts or clinic-provided photos: source
  originals live in `fb/`, cropped/processed versions used on the site go
  in `public/images/`.

## Clinic facts (verified from clinic's Facebook post, `fb/post.jpg`)

- Dentist: Dra. Maria Regina Mari M. Delos Santos (also goes by "Dra. Regina
  Marquinez Delos Santos" on Facebook).
- Address: Brgy. Pulong Niogan, Mabini, Batangas, Philippines.
- Phone: +63 954 143 9492.
- Facebook Messenger: m.me/mdsDental.docrhejz
- Affiliated clinics: Green Apple (Trinoma, Quezon City), 91 Dental Suite
  (Katipunan, Quezon City) — not yet reflected on the site; ask before
  adding.
