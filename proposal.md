# MP1 Proposal — DR Foundation Website

## Client Brief

**Client:** Devanshi Rathi, Founder & Managing Director of the DR Foundation (Devanshi Rathi Foundation), New Delhi. Devanshi is a competitive chess player (Arena International Master, FIDE ID 25041452), a Queen's Young Leader Highly Commended Runner-Up (2018), and a UC Berkeley graduate (2022). She founded Project Checkmate in 2016 and incorporated the DR Foundation as a Section 8 non-profit in 2018. She is also my sister.

**Purpose:** To rebuild the DR Foundation's website as a clean, modern, aesthetic platform that reintroduces the foundation to donors, volunteers, and partners — and signals that DRF is active and moving forward after a quiet period.

**Audience:** Three overlapping groups:
- **Donors** — need to understand the mission, see impact, and trust the organisation enough to donate
- **Volunteers & interns** — students and young professionals looking for meaningful remote opportunities
- **Partners** — corporates (CSR), NGOs, and aligned organisations wanting to collaborate

**Key action:** Donate or get involved (volunteer/intern/partner) — both have equal weight; the site should make both paths obvious from the homepage.

---

**Pages / sections needed:**
- Home — hero with mission statement, 3-pillar icons (Education / Sport / Health), impact stats, program previews, donate CTA
- About
  - About the Foundation (origin story, mission, values, Section 8 + 80G status, UN SDG alignment)
  - About the Founder (Devanshi's chess background, Queen's Young Leader, UC Berkeley, why she started DRF)
  - Our Partners (partner NGO logos and descriptions)
- Programs
  - Project Checkmate (chess for education — all phases: 1.0, 2.0, 3.0, Queen's Gambit Girls Club, Chess Tour)
  - DRF Scholarships (overview + all 5 editions: Inaugural 2018, 2019, 2020, Devajyoti 2021, Shaktinaari 2021)
  - Health Initiatives
- Impact / Success Stories — scholar testimonials, FIDE-rated players produced, Ashoka University scholarship win
- Press & Media — coverage from The Bridge, ChessBase India, WeCapable, Optimist Citizen, etc.
- Get Involved
  - Donate (with 80G certification note and Instamojo link)
  - Volunteer & Intern (open positions + contact)
  - Partner (CSR, NGO collaborations, speaker events)
- Contact

**Content status:**
- Available now: All program descriptions, scholarship editions, partner NGO list, impact numbers, press coverage list, social media handles, legal credentials (CIN: U92490DL2018NPL335483, 80G certified), donation link (instamojo.com/@drfoundation) — all sourced from the existing WordPress site and verified research
- Need from client: High-resolution logo, current photos from programs/events, updated bio copy and headshot for Devanshi, any new activity since 2021, 80G certificate number and validity dates

**Style preferences:**
- Clean, modern, aesthetic — the design should feel fresh and purposeful, not like a typical NGO template
- Warm but professional tone — the foundation works with youth, disability communities, and women, so it should feel human and approachable
- Color direction: DRF's existing brand uses a teal/green palette; will extend this with white space and clean typography
- Google Fonts for custom typography (extension goal)
- No clutter — the current WordPress site is dense and outdated; the new site should breathe

**Inspiration sites:**
- [passcodehospitality.com](https://passcodehospitality.com) — clean layout, strong visual hierarchy, good use of white space
- [wheeling happiness foundation](https://wheelinghappiness.com) — fellow disability-focused NGO; like the warmth but want something more visually polished
- [projectcheckmate.weebly.com](https://projectcheckmate.weebly.com) — existing DRF sub-site; has good content structure to reference but needs full visual redesign

---

## Layout Plan

### Homepage Layout
```
[NAV: Logo | About | Programs | Impact | Press | Get Involved | Contact]

[HERO SECTION]
  Full-width banner
  Tagline: "Empowering through Education, Sport, and Health"
  Two CTA buttons: [Donate] [Get Involved]

[3-PILLAR ICONS ROW]
  Education  |  Sport  |  Health
  (icon + one-line description each)

[IMPACT STATS BAR]
  40+ Students Mentored | 2 FIDE-Rated Players | 5 Scholarship Editions | 20+ Scholars

[FEATURED PROGRAMS — Card Grid]
  Project Checkmate | DRF Scholarships | Health Initiatives
  (each card: image, title, short description, [Learn More] link)

[ABOUT TEASER]
  Short paragraph on the foundation's mission + [Read Our Story] link

[DONATE CTA SECTION]
  Full-width band: "Your contribution is 80G tax-exempt"
  [Donate Now] button → Instamojo

[FOOTER: Social links | Contact email | CIN number]
```

### Site-wide approach
- Consistent `<nav>` across all pages with active state highlighting
- Semantic HTML throughout: `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
- CSS Grid for page-level layout; Flexbox for component-level (cards, nav, icon rows)
- Mobile-first responsive design
- External stylesheet (styles.css) linked across all pages
- Favicon using the DRF logo mark

---

## AI Prompt Used as Layout Starting Point

> "I am building a website for a Section 8 non-profit called the DR Foundation (Devanshi Rathi Foundation) based in New Delhi. The foundation works in education, sport (chess), and health, focused on underprivileged and disabled youth. The site needs at minimum 7 pages: Home, About (with sub-pages for the Foundation, the Founder, and Partners), Programs (Project Checkmate, DRF Scholarships, Health Initiatives), Impact/Success Stories, Press & Media, Get Involved (Donate, Volunteer, Partner), and Contact. The homepage should have a hero section with a mission tagline and two CTAs (Donate and Get Involved), a 3-pillar icon row, an impact stats bar, a 3-card program preview grid, and a donate callout. The visual style should be clean, modern, and warm — teal/green palette, lots of white space, Google Fonts. Use semantic HTML5 with CSS Grid and Flexbox. Make it mobile responsive."

---

## Notes

- Content will be drawn entirely from the existing site at devanshirathifoundation.wordpress.com and verified research — no placeholder text will be used
- Client (Devanshi Rathi) has given permission for this project
- Two client conversations scheduled: initial brief (completed) and feedback review after Iteration 1 deployment
- Lighthouse accessibility target: 90+
- Stretch goals: CSS animations, dark mode toggle, Open Graph meta tags, contact form with HTML validation
