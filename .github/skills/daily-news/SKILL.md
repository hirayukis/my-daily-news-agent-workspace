---
name: daily-news
description: Gather, prioritize, and summarize daily news for a specified topic, region, or set of sources. Use this when the user wants a current-events briefing, a news digest, or help monitoring important stories.
argument-hint: "[topic] [region] [sources]"
---

# Daily News Skill

Use this skill when the user wants a concise daily news briefing or help tracking important current events.

## Workflow

1. Clarify the scope.
   - Ask which topics matter most, such as technology, AI, business, politics, or local events.
   - Default to an AI and technology focus with a Japan-oriented lens unless the user asks for something else.
   - Confirm the region or language if relevant.
   - Ask for preferred sources if the user has a shortlist.

2. Gather recent information.
   - Prefer recent and reputable sources.
   - Focus on stories with clear impact, public relevance, or strong novelty.
   - If the user asks for a broad summary, include a small number of high-signal stories rather than a long list.

3. Synthesize the briefing.
   - Produce a short overview with 3 to 7 bullets or a compact summary.
   - Include the headline, why it matters, and any notable implications.
   - If facts are uncertain, say so clearly and note the ambiguity.

## Output format

- Title: a short label for the briefing
- Summary: 2 to 3 sentences capturing the main theme
- Key stories: 3 to 7 bullets with headline and significance
- Takeaways: 2 to 3 concise points for the user
- Follow-up: one optional question or suggested next step
