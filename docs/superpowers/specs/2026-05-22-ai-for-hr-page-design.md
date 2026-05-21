# AI for HR Landing Page — Design Spec

**Date:** 2026-05-22  
**URL:** `/ai-for-hr/` → `Website/ai-for-hr/index.html`  
**Purpose:** Warm credibility page sent to HR prospects Craig has already reached out to. Not a lead-gen page — establishes expertise, provides genuine value, reinforces the "let's meet" conversation already in progress.  
**Reference model:** teachmeto.ai/ai-for-hr/ — adapted for DHM design system and Australian context.

---

## Design System

Match `Website/voice-agents/index.html` exactly:

- **Fonts:** Plus Jakarta Sans (headings/body), JetBrains Mono (labels/tags)
- **Colors:** `--accent #4f6df5`, `--feat-teal #0d9488`, `--feat-orange #d96a3b`, `--feat-purple #7c5cbf`, `--feat-rose #d94f7a`, `--feat-amber #b8860b`
- **Backgrounds:** `--bg #fafaf8` (light sections), `--bg-dark #111111` (dark sections)
- **Cards:** white bg, 1px border, 16-20px border-radius, hover lift, coloured top accent line
- **Layout:** max-width 1120px container, sticky dark nav, fadeUp animations on hero elements
- **Nav:** same dark sticky nav as voice-agents page, with "AI for HR" as active link highlight

---

## Page Sections

### Section 1 — Hero (dark background)

- **Pill label:** "AI for HR Professionals" (accent colour)
- **H1:** "Your Team Is Already Using AI. Let's Make Sure They're Doing It Right."
- **Subhead:** "Practical guidance on the AI tools making a real difference in HR — and the guardrails every team should have before they go all-in."
- **CTA button:** "Get in Touch" → `mailto:craig@darkhorse.marketing`

---

### Section 2 — Stats (dark background, continues from hero)

- **H2:** "AI Is Already in Your Organisation"
- **Body copy:** "Research shows 46% of organisations now use AI in HR. But the reality on the ground is messier — 88% of employees are already using some form of AI at work, and 80% of them are using tools their employer hasn't approved."
- **Bold callout:** "The question isn't whether your team is using AI. It's whether they're doing it safely."
- **3 stat cards** (dark bordered, accent number colour):
  - `46%` — of organisations use AI in HR *(SHRM, 2026)*
  - `80%` — of workers use unapproved AI tools *(UpGuard / HR Dive)*
  - `77%` — have pasted sensitive data into AI *(LayerX Research)*

---

### Section 3 — Use Cases (light background)

- **H2:** "Practical Use Cases"
- **Subhead:** "AI won't replace HR. But it will save you hours on the work you're already doing."
- **2×2 card grid** (white cards, coloured top accent line per card, icon + title + 3 bullets):

| Card | Accent colour | Title | Bullets |
|------|--------------|-------|---------|
| 1 (top-left) | `--feat-teal` | Communication & Documentation | Rewrite difficult emails with the right tone / Turn rough notes into professional memos / Draft disciplinary documentation (anonymised) |
| 2 (top-right) | `--feat-orange` | Training & Onboarding | Generate 90-day onboarding checklists by role / Create training outlines and quiz questions / Practice difficult conversations with AI role-play |
| 3 (bottom-left) | `--feat-purple` | Recruiting & Job Descriptions | Draft and refine job descriptions in seconds / Flag biased language automatically / Generate role-specific interview questions |
| 4 (bottom-right) | `--accent` | Policy Research & Compliance | Use AI to summarise legislation and regulations with citations / Research Fair Work Act obligations faster / Start at 80% instead of starting from zero |

---

### Section 4 — Data Safety (dark background)

- **H2:** "Where Is Your Data Safe?"
- **Subhead:** "Not all AI plans are equal. The tier you choose determines how your data is protected."
- **3 tier comparison cards:**

| Tier | Colour label | Price | Bullets | Examples |
|------|-------------|-------|---------|----------|
| Free & Individual | Red/rose | $0–20/mo | Data may be used for model training / Human reviewers may see your input / Consumer terms of service only | ChatGPT Free/Plus, Gemini Free/Advanced, Claude Free/Pro |
| Team / Business | Amber/yellow | $25–30/user/mo | Data NOT used for training / Business data protections and admin controls / SOC 2 compliance | ChatGPT Team, Claude Team, M365 Copilot, Workspace Gemini |
| Enterprise | Green/teal | Custom pricing | Contractual data guarantees / Custom retention, SSO, audit logs / Australian Privacy Act compliance | ChatGPT Enterprise, Claude Enterprise, Vertex AI |

- **Warning banner** (amber, full-width): "⚠️ The minimum for sensitive employee data: Team/Business tier at $25+/user/month."

---

### Section 5 — AI Policy (light background)

- **H2:** "Your AI Policy Can Start on One Page"
- **Subhead:** "You don't need a 20-page governance document. Cover these five things."
- **5 full-width numbered rows** (icon + bold title + one-line description):
  1. **Approved Tools** — Which AI tools are allowed? Which are not?
  2. **Prohibited Data** — What can never go into an AI tool? (personal information, employment records, legal matters)
  3. **Required Review** — All AI output must be reviewed by a human before use.
  4. **Documentation** — When AI is used for decisions, it should be noted.
  5. **Transparency** — Employees should know when AI was used in processes that affect them.

---

### Section 6 — CTA (dark background)

- **H2:** "Let's Talk About What This Looks Like for Your Team"
- **Body:** "Already thinking about AI for your HR function? I work with businesses across Australia to make it practical, safe, and actually useful."
- **CTA button:** "Email Craig" → `mailto:craig@darkhorse.marketing`

---

## AU Localisation Notes

- All "-ize"/"-ize" spellings → "-ise" (organisation, anonymised, etc.)
- "HIPAA BAA" → "Australian Privacy Act compliance"
- "PII, PHI" → "personal information, employment records"
- "Sensitive business data" → "sensitive employee data"
- State comparison (Missouri vs Arkansas) → removed, replaced with Fair Work Act reference
- Prices remain USD (tools are global, pricing is USD)

## What's NOT on this page

- No lead capture / email opt-in (may be added later)
- No pricing for DHM services
- No testimonials (can be added later)
- No optin for resource kit or slide deck
