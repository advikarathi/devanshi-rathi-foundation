# DR Foundation — Devanshi Rathi Foundation

## Client

**Devanshi Rathi** — Founder & Managing Director of the DR Foundation (Devanshi Rathi Foundation), New Delhi. Devanshi is a competitive chess player (Arena International Master), a Queen's Young Leader Highly Commended Runner-Up (2018), and a UC Berkeley graduate (2022). She founded Project Checkmate in 2016 and incorporated the DR Foundation as a Section 8 non-profit in 2018. She is also my sister.

## About the Site

A clean, modern website for the DR Foundation — a Section 8 non-profit that empowers underprivileged and disabled youth across India through chess education, scholarships, and health initiatives.

**Pages:**
- **Home** — mission statement, 3-pillar overview, impact stats, programme previews, donate CTA
- **About** — foundation story, founder bio, partner organisations
- **Programs** — Project Checkmate, DRF Scholarships (5 editions), Health Initiatives
- **Impact** — scholar stories, FIDE-rated players, awards, testimonials
- **Press & Media** — coverage from The Bridge, ChessBase India, WeCapable, and more
- **Get Involved** — donate (80G-certified), volunteer/intern, partner (CSR/NGO)
- **Contact** — contact form with HTML5 validation, legal details

**Key features:**
- Semantic HTML5 (`<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<article>`)
- Shared CSS design system (`shared.css`) with CSS custom properties
- CSS Grid and Flexbox for all layout
- Mobile-responsive with animated hamburger nav (600px breakpoint)
- Google Fonts: Cormorant Garamond + DM Sans
- CSS `@keyframes` fadeUp animations
- Open Graph meta tags on all pages
- Favicon, ARIA labels, `role` attributes throughout
- Contact form with `required`, `type="email"`, `autocomplete` validation attributes

## Live Site

**[https://advikarathi.github.io/devanshi-rathi-foundation/](https://advikarathi.github.io/devanshi-rathi-foundation/)**

## What I Learned

- **CSS Grid and Flexbox in practice** — not just theoretically. Using grid for two-column page heroes and four-column footers, flexbox for nav and card rows, taught me when each is the right tool.
- **Design tokens via CSS custom properties** — centralising colours, font sizes, border-radii, and spacing in `:root` variables in `shared.css` made it fast to stay consistent across 7 pages without copy-pasting.
- **Semantic HTML matters beyond just correctness** — using `<article>` for scholar cards, `<section>` with `aria-labelledby`, and proper heading hierarchy made the document structure obvious and accessible.
- **Mobile-first responsive design** — building the hamburger nav in pure vanilla JS (no libraries) and getting the CSS `@media` breakpoints right at 900px and 600px took more iteration than expected.
- **The interview process shapes everything** — having a real client brief before writing any HTML meant design decisions had a purpose. The three-audience model (donors, volunteers, partners) directly drove the site's information architecture.
- **Performance details add up** — learning that an unused Tailwind CDN import (300 KB) on every page load is a real cost, not a minor issue.
