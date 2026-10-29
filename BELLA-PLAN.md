# Bella Care Aesthetics — Demo + CMS Plan (2026-10-29)
## Pitch issue (verified live 2026-10-29, bellacare.com.pk)
- Do NOT pitch as "no website" — they have a live WordPress site with 22 services and 2 branches.
- Pitchable problems: (1) demo shop/product pages still live with Lorem ipsum and $ demo prices; (2) no PKR service prices anywhere — HydraFacial says only "competitive pricing, varying by customization"; (3) duplicate/mismatched service pages (carbon-laser-facial/-2/-3, hifu-treatment/-2; carbon-laser page shows fat-dissolving content); (4) footer still Copyright 2024 and garbled homepage sentences; (5) no treatment + branch + date/time booking flow (WhatsApp button only).
- Offer mapping: clean WordPress rebuild/clean-up (remove demo shop, fix duplicates/mismatches, update footer), one clean services list, price-on-consultation pages until owner sets prices, booking with branch + date/time, local SEO for Gulberg III and Johar Town, plus the CMS in admin.html.
- Tracker estimate for rebuild/clean-up: PKR 35,000–60,000 (estimate only); SEO from PKR 10,000/month separate. No PKR prices are invented in the demo.
## Demo architecture (same limit as SkinLab demo)
- GitHub Pages is static only. This is a front-end demo CMS: data in browser localStorage under bc_* keys (separate from SkinLab's sl_* keys on the same origin), no server, no real login, no real notifications/payments. Production needs a backend/WordPress build.
- Files: index.html (public demo), admin.html (CMS: Dashboard, Appointments, Services, Packages, Staff, Customers, Gallery, Reviews, Promotions, Blog, Pages, Reports, SEO, Settings), BELLA-PLAN.md (this file).
- Verified brand colours used: #9a563a (rust), #121f38 (navy headings), #555555 (body), #ffffff, #EFF1F5. Logo is recreated as text in the demo, not the clinic's logo file.
- Services seeded: all 22 from the live Services page, price = On consultation (live site lists no PKR price), duration default 60 min (owner to confirm). Staff seeded as placeholder branch teams only — no staff names invented (none were publicly named in the check).
- Contact (verified): phone 042 32314419, WhatsApp 0344 4296916 (wa.me/923444296916, different from header phone), email bellacare.pk@gmail.com, Gulberg III 42 Ghalib Rd Block E-1, Johar Town 386 Block J-3 Phase 2, hours Mon–Sun 10:00–22:00.
- Tests: JS syntax checked with node --check; availability logic tested — Sunday allowed (open 7 days), before 10:00 and 21:30+duration+buffer blocked, overlap logic inherited from SkinLab CMS and re-tested there.
- Outstanding: enable GitHub Pages (main, root) for the new repo, verify live URLs, owner to confirm prices, durations, staff names, breaks, and cancellation policy.
