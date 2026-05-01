# Global Talent Visa Website

Premium static website for a UK Global Talent Visa consultancy focused on profile strategy, evidence positioning, endorsement support, and visa guidance.

## Live Website

Live link: https://global-talent-visa.netlify.app/

## Project Overview

This project is a conversion-focused multi-page static website built for a consultancy that supports high-achieving professionals applying under the UK Global Talent route.

The site is positioned as a premium advisory brand rather than a generic visa agency. Messaging is built around:

- profile strength
- evidence-led case strategy
- endorsement-body awareness
- recommendation letter quality
- end-to-end support from route review to visa filing

The website includes a main landing page, printable support resources, and dedicated package pages for Basic, Standard, and Premium service tiers.

## Live Goals

Primary goals:

- Generate consultation enquiries
- Capture qualified Global Talent leads
- Build trust through strong positioning and clear service structure

Secondary goals:

- Educate potential applicants about the route
- Support package comparison during sales conversations
- Provide printable resources for client follow-up

## Pages Included

### Main entry point

- `index.html`
	Redirects to the main landing page for easier deployment and root access.

### Main landing page

- `global-talent.html`
	Premium conversion-focused landing page with:
	- sticky header navigation
	- hero section
	- applicant pain points
	- evidence-first solution model
	- services grid
	- audience positioning
	- package preview
	- process summary
	- testimonials placeholders
	- FAQ section
	- contact and consultation CTA block

### Printable support pages

- `global-talent-pricing.html`
	Printable pricing guide with package comparison, positioning, upgrade path, and buying guidance.

- `global-talent-checklist.html`
	Printable evidence checklist covering CV, profile materials, recognition, recommendation planning, identity documents, and statement inputs.

- `global-talent-process.html`
	Printable roadmap explaining the Global Talent process from consultation through endorsement and visa filing.

### Package detail pages

- `global-talent-basic.html`
	Details the Basic package for route-fit clarity and initial profile review.

- `global-talent-standard.html`
	Details the Standard package for evidence strategy, dossier structure, and stronger case preparation.

- `global-talent-premium.html`
	Details the Premium package for joined-up support across review, evidence strategy, endorsement preparation, and visa-stage coordination.

## Design and Build Notes

- Static HTML project
- Tailwind CSS loaded via CDN
- Minimal vanilla JavaScript
- Mobile-first responsive layout
- Premium consultancy visual direction
- Print-friendly layouts for pricing, checklist, and roadmap pages
- Internal navigation across all major pages

## Contact Information Used On Site

- Email: uddin@uplesk.com
- WhatsApp: +44 7481 866697
- Telegram: +44 7481 866697

## File Structure

```text
.
├── index.html
├── global-talent.html
├── global-talent-pricing.html
├── global-talent-checklist.html
├── global-talent-process.html
├── global-talent-basic.html
├── global-talent-standard.html
├── global-talent-premium.html
├── README.md
└── plan.md
```

## Running Locally

Because this is a static site, no build process is required.

Options:

1. Open `index.html` directly in a browser.
2. Open `global-talent.html` directly if you want to bypass the redirect entry point.
3. Serve the folder with any lightweight static server if preferred.

Example using Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Deployment

The project is deployed as a static site.

- Live production URL: https://global-talent-visa.netlify.app/
- Root entry file: `index.html`

This structure is compatible with common static hosting platforms such as Netlify, GitHub Pages, Vercel static deployments, or any basic web server.

## Messaging Guardrails

The content is designed to stay within these boundaries:

- no guarantee of endorsement
- no guarantee of visa approval
- no hype-heavy or legal-template messaging
- no generic low-cost agency positioning
- emphasis on profile quality and evidence logic

## Intended Audience

The website targets:

- digital technology professionals
- senior engineers and product leaders
- AI, data, and technical specialists
- founders and startup operators
- researchers and academics
- other credible high-achievement professionals exploring the UK Global Talent route

## Notes

- `plan.md` contains the original build brief used to structure the site.
- Placeholder testimonials are still present and should be replaced with approved client quotes when available.
- Tailwind is loaded via CDN for simplicity in this version.

## Repository

GitHub repository: https://github.com/muhammadsalauddin/Global-Talent-visa.git