# UseCustory Docs: Condensed Structure Plan
## For a solo founder who needs maximum value with minimum maintenance

---

# THE PHILOSOPHY

You have 48 pages right now. You need ~25-30 that are actually great.
The rule: **Every page must either teach a concept or unblock a task. If it does neither, merge or kill it.**

---

# PAGES TO REMOVE OR MERGE

## Kill entirely (5 pages → 0):

| Page | Why | Action |
|------|-----|--------|
| `/glossary` | Dead redirect, zero value | Delete |
| `/views-and-priorities` | 3,400 chars, basically a TOC | Merge into `/journey-editor` as a short section |
| `/collaboration-and-history` | Too thin, overlaps with `/version-history` | Merge into `/version-history` |
| `/ai-and-automations` | Overlaps with `/ai-workspace-member` | Merge into `/ai-workspace-member` |
| `/journey-view` | Too thin (4,576 chars) | Merge into `/journey-editor` as a section |

## Merge into fewer pages (10 pages → 4):

| Current pages | Merge into | New page title |
|--------------|-----------|----------------|
| `/automation-triggers` + `/automation-filters` + `/automation-actions` | One page | "How automations work" (keep `/automations` as overview) |
| `/persona-detail-editing` + `/persona-linking` | One page | Merge into `/personas` |
| `/notification-delivery-setup` + `/notifications` | One page | "Notifications" |
| `/impact-vs-effort-view` + `/table-view` | One page | Merge into expanded `/journey-editor` |

## Result: 48 pages → ~33 pages (before additions)

---

# PAGES TO ADD (4 new pages)

| New page | Purpose | Target length | Priority |
|----------|---------|---------------|----------|
| "What is a customer journey?" | Teach the concept from zero | 600-800 words | #1 |
| "How Custory works" (visual overview) | Show the mental model + 1 screenshot | 400-600 words + diagram | #2 |
| "Security & privacy" | One-pager for evaluators | 300-500 words | #3 |
| "Build your first journey" (mini-tutorial) | Bridge quickstart → real usage | 800-1000 words | #4 |

## Result: 33 + 4 = ~37 pages total (down from 48, but higher quality)

---

# RECOMMENDED FINAL STRUCTURE

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📘 UNDERSTAND                    (4 pages)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── What is a customer journey?     [NEW]
├── How Custory works               [NEW - replaces Core Concepts]
├── FAQ                             [EXISTS - expand slightly]
├── Security & privacy              [NEW]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🚀 GET STARTED                   (4 pages)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── Quickstart                      [EXISTS - add screenshots]
├── Build your first journey        [NEW]
├── Workspaces                      [EXISTS]
├── Manage your team                [EXISTS]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🗺️ JOURNEYS                      (5 pages)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── Journeys                        [EXISTS]
├── Journey templates               [EXISTS]
├── AI journey imports              [EXISTS]
├── Nested journeys                 [EXISTS]
├── Journey settings                [EXISTS]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
✏️ THE EDITOR                    (3 pages)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── Editor & views                  [MERGED - editor + views overview + journey/table/impact views]
├── Search and filters              [EXISTS]
├── Editor controls                 [EXISTS]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📋 ITEMS & EVIDENCE              (7 pages)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── Items overview                  [EXISTS]
├── Touchpoints                     [EXISTS]
├── Insights                        [EXISTS]
├── Opportunities                   [EXISTS]
├── Solutions                       [EXISTS]
├── Metrics                         [EXISTS]
├── Item fields & linking           [MERGED]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
👤 PERSONAS                      (1 page)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── Personas                        [MERGED - overview + editing + linking]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🤖 AI                            (4 pages)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── AI workspace member             [EXISTS - absorbs ai-and-automations]
├── Workspace memory                [EXISTS]
├── Slack & Discord AI threads      [EXISTS]
├── MCP server                      [EXISTS - add code examples]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
⚡ AUTOMATIONS                   (3 pages)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── Automations overview            [EXISTS]
├── How automations work            [MERGED - triggers + actions + filters]
├── Automation templates            [EXISTS]
├── Build with AI chat              [EXISTS]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🔌 INTEGRATIONS                  (5 pages)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── Integrations overview           [EXISTS]
├── GitHub                          [EXISTS]
├── PostHog & Stripe                [EXISTS]
├── External tasks                  [EXISTS]
├── Notifications                   [MERGED - notifications + delivery setup]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
💳 ACCOUNT                       (1 page)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
├── Billing and usage               [EXISTS]
```

**Total: ~37 pages** (down from 48, cleaner, stronger)

---

# EXECUTION CHECKLIST

## Phase 1: Quick wins (Do this week — ~4 hours total)

- [ ] **Remove the LLMs.txt callout block from all rendered pages**
      → Keep the /llms.txt endpoint, just remove the visible callout from page content
      → Time: 15 minutes (one config change in Mintlify)

- [ ] **Delete the `/glossary` page**
      → Remove from sidebar nav
      → Time: 5 minutes

- [ ] **Write "What is a customer journey?" page**
      → Use draft below as starting point
      → 600-800 words, no screenshots needed yet
      → Time: 45 minutes

- [ ] **Add 1 screenshot to the Quickstart page**
      → Just the dashboard/journey view — whatever a new user sees first
      → Time: 20 minutes

- [ ] **Add the data model diagram to Core Concepts (or "How Custory works")**
      → Simple box diagram: Workspace → Journeys → Stages → Steps → Items
      → Can be made in Figma/Excalidraw in 15 minutes
      → Time: 30 minutes

- [ ] **Write a 3-line Security & Privacy page**
      → Even a short "Your data is encrypted at rest and in transit. We do not sell customer data. SOC 2 in progress." is better than nothing.
      → Time: 15 minutes


## Phase 2: Merges & structure (Next week — ~3 hours)

- [ ] **Merge persona pages** (persona-detail-editing + persona-linking → into /personas)
      → Copy the best content from sub-pages into one comprehensive personas page
      → Delete the sub-pages, set up redirects
      → Time: 30 minutes

- [ ] **Merge notification pages** (notifications + notification-delivery-setup → one page)
      → Time: 20 minutes

- [ ] **Merge thin view pages into /journey-editor**
      → Add "Views" section to journey-editor with Journey View / Table View / Impact vs Effort as H2s
      → Keep the detail that's useful, cut the padding
      → Time: 30 minutes

- [ ] **Merge automation detail pages** (triggers + actions + filters → "How automations work")
      → Time: 45 minutes

- [ ] **Kill `/ai-and-automations`** — merge useful bits into `/ai-workspace-member`
      → Time: 15 minutes

- [ ] **Kill `/collaboration-and-history`** — merge into `/version-history`
      → Time: 15 minutes

- [ ] **Restructure sidebar** to match the new structure above
      → Time: 30 minutes


## Phase 3: Add remaining value (Within 2 weeks — ~4 hours)

- [ ] **Write "Build your first journey" mini-tutorial**
      → Concrete: "We'll build a Trial-to-Paid journey in 10 minutes"
      → 800-1000 words, 2-3 screenshots
      → Time: 1.5 hours

- [ ] **Rename "Core Concepts" → "How Custory works"**
      → Add the diagram
      → Rewrite intro to be warmer
      → Time: 30 minutes

- [ ] **Add 1 screenshot each to: Journey editor, Items, Automations**
      → Just enough to show the product is real
      → Time: 30 minutes

- [ ] **Add "Next steps" links to the bottom of every page**
      → 2-3 relevant links per page
      → Time: 1 hour (batch across all pages)

- [ ] **Expand FAQ to 15-20 questions**
      → Add: pricing, security, data export, team size, comparison, mobile
      → Time: 45 minutes

- [ ] **Add one code example to MCP server page**
      → JSON config for Cursor or Claude
      → Time: 20 minutes


## Phase 4: Polish (When you have time — ongoing)

- [ ] Add more screenshots gradually (1-2 per week)
- [ ] Record one 3-minute Loom walkthrough
- [ ] Add "Common mistakes" sections to 3-4 more pages
- [ ] Write 2-3 example journey descriptions for the templates page
- [ ] Add a "Last updated" date to key pages

---

# DRAFT: "What is a customer journey?" page

(Copy this, edit to your voice, publish)

```markdown
---
title: "What is a customer journey?"
description: "A plain-English explanation of customer journeys and why they matter for product teams."
---

# What is a customer journey?

A customer journey is the path someone takes from first hearing about your product
to becoming (or not becoming) a successful, paying user.

It's the story of their experience — told from their side, not yours.

## A simple example

Say you run a B2B SaaS tool. A typical journey might look like:

1. **Discovery** — They find you through a blog post or a colleague's recommendation
2. **Evaluation** — They check your website, read the pricing page, maybe start a trial
3. **Setup** — They create an account, connect a tool, invite a teammate
4. **First value** — They complete the action that makes the product click
5. **Retention** — They come back because it solves a real, recurring problem
6. **Growth** — They upgrade, invite others, or adopt more features

Each stage has real moments where customers succeed, get confused, or give up.
Those moments are what you map.

## Why does this matter?

Without a shared map of the customer experience, teams make decisions based on
fragments. Support sees one problem. Product sees another. Marketing tells a
different story. Everyone is partially right and nobody is aligned.

A journey gives your team one shared picture of what customers actually go through.
That makes it faster to agree on what's broken, what matters, and what to fix first.

## What teams do with journey maps

- Identify where people drop off or get stuck
- Prioritize which problems to solve first
- Align product, support, and marketing around the same reality
- Track whether improvements actually work
- Onboard new teammates with a clear picture of the customer experience

## How Custory fits in

Custory is where your team builds, maintains, and works from the customer journey.
It's not a static diagram tool — it's an operating system where evidence, decisions,
and follow-up stay connected to the customer moments they belong to.

→ **Next:** [How Custory works](/core-concepts) — see how journeys, items, and
personas connect in the product.
```

---

# DRAFT: Security & Privacy page (minimal viable version)

```markdown
---
title: "Security & privacy"
description: "How Custory protects your workspace data."
---

# Security & privacy

## Data protection

- All data encrypted in transit (TLS 1.2+) and at rest (AES-256)
- Hosted on secure cloud infrastructure with SOC 2-compliant providers
- No customer data is sold or shared with third parties
- Workspace data is isolated between customers

## Access control

- Role-based access (Owner, Editor, Viewer)
- Workspace-scoped API and MCP keys with configurable expiry
- Invite-only workspace access with join-request approval

## AI and privacy

- AI features use your workspace context only when you invoke them
- Workspace memory is scoped to your workspace and not shared across accounts
- Connected integrations only access what you explicitly authorize

## Questions?

Reach out in [Discord](https://discord.gg/B9pA8YuVf6) or email us directly
for specific security questions, compliance documentation, or DPA requests.
```

---

# PRIORITY SUMMARY

| When | What | Time | Impact |
|------|------|------|--------|
| Today | Remove LLMs.txt callout + delete glossary | 20 min | Immediate cleanup |
| This week | Write "What is a customer journey?" | 45 min | Fills #1 gap |
| This week | Add 1 screenshot to Quickstart | 20 min | Trust boost |
| This week | Add diagram to Core Concepts | 30 min | Comprehension boost |
| This week | Write Security page (short) | 15 min | Buyer trust |
| Next week | Merge pages (personas, notifications, views, automations) | 2-3 hrs | Reduces maintenance |
| Next week | Restructure sidebar | 30 min | Better navigation |
| In 2 weeks | Write "Build your first journey" tutorial | 1.5 hrs | Fills onboarding gap |
| In 2 weeks | Add "Next steps" to all pages | 1 hr | Kills dead ends |
| Ongoing | Add 1-2 screenshots per week | 15 min/wk | Cumulative trust |

**Total initial investment: ~11 hours over 2 weeks**
**Ongoing maintenance: ~30 min/week**

---

*This plan takes you from 48 scattered pages to ~37 intentional pages
that actually teach, orient, and unblock your readers.*
