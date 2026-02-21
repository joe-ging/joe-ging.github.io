# 🏠 joe-ging.github.io — Portfolio Site Plan

> **Status:** Redirect to macbase (temporary)
> **Goal:** Personal developer portfolio + project showcase hub
> **Priority:** After macbase launch (Week 3+)

---

## Current State

- `joe-ging.github.io` → redirects to `/macbase` (temporary, for launch)
- `joe-ging.github.io/macbase` → macbase landing page (live)

---

## Future Vision: Developer Portfolio

### Main Page (`joe-ging.github.io`)

**Sections to include:**
- [ ] Hero with name, title, one-liner ("Builder. Chess player. Entrepreneur.")
- [ ] Short bio — multilingual background, chess + tech journey
- [ ] Featured projects grid (cards linking to subpages)
- [ ] Entrepreneurship timeline (chess programs, Beijing adventures, tech journey)
- [ ] Skills / tech stack
- [ ] Links (GitHub, LinkedIn, etc.)

### Project Subpages

| Project | URL | Status |
|---|---|---|
| macbase | `/macbase` | ✅ Live |
| JL Intelligence Parser | `/jl-intelligence-parser` | 🔒 Private (has API key) |
| Chess AI Coach | `/chess-ai-coach` | ❌ Not yet |
| Future projects... | `/project-name` | — |

---

## Design Direction

- Same dark theme as macbase (consistency across brand)
- Minimal, premium feel — not a generic template
- Mobile responsive
- Fast — static HTML/CSS, no framework needed

---

## Content to Prepare (Margot)

- [ ] Professional headshot or avatar
- [ ] 2-3 sentence bio
- [ ] List of projects with one-line descriptions
- [ ] Key milestones for entrepreneurship timeline
- [ ] Social links to include

---

## When to Build

**Not now.** Focus is on macbase launch (Days 2-5). Portfolio site is a Week 3+ task, after macbase is shipped and getting feedback. The redirect serves its purpose for now — anyone who finds your GitHub profile lands on macbase.

---

## Technical Notes

- Repo: `joe-ging/joe-ging.github.io` (branch: `master`)
- Currently contains: `index.html` (redirect), `style.css`, `Fun.png`
- Each project gets its own repo with GitHub Pages from `/docs`
- Main site stays in the `joe-ging.github.io` repo
