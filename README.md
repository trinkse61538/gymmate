# GymMate — Gym Tự Do | Website Concept

A Vietnamese, GymMate-specific, conversion-oriented website proposal for **gymmate.khaitringuyen.com**. This is an independent concept and **not GymMate's official website**. No forms or leads are stored here.

## Positioning and copy
- Officially published positioning: **GYMMATE — GYM TỰ DO / Tự do bắt đầu – Tự do gắn bó**.
- USP: flexible smaller membership packages; no fixed PT sales team; independent trainers welcomed.
- Proof: 4 addresses, actual venue photography, actual logo in venue photography and ModunFit profile.
- No unverified promises about current prices, perks, class timetables or cross-location usage.
- Official lead destination (third-party GymMate listing): https://modunfit.com/dia-diem/gymmate

## Run locally
Open `index.html` in a browser. No frameworks, no bundler, no tracking scripts.

## Publish to a dedicated GitHub Pages repository
1. Create a public repo in `trinkse61538` named `gymmate`.
2. Add `index.html`, `CNAME` and `README.md` at repository root on the `main` branch.
3. Settings → Pages → Deploy from a branch → main / (root) → Save.
4. In your DNS provider for `khaitringuyen.com`, create CNAME `gymmate` → `trinkse61538.github.io` (or use the custom domain host GitHub instructs, if different).
5. In GitHub Pages settings, configure custom domain `gymmate.khaitringuyen.com` and enable **Enforce HTTPS** when certificate is ready.
6. Until GymMate authorizes use, keep the 'independent concept' banner and the `noindex,nofollow` meta tag. Do not position as the official site.

## Brand / media sources
- Official GymMate ModunFit profile: https://modunfit.com/dia-diem/gymmate
- Venue images from `modunfit.com/wp-content/uploads/2026/09/` and `modunsport.com/assets/includes/upload/images/project/Gym/`.
- Original logo appears in GymMate source photography. Header uses a typographic interpretation of the brand wordmark, **not an official vector SVG**; replace with official logo SVG/PNG sent by GymMate before production.
- Media is **hot-linked** for the concept only. Replace with licensed, optimized local AVIF/WebP assets after obtaining permission.
- Terms, contact info and offers should be reconfirmed with GymMate before a public launch.

## Notes
- Responsive, keyboard navigable, semantic HTML, native FAQ, mobile navigation, four-location filter, phone links, map links, accessible CTAs, OG/SEO tags.
- The brand images rely on external hosts and may become unavailable. A production site requires local assets and usage authorization.
- GitHub Pages hosts public static assets only; CRM forms, membership systems and account actions would require separate secure backend integration.
