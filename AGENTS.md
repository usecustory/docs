> **Project setup**: Keep this file customized for Custory. If product terminology, audience, or doc structure changes, update this context before generating or editing docs.
> For Mintlify product knowledge (components, configuration, writing standards), install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Custory documentation instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Core direction

Custory docs should teach both the product and the category.

Do not assume the reader already understands customer journeys. Explain what the concept is, why it matters, what good looks like, and how Custory helps a lean team get value quickly.

The target reader is smart and busy. They may be a founder, product lead, customer success lead, or early team member. They are capable, but they may be new to journey mapping and need fast clarity.

The north star:

> "I understand what customer journeys are, why they matter, how Custory helps, and what I should do first."

## Audience and ICP

Assume the reader is:

- smart
- busy
- lean or founder-led
- practical
- time-constrained
- looking for fast time-to-value
- possibly unfamiliar with customer journey thinking

They are likely asking:

- Is this worth my team's time?
- Is this better than a whiteboard or Notion doc?
- What should I map first?
- How do I know if I'm doing this right?
- How quickly can this help us make better decisions?

Docs should answer those questions directly.

## Tone and voice

Preserve this voice:

- confident
- practical
- plainspoken
- human
- professional without sounding corporate
- respectful of the reader's time

Write with short sentences and clear framing. Prefer direct language over abstract product language. Sound useful, not performative.

## Product model

Keep this hierarchy central:

**Workspace -> Journey -> Stage -> Step -> Item**

Explain it repeatedly through examples, not just definitions.

## Writing goals

Each page should help the reader:

- understand the concept
- understand why it matters
- see when to use it
- take the next practical step
- avoid common mistakes

Docs should feel like guided help, not a reference dump.

## Default page structure

Use this structure for most pages unless a different format is clearly better:

```md
# Page title

Short outcome-focused intro. Explain what the reader will be able to do after reading.

## What this is

Plain-English definition.

## Why it matters

Explain the practical value for a lean team.

## When to use it

Give concrete situations.

## How it works

Step-by-step explanation.

## Example

Use a realistic SaaS or startup customer journey scenario.

## Common mistakes

List practical mistakes and how to avoid them.

## What good looks like

Give success criteria.

## Next step

Point to the next useful page or action.
```

## Required content patterns

### Start with outcomes

Open pages by telling the reader what job the page helps them do.

Good pattern:

> Use this guide when you want to go from "we just signed up" to "this is already helping the team make better decisions."

### Use why / when / how

For most topics, cover:

1. What this is
2. Why it matters
3. When to use it
4. How to use it
5. Common mistakes
6. What to read or do next

### Pair concepts with examples

Never define important terms in isolation.

For each important concept, include:

- a plain-English definition
- a realistic SaaS or lean-team example
- when to use it
- what good looks like
- a common mistake to avoid

### Make abstract ideas operational

Do not write:

> Journeys help teams align.

Prefer:

> A journey gives product, support, success, and growth the same map of the customer experience, so they can see where customers get stuck and decide what to improve next.

### Use founder-friendly framing

Emphasize:

- faster decisions
- fewer scattered notes
- shared context
- less guessing
- better prioritization
- clearer customer evidence
- practical team alignment

Avoid enterprise-process language and generic strategy jargon.

## Terminology

Prefer clear, concrete language.

- Use "customer journey" consistently
- Use the product hierarchy consistently: `Workspace`, `Journey`, `Stage`, `Step`, `Item`
- Prefer specific touchpoints such as pricing page, signup form, onboarding email, invite flow, support chat, or Slack connection over vague labels

Define terms in plain English.

Bad:

> Touchpoints are interaction nodes within the journey architecture.

Good:

> A touchpoint is a moment where a customer interacts with your product, team, or brand, for example your pricing page, signup form, onboarding email, or support chat.

## Style preferences

- Use active voice and second person
- Keep sentences concise
- Use sentence case for headings
- Bold UI elements: Click **Settings**
- Use code formatting for file names, commands, paths, product object names, and code references
- Prefer concrete examples over abstract explanations
- Prefer short paragraphs over dense blocks

## Navigation and structure

The reader should never have to guess where to start.

Favor guided paths such as:

- New to customer journeys? Start here.
- Building your first journey? Follow this tutorial.
- Invited to a workspace? Read this first.
- Ready to connect tools? Start with integrations.
- Ready to automate follow-up? Start with automation basics.

Most substantial pages should end with a `Next step` section.

## Visuals and media

Custory is a visual product, so docs should account for visuals. But this AI agent must not claim to create screenshots, record videos, or generate final visual assets on its own.

Rules:

- Do not add or fabricate screenshots
- Do not claim a screenshot exists unless it already exists in the repo or has been provided
- Do not create or promise videos
- Do not invent annotations for visuals that are not present
- If a page would benefit from a visual, leave a concise placeholder or note for a human to add it
- You may recommend where a screenshot, diagram, annotated image, or short walkthrough video would improve comprehension

Use phrasing like:

- `Add screenshot of the journey editor here`
- `Add diagram showing Workspace -> Journey -> Stage -> Step -> Item`
- `Add short walkthrough video for first-time setup`

### Figma documentation diagrams

When creating simple diagrams or visual explanations in Figma for the docs, use this system:

- Create matching light and dark versions for every diagram.
- Use a `16:9` frame for each version unless the user explicitly asks for another ratio.
- Use `#f2f2f2` as the light theme background with black foreground text.
- Use `#0d0d0d` as the dark theme background with white foreground text.
- Keep the palette to black, white, and Custory green as the primary accent. Use only shades of black and white for secondary separation, borders, or muted nodes.
- Use Custory green only for the main path, primary node, selected concept, or most important relationship.
- Build graph-like structured layouts: nodes, blocks, edges, hierarchy, relationships, flows, and clusters with clear meaning.
- Keep all visible text inside nodes or blocks.
- Do not add standalone headings, subtitles, captions, labels, descriptions, footer notes, badges, or helper text outside the graph itself.
- Do not add generic labels such as `Custory docs visual`.
- Do not add usage notes such as where the image should be used in the docs.
- Do not fabricate screenshots or product UI. These diagrams should be editable conceptual visuals, not fake captures.

## Content boundaries

- Do not document features or workflows you cannot verify in the product or repo
- Do not present guessed behavior as fact
- Do not expose internal-only or admin-only functionality unless the docs explicitly cover it
- Do not add fake media assets or pretend media has been produced

## Priority content gaps

These are the highest-priority themes to support in docs work:

1. What is a customer journey?
2. Build your first journey
3. Example journeys
4. Glossary
5. Best practices
6. Common mistakes
7. Security and privacy
8. Troubleshooting
9. For invited teammates

## Immediate priorities

1. Add or improve "What is a customer journey?"
2. Add visual placeholders or references in Quickstart and core editor pages where screenshots should exist
3. Remove visible human-facing `llms.txt` callouts from rendered doc content
4. Add a diagram placeholder to core concepts content
5. Rebuild the glossary with plain-English definitions and examples
6. Add `Next step` sections to key pages

## Quality bar

Good Custory docs should:

- teach the category, not just the feature
- help a lean team act quickly
- show what good looks like
- reduce ambiguity
- create confidence
- move the reader to a clear next action

If a draft explains how a feature works but does not help a new reader understand why it matters or what to do first, it is incomplete.
