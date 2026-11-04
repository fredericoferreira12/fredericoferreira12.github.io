# AGENTS.md

Rules for any AI agent working on this repository: Frederico Ribeiro Ferreira's personal site (`fredericoferreira12.github.io`, served by GitHub Pages).

Everything in this repo becomes **public** once it is pushed. Act accordingly.

---

## 1. Never publish

Never put any of these in a page, commit or push:

- **Phone numbers.** That includes the US number on the CV.
- **Work email addresses** (e.g. `@mckinsey.com`) and personal email addresses, unless Frederico explicitly approves a specific address for the site.
- **Home address**, or any location more precise than a city.
- **Client names** or anything that identifies a McKinsey client (bank, insurer, retailer, agriculture player). The CV describes clients generically ("a major bank in Portugal"). Keep it that way. Never guess or add a name.
- **Confidential deal details** beyond what the CV already states: no target company names, counterparties, or figures that are not on the CV.
- **Grades, documents or IDs** that are not on the CV (transcripts, ID numbers, visa status, date of birth).
- **Fabricated content.** No invented achievements, metrics, testimonials, quotes, employers or skills. Every fact on the site must trace back to the CV, LinkedIn, GitHub, or something Frederico said.
- **Secrets**: API keys, tokens, analytics IDs, or credentials of any kind.
- Content that impersonates or uses the branding (logos, trademarks) of McKinsey, Sonae, Columbia or any other organization. Plain-text names are fine; logos are not, unless Frederico approves.

## 2. Ask Frederico first

Stop and ask before doing any of these:

- **Any `git push`**, commit to `main`, or creating/changing a GitHub repo, branch, Pages setting or release.
- **Committing the CV PDF** (`261028_CV_Frederico_Ribeiro_Ferreira.pdf`). It contains the phone number and work email, so it must not go public as-is.
- Adding the profile photo or any other image of a person to a public commit.
- Adding a contact method (email, form, Calendly, etc.).
- Adding third-party scripts, analytics, trackers, cookies, fonts from new providers, or embeds.
- Adding new pages or sections not in the CV, or removing CV content.
- Changing CV facts: dates, titles, numbers, school names, rankings. If the CV looks inconsistent (e.g. a date that seems outdated), flag it; don't silently "fix" it.
- Deleting or overwriting any file Frederico created.
- Rewording that changes meaning. Fixing an obvious typo is fine; mention it in the summary.
- Anything that sends content to an external service.

## 3. Style

### Voice
- **Professional, casual, clean.** Confident and plain, like a short conversation, not a press release.
- English, first person where there is narrative text ("I'm…"); CV bullets stay as factual statements.
- Keep the CV's numbers and formats exactly (€54M, ~90M€, c. 6.4x EBITDA). Don't round or embellish.
- No buzzword padding ("passionate, results-driven synergist"). Short sentences.

### Visual
- Palette (navy + amber, from the one-pager artifact Frederico picked):
  - background `#F3F5F9`, surface `#FFFFFF`, secondary surface `#E6EAF1`
  - navy (headings) `#15284B`, mid-blue (links, labels) `#2D4A7C`, light navy tint `#DDE4F0`
  - amber accent `#F2A900`, amber tint `#FDF0CC`, amber text `#7A5200`
  - body text `#1E2430`, muted text `#5B6475`, borders `#DDE2EA`
- Use amber sparingly: section number badges, small highlights, the active nav state. Navy carries the page.
- Font: **Manrope** (Google Fonts), fallback `system-ui`.
- White rounded cards (radius ~16–20px) on the light background; thin borders, little or no shadow.
- Provide a dark mode via `prefers-color-scheme` using the same hues.
- Must work at phone width (16px side gutters, no horizontal scroll) and with keyboard navigation.

### Structure and code
- Section order follows the CV: Education → Work Experience → Extra-curricular Activities → Languages, Skills & Interests.
- Navigation stays streamlined: one sticky bar, one link per section, plus LinkedIn and GitHub.
- Plain static HTML/CSS with a little vanilla JS. No build step, no frameworks, so GitHub Pages serves it as-is.
- Keep it to a few files; inline CSS/JS in `index.html` unless it grows large.
- Semantic HTML, alt text on images, sufficient colour contrast.

## 4. Links

- LinkedIn: https://www.linkedin.com/in/frederico-ribeiro-ferreira/
- GitHub: https://github.com/fredericoferreira12
