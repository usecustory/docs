# Custory Documentation Audit
## Strategic, Implementation-Ready To-Do List

---

## A. Missing or Underdocumented Product Concepts

### A1. "Signals" — the concept the website sells hardest — has no docs page

**Issue:** The marketing site uses "signals" as a core pillar (scattered signals, customer signals, connected signals, signal sources). It's used 30+ times across marketing pages. The docs never define what a signal is, where signals come from, or how they relate to items.

**Why it matters:** A new user reads "connect scattered signals" on the website, signs up, opens the docs, and cannot find the word "signal" explained anywhere. The mental model breaks immediately.

**What should change:** Create a dedicated concept page: "What are signals in Custory?" explaining that signals = raw inputs (analytics events, support conversations, revenue changes, feedback) that become structured items (insights, touchpoints, metrics) when placed on the journey.

**Effort:** Medium

---

### A2. "Living system" / "Operating system for customer journeys" — the core positioning — is barely reflected in docs

**Issue:** The website positions Custory as an "operating system" and "living system" repeatedly. The docs never explain what this means practically. The closest is a brief mention on "How Custory works" but it doesn't explain the concept as a distinct mental model.

**Why it matters:** This is the single most important differentiator from Miro/Notion/whiteboards. If the docs don't explain what makes Custory "living" (automations keep it current, AI maintains it, work connects back to it), the user doesn't understand the product category.

**What should change:** The "How Custory works" page should open with a clear explanation of what "living system" means: the journey updates as your product evolves because signals flow in, automations run, AI helps maintain it, and shipped work connects back. Then explain the static model (workspace → journey → stage → step → item) as the structure underneath.

**Effort:** Low

---

### A3. Prioritization workflow is a major website selling point but underdocumented

**Issue:** The website dedicates significant space to "Prioritized Work" — impact vs. effort views, keeping priorities tied to customer moments. The docs have a brief mention in the Editor/Views page but no dedicated guidance on how to actually prioritize in Custory.

**Why it matters:** "How do I prioritize what to work on?" is the question teams ask after mapping. The docs don't answer it.

**What should change:** Add a practical page: "Prioritize with customer context" covering: how to use impact/effort fields, how the priority view works, how to run a weekly prioritization review, and how opportunities flow into solutions.

**Effort:** Medium

---

### A4. "Connected Stack" narrative is fragmented

**Issue:** The website presents the connected tool stack as a unified value pillar (signals in from PostHog/Stripe, work out to GitHub/Linear/Jira, communication through Slack/Discord). The docs have separate integration pages but no connecting narrative explaining the philosophy.

**Why it matters:** A user who reads "Custory connects your stack" needs to understand the mental model: signals flow IN, the journey is the decision layer, and work flows OUT. Without this framing, each integration page feels like a feature checkbox.

**What should change:** The integrations overview page should open with a 3-sentence explanation of the signal → journey → execution flow, then group integrations by role (signal sources, execution targets, communication channels, AI clients).

**Effort:** Low

---

### A5. No "use cases" or "workflows" documentation

**Issue:** The website describes several concrete workflows (weekly journey pulse, PostHog drift monitoring, GitHub PR refresh). The docs have automation template pages but no broader "how teams actually use Custory week-to-week" content.

**Why it matters:** After setup, users ask "what do I do on Monday morning?" The docs have no answer.

**What should change:** Create a "Weekly workflows" or "How teams use Custory" page with 3–4 concrete rhythms: weekly journey review, signal triage, sprint planning with journey context, shipping and connecting back.

**Effort:** Medium

---

### A6. AI journey import is a key onboarding feature but buried in sidebar

**Issue:** The website prominently sells "paste a URL, connect a repo, or describe your product and Custory drafts stages and steps." This is the primary onboarding hook. In the docs, it's a sub-page under "Journey editor" tab, not part of the "Get started" flow.

**Why it matters:** The #1 "aha" moment for new users is probably seeing their product turned into a journey automatically. The docs bury this under editor mechanics instead of making it the first thing in the getting-started flow.

**What should change:** Reference AI import prominently in the Quickstart page (step 2 or 3). Consider moving it from "Journey editor" sidebar into "Get started" or at minimum cross-linking heavily from the Quickstart.

**Effort:** Low

---

## B. Website/Docs Positioning Mismatches

### B1. Website tone is confident and outcome-focused; docs tone is neutral and feature-descriptive

**Issue:** Website says "Build product experiences that turn customers into advocates." Docs say "What this is. This is the fastest path to a useful Custory setup." The website sells outcomes; the docs describe mechanics.

**Why it matters:** The docs should sustain the confidence of the website. A user who was excited by the website should feel that same expert energy in the docs, not a shift into bland technical writing.

**What should change:** Page openers should start with what the user will be able to do, not what the page "is." Example: Instead of "What this is: This page explains the core objects," write "After this page, you'll understand exactly how customer evidence flows from raw signal to shipped improvement in Custory."

**Effort:** Low (rewrite first paragraph of each page)

---

### B2. Website emphasizes speed and lean teams; docs feel heavyweight

**Issue:** Website repeatedly says "lean teams," "ship faster," "without heavyweight process." The docs, while not long, feel process-heavy because of repeated structural sections (What this is / Why it matters / Common mistakes / What good looks like) on every single page.

**Why it matters:** The repetitive structure makes 7 pages feel like 17. A lean team scanning docs wants fast answers, not the same template 48 times.

**What should change:** See section D below for specific heading fixes. The broader fix: not every page needs all 4 structural bookends. Use them selectively.

**Effort:** Medium

---

### B3. Website heavily features automation templates with names and descriptions; docs are more abstract

**Issue:** The website lists specific templates by name (Active team member for Slack, Weekly journey pulse, PostHog event drift, GitHub merged PR refresh) with one-line descriptions. The docs automation-templates page is more abstract about categories.

**Why it matters:** Concrete template names are scannable and help users self-select. If the docs match the specificity of the website, users can find the exact template they need.

**What should change:** The automation-templates docs page should mirror the website's specificity: list each template by name, one-line description, what it does, when to use it.

**Effort:** Low


---

## C. Docs Structure Improvements

### C1. The "Understand" section has only 4 pages — not enough to bridge website → product

**Issue:** "Understand" contains: Custory documentation (index), What is a customer journey?, How Custory works, FAQ. A user coming from the website needs more bridging content before jumping into "Get started."

**Why it matters:** The website explains a new product category. The docs jump from "here's what a journey is" to "here's how to set up your workspace." There's no page that says "here's what Custory does differently and why you should care" — the docs equivalent of the website's hero section.

**What should change:** Add 1–2 pages to "Understand": a "What Custory does" page (the docs version of the website pitch — 300 words, practical, confident) and optionally a "Key concepts at a glance" page that gives a one-paragraph definition of every core term (stage, step, touchpoint, insight, opportunity, solution, metric, persona, signal, automation).

**Effort:** Medium

---

### C2. Sidebar organization hides the learning path

**Issue:** The sidebar groups pages by product area (Journey editor, AI & automations, Integrations) which makes sense for reference but not for learning. A new user doesn't know they should read Items before Touchpoints before Insights before Opportunities.

**Why it matters:** The reading order matters. The item types build on each other. Touchpoints ground the journey; insights capture learning; opportunities frame problems; solutions propose fixes; metrics validate. This chain is invisible in the current sidebar.

**What should change:** Within the "Items and evidence" group, add a brief "reading order" note at the top of the Items page, or reorder the sidebar to match the logical flow. Also consider a "Concepts" learning path link from the index page.

**Effort:** Low

---

### C3. No "after your first journey" guidance

**Issue:** The onboarding flow is: Quickstart → Build your first journey → (nothing). There's no page that says "Now that you have a journey, here's what to do next: invite the team, connect Slack, set up one automation, run your first review."

**Why it matters:** Post-setup abandonment. The user built a journey, felt good, then didn't know the next action.

**What should change:** Add a "What to do after your first journey" page or section at the end of "Build your first journey" that routes users to: invite team, connect one integration, set up one automation, run a first review.

**Effort:** Low

---

## D. Heading and Language Improvements

### D1. Replace "What this is" / "Why it matters" pattern with page-specific headings

**Issue:** At least 12 pages use the exact same opening headings: "What this is" and "Why it matters." This pattern appears on: How Custory works, Quickstart, Build your first journey, Items, Personas, AI workspace member, Automations, MCP server, Journey editor, Item fields, and more.

**Why it matters:** These headings are invisible to scanners. They don't tell you what you'll learn. They make the docs feel templated and robotic. Worse: "Why it matters" as a heading trains the reader to skip it because it sounds like filler.

**What should change:** Replace with page-specific, question-based or statement-based headings.

**Rules for docs page headings:**

1. The H1 is the page title (usually the concept name)
2. The first section heading should answer "what will I understand after reading this?" — make it specific to the page topic
3. Never use "What this is" — instead use "What [concept] means in Custory" or "How [concept] works" or just start with the explanation (no heading needed if it's the natural first paragraph)
4. Never use generic "Why it matters" — instead use "Why [specific concept] matters for [specific user goal]" or fold the "why" into the opening paragraph
5. Use action-oriented or question-based headings: "When to use X," "How X connects to Y," "What to do first"
6. "Common mistakes" is fine — it's specific enough
7. "What good looks like" is fine but could be stronger as "A good [concept] in practice" or "Example of a strong [concept]"

**Example rewrites:**

| Page | Current | Better |
|------|---------|--------|
| How Custory works | "What this is" | "The core model: workspace → journey → step → item" |
| How Custory works | "Why it matters" | "Why the model matters for your team" |
| Quickstart | "What this is" | "What you'll set up" |
| Quickstart | "Why it matters" | (delete — fold into opening paragraph) |
| AI workspace member | "What this is" | "How AI participates in your workspace" |
| AI workspace member | "Why it matters" | "What changes when AI is a team member" |
| MCP server | "What this is" | "What the MCP server lets you do" |
| Automations | "What this is" | "What automations do in Custory" |
| Items | "What this is" | "What items are" |
| Personas | "What this is" | "How personas work in Custory" (already exists as a later heading — move it up) |

**Effort:** Low (systematic find-and-replace with page-specific rewrites)

---

### D2. "What good looks like" / "Common mistakes" are useful but formulaic

**Issue:** Nearly every page ends with "Common mistakes" and "What good looks like." The content in these sections is often genuinely useful, but the repetition across all 48 pages makes them feel like padding.

**Why it matters:** By page 5, a reader skips these sections reflexively.

**What should change:** Keep them on the 8–10 most important concept pages (Items, Touchpoints, Insights, Opportunities, Solutions, Metrics, Quickstart, Build your first journey). Remove or fold into the body on shorter/mechanical pages (Workspaces, Team management, Editor controls, Notifications). When keeping them, vary the heading: "Mistakes to avoid," "What a strong [X] looks like," "Common patterns that don't work."

**Effort:** Low

---

### D3. Page openers are passive and feature-descriptive

**Issue:** Most pages open with a neutral description: "Use items to turn a journey from a visual map into an operating system." This is fine but doesn't hook the reader.

**Why it matters:** The first sentence determines whether the reader keeps reading. Busy users need to immediately understand: "Is this page for me right now?"

**What should change:** Open each page with who it's for and what they'll be able to do after reading. One confident sentence. Not marketing. Not hype. Just clarity.

**Examples:**
- Current (Items): "Use items to turn a journey from a visual map into an operating system for evidence, decisions, follow-up, and measurement."
- Better: "Items are how your team captures evidence, frames problems, tracks solutions, and measures progress — all anchored to the customer moment they belong to."

- Current (Automations): "Use Custory automations to turn repeated journey work into scheduled or event-based follow-up."
- Better: "Automations keep your journey current without manual work. They pull signals, create items, notify your team, and trigger follow-up — on a schedule or when something changes."

**Effort:** Low

---

## E. Beginner Education Improvements

### E1. The item chain (touchpoint → insight → opportunity → solution → metric) is never explained as a connected flow

**Issue:** Each item type has its own page explaining what it is. But nowhere does the documentation show the full chain: a touchpoint captures the moment → an insight captures what you learned → an opportunity frames the problem → a solution proposes a fix → a metric validates whether it worked. This chain IS the product.

**Why it matters:** Without this mental model, a beginner creates items randomly. They don't understand why linking matters or what "structured context" actually means in practice.

**What should change:** Add a "How items connect" section (or separate page) with a clear progression explanation and one worked example showing how a single customer problem flows through all five item types. The "How Custory works" page partially does this but it's too abstract.

**Example direction:** "A user drops off at the setup wizard (touchpoint). Your team learns that the third step asks for data they don't have yet (insight). You frame 'reduce setup friction for users without pre-existing data' as the problem to solve (opportunity). You propose a skip-and-come-back-later option (solution). You track setup completion rate as the number that tells you if it worked (metric)."

**Effort:** Medium

---

### E2. No explanation of how to move from "mapping" to "improving"

**Issue:** The docs explain how to build a journey and how to capture evidence. They don't explicitly explain the transition: "You've mapped the journey — now what? How do you use this to actually ship improvements?"

**Why it matters:** This is the #1 risk of journey mapping tools: teams map, feel good, and never act. Custory's product is designed to prevent this (opportunities, solutions, linked work, automations). The docs should make this transition explicit.

**What should change:** Add a section to "Build your first journey" or a standalone page: "From mapping to shipping." Cover: when to stop mapping and start acting, how to identify the first opportunity worth pursuing, how to assign an owner, how to create linked work, how to track whether the fix worked.

**Effort:** Medium

---

### E3. "What is a customer journey?" page is decent but doesn't connect to product thinking

**Issue:** The page explains journeys as a concept but doesn't explain why product teams specifically benefit from journey thinking vs. just looking at funnels, dashboards, or support tickets.

**Why it matters:** The ICP is product teams who already have analytics and feedback tools. They need to understand what journey-level thinking adds on top of what they already have.

**What should change:** Add a brief section: "How journey thinking differs from dashboards and ticket queues." Key point: a dashboard shows what happened; a journey shows where it happened in the customer's experience and what came before and after.

**Effort:** Low

---

### E4. No glossary or quick-reference for terminology

**Issue:** There's a /glossary URL that appears to be empty/minimal. The docs use specific terms (stages, steps, items, touchpoints, insights, opportunities, solutions, metrics, personas, signals, automations) without a single-page reference.

**Why it matters:** When reading any docs page, a user might encounter a term from another page. A glossary gives them a 10-second answer without requiring a full page read.

**What should change:** Create a real glossary page with one-sentence definitions. Keep it scannable. Link each term to its full page.

**Effort:** Low

---

## F. Onboarding Flow Improvements

### F1. Recommended reading order should be explicit

**Issue:** The docs landing page provides three routing options (fuzzy on journeys → concepts page, want mental model → How Custory works, want to set up → Quickstart). But it doesn't give a linear path for "I want to learn everything in the right order."

**Why it matters:** Many users prefer a guided learning path. They want to know: read this, then this, then this, and you'll be productive.

**What should change:** Add a "Recommended reading order" to the docs landing page:
1. What is a customer journey? (2 min)
2. How Custory works (3 min)
3. Quickstart (5 min)
4. Build your first journey (10 min)
5. Items and how they connect (5 min)
6. Connect your first integration (3 min)
7. Set up your first automation (5 min)

**Effort:** Low

---

### F2. "Build your first journey" should be the star page — make it more discoverable

**Issue:** This is actually the best page in the docs. It's practical, concrete, and walked-through. But it's one of five items in the "Get started" sidebar group, visually equal to "Workspaces" and "Billing and usage."

**Why it matters:** This page is the onboarding conversion point. If a user reads this page and follows it, they'll get value from Custory.

**What should change:** Make this page more prominent: larger card on the landing page, first item in the "Get started" section after Quickstart, mentioned in the website's "Help center" link context. Consider renaming to "Your first journey (step by step)" for more clarity.

**Effort:** Low

---

### F3. No "invite your team" guidance in the onboarding flow

**Issue:** The website says Custory is for teams. The docs have a "Manage your team" page, but the onboarding flow (Quickstart → Build first journey) doesn't clearly say when and how to bring teammates in.

**Why it matters:** A product that requires collaboration needs to tell users when to invite others. Too early = chaos. Too late = the journey becomes one person's artifact.

**What should change:** Add a brief "When to invite your team" section to the Quickstart, after the first journey is built. The Quickstart page partially addresses this ("invite a small editor group first") but it's buried.

**Effort:** Low

---

### F4. AI import should be positioned as the default starting path, not an alternative

**Issue:** The Quickstart page describes manual journey creation as the primary path. AI import is mentioned as a tool. But the website positions AI import as THE way to start ("Start from structure instead of a blank page").

**Why it matters:** If AI import produces a useful draft in 30 seconds, it should be step 1. Manual creation should be the fallback for teams who prefer starting from scratch.

**What should change:** In the Quickstart, make AI import the default: "Step 1: Create a workspace. Step 2: Import your first journey from your website or repo. Step 3: Refine the draft." Then mention "prefer to start from scratch? See manual journey creation."

**Effort:** Low

---

## G. Pages That Should Be Added, Merged, or Rewritten

### G1. ADD: "What Custory does" — a docs-specific product overview (not marketing)

300 words. Confident. What the product is, who it's for, what it replaces, what it connects to. This is the bridge between website and docs.

**Effort:** Low

---

### G2. ADD: "Signals — where your customer data comes from"

Explain the concept of signals, how they flow into Custory, what turns them into structured items, and which integrations provide them.

**Effort:** Medium

---

### G3. ADD: "From mapping to shipping — using the journey to improve your product"

The transition page. How to stop mapping and start acting. How to find the first opportunity, assign work, measure results.

**Effort:** Medium

---

### G4. ADD: "Weekly workflows — how teams use Custory in practice"

3–4 concrete weekly rhythms. What to check, what to update, what to review with the team.

**Effort:** Medium

---

### G5. ADD: "Glossary"

One-sentence definitions of every core term. Scannable. Linked to full pages.

**Effort:** Low

---

### G6. REWRITE: "How Custory works" — make the first section about the living system, not the object model

Currently leads with "What this is: This page explains the core objects." Should lead with: "Custory is a living system that keeps your team's understanding of the customer experience current, connected, and actionable. Here's how the pieces fit together."

**Effort:** Low

---

### G7. REWRITE: "Quickstart" — lead with AI import as default path

Reframe so the fastest path (AI import) is primary, manual creation is secondary.

**Effort:** Low

---

### G8. MERGE or CLARIFY: "Automations" and "How automations work"

Two pages covering similar ground. "Automations" is the overview; "How automations work" is the detail. Consider merging into one or making the distinction clearer (the first as "why," the second as "how to build").

**Effort:** Low

---

## H. Quick Wins


### H1. Add screenshots or diagrams to at least 5 key pages

**Issue:** Zero screenshots or diagrams anywhere in the docs. For a visual product with a journey editor, map views, table views, and priority views, this is a major gap.

**Why it matters:** A product that shows a "living journey map" on its website should show that same map in its docs. Users need to see what they're building before they build it.

**What should change:** Add screenshots to: How Custory works (the object model), Journey editor/views, Build your first journey (show the result), Automations (show the builder), AI import (show before/after).

**Effort:** High (requires screenshot creation and maintenance)


**Issue:** Every page renders "Copy page" text twice near the top. This is a Mintlify rendering artifact.

**Why it matters:** Looks broken to human readers.

**What should change:** Fix the Mintlify template configuration to suppress or properly hide this.

**Effort:** Low

---

### H2. Cross-link more aggressively between related pages

**Issue:** Pages often mention concepts without linking to the relevant page. For example, the Automations page mentions integrations but doesn't link to specific integration pages.

**Why it matters:** Users shouldn't have to use search to find the obvious next page.

**What should change:** Audit each page for terms that should link: touchpoints, insights, opportunities, solutions, metrics, personas, automations, integrations, AI, MCP. Add inline links wherever these are mentioned.

**Effort:** Low

---

## I. Top 5 Highest-Impact Fixes

### 1. Replace all "What this is" / "Why it matters" headings with page-specific alternatives (Section D1)
**Impact:** Immediately makes docs feel less robotic, more scannable, more confident.
**Effort:** Low.

### 2. Add the item chain explanation — show how touchpoint → insight → opportunity → solution → metric connects as one flow (Section E1)
**Impact:** This IS the product mental model. Without it, users don't understand structured context.
**Effort:** Medium.

### 3. Create a "Signals" concept page and weave the term into existing docs (Sections A1, A4)
**Impact:** Bridges the biggest gap between website language and docs language.
**Effort:** Medium.

### 4. Reframe Quickstart to lead with AI import as the default first action (Sections A6, F4, G7)
**Impact:** Aligns docs onboarding with the product's actual fastest path to value.
**Effort:** Low.

### 5. Add screenshots to the 5 most important pages (Section H2)
**Impact:** A visual product with zero visual docs is a trust gap. Even 5 screenshots would fix most of it.
**Effort:** High.

---

## Implementation Priority Order

If implementing sequentially, do this:
1. **Week 1 (Low effort, high impact):** D1 heading rewrites + D3 page openers + H1 remove llms.txt callout + H3 fix copy page artifact
2. **Week 2 (Medium effort, high impact):** E1 item chain page + A1 signals page + G6 rewrite How Custory works opener + F4 reframe Quickstart
3. **Week 3 (Medium effort, medium impact):** A3 prioritization page + A5 weekly workflows page + E2 mapping-to-shipping page + G5 glossary
4. **Week 4 (High effort, high impact):** H2 screenshots (5 key pages) + C1 expand Understand section + F1 reading order

---

*End of audit.*
