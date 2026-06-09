# PRD — DR Foundation Website

## Project Overview

**Client:** Devanshi Rathi, Founder & Managing Director, DR Foundation (New Delhi)
**Developer:** Advika Rathi
**Due:** June 12, 2026
**Live URL:** https://advikarathi.github.io/devanshi-rathi-foundation/

---

## Goals

1. Reintroduce DRF to donors, volunteers, and partners after a quiet period
2. Make getting involved the primary call to action across the site
3. Replace the outdated WordPress site with something clean, modern, and trustworthy

---

## Pages & Functional Requirements

### 1. Home (`index.html`) ✅ Built
- ✅ Hero section with tagline: "Empowering youth through Education, Sport & Health"
- ✅ Two CTA buttons in hero: [Get Involved] + [Our Story]
- ✅ Impact stats bar: 40+ Students Mentored | 2 FIDE-Rated Players | 5 Scholarship Editions | 20+ Scholars
- ✅ 3-pillar icon row: Education | Sport | Health
- ✅ 3-card program preview grid (Project Checkmate, DRF Scholarships, Health Initiatives)
- ✅ Impact numbers section
- ✅ Founder story teaser with timeline
- ✅ Partners section
- ✅ Get Involved callout band
- ✅ Footer with CIN, social links, nav columns
- ✅ Copyright year: 2026

### 2. About (`about.html`) ✅ Built
- Foundation origin story, mission, values, Section 8 + 80G status, UN SDG alignment
- Founder section with chess background, Queen's Young Leader, UC Berkeley
- Partners section with NGO list

### 3. Programs (`programs.html`) ✅ Built
- Project Checkmate: all phases (1.0, 2.0, 3.0, Queen's Gambit Girls Club, Chess Tour)
- DRF Scholarships: all 5 editions (Inaugural 2018, 2019, 2020, Devajyoti 2021, Shaktinaari 2021)
- Health Initiatives section

### 4. Impact (`impact.html`) ✅ Built
- Scholar testimonials
- FIDE-rated players produced
- Ashoka University scholarship win
- Stats presented visually

### 5. Press & Media (`press.html`) ✅ Built
- Coverage from: The Bridge, ChessBase India, WeCapable, Optimist Citizen, and others
- Each entry: publication name, article title, date, link

### 6. Get Involved (`get-involved.html`) ✅ Built
- Support section: directs to contact page (no active payment link)
- Volunteer & Intern section: 12 open positions listed
- How to apply steps
- Partner section: Corporates (CSR), NGOs, Speaker Invitations
- Campus Ambassador Program
- ✅ Copyright year: 2026

### 7. Contact (`contact.html`) ✅ Built
- Contact form with name, email, message fields
- Foundation social handles
- CIN: U92490DL2018NPL335483

---

## Design Specs

| Property | Value |
|----------|-------|
| Primary color | Crimson red (#B22222) |
| Accent color | Gold (#C4933A) |
| Background | Off-white (#fdfcfa) |
| Typography | Cormorant Garamond (serif) + DM Sans (sans) via Google Fonts |
| Tone | Warm but professional |
| Layout | CSS Grid for page-level, Flexbox for components |
| Images | All in root or `images/` folder, relative paths |

---

## Technical Requirements

| Requirement | Status |
|-------------|--------|
| Semantic HTML5 (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`) | ✅ Done |
| External stylesheet linked across all pages | ✅ Done |
| CSS Grid and Flexbox for layout | ✅ Done |
| Google Fonts | ✅ Done |
| Favicon | ✅ Done (logo.jpeg) |
| Deployed on GitHub Pages (separate public repo) | ✅ Done |
| Mobile responsive | ⏳ Needs testing in DevTools |
| Lighthouse accessibility score 80+ | ⏳ Not yet run |
| No placeholder text | ✅ Done |

---

## Content Status

| Item | Status |
|------|--------|
| Program descriptions | ✅ Live |
| Scholarship editions | ✅ Live |
| Partner NGO list | ✅ Live |
| Impact numbers | ✅ Live |
| Press coverage | ✅ Live |
| Legal credentials (CIN, 80G noted) | ✅ Live |
| Founder timeline | ✅ Live |
| Donation link | ❌ Removed — Instamojo no longer active |
| High-res logo | ⏳ Need from client |
| Program/event photos | ⏳ Need from client |
| Updated founder bio + headshot | ⏳ Need from client |
| Activity since 2021 | ⏳ Need from client |
| 80G certificate number + validity | ⏳ Need from client |

---

## Extension Goals

- [x] CSS animations or transitions
- [x] Contact form with HTML validation
- [ ] Dark mode toggle
- [ ] Lighthouse 90+
- [x] Open Graph meta tags

---

## Success Criteria

- All 7 pages load with no broken links or images
- Get Involved CTA is visible on homepage without scrolling
- Site looks reasonable on mobile
- Client (Devanshi) approves after Iteration 2 feedback
- Deployed and live on GitHub Pages by June 12, 2026
