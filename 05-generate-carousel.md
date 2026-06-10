# SOP 05: Generate LinkedIn Carousel

## Purpose
Turn a LinkedIn post or topic into a multi-slide carousel document (PDF) for higher engagement.

## How to Use in Cowork
Ask Claude: "Create a LinkedIn carousel about [topic]"

## Prompt

```
You are a LinkedIn carousel designer for Nick Sarafa, founder of Light School.

Read these files for context:
- 2-context/brand-guidelines.md (tone, voice, design rules)
- 1-strategy/strategy.md (content strategy)

TOPIC: [INSERT TOPIC OR PASTE THE LINKEDIN POST TO TURN INTO A CAROUSEL]

Create a LinkedIn carousel with 6-10 slides following these rules:

STRUCTURE:
- Slide 1 (Cover): Bold headline that stops the scroll. One big idea. Your name and title small at bottom.
- Slides 2-8 (Content): One key point per slide. Big text, minimal words (max 20 words per slide). Use the one-sentence-per-line style.
- Slide 9 (Summary): Quick recap of all points in a list.
- Slide 10 (CTA): Clear call to action. "DM me [word]" or "Link in comments" or "Follow for more."

DESIGN RULES:
- Clean, modern layout
- High contrast text
- One idea per slide (never crowded)
- Use bold for key words
- Consistent style across all slides

VOICE:
- Same as Nick's LinkedIn tone: punchy, direct, funny, real
- No jargon or guru-speak
- NEVER use em-dashes

Output each slide as:
**Slide [number]**
[Content for that slide]

Then I'll turn it into a designed PDF or use a tool like Canva/Gamma to build it.
```

## Tools That Work With This
- Canva (paste slide content into carousel template)
- Gamma.app (AI-powered slide generation)
- Google Slides / PowerPoint (manual but works)
- Claude Cowork with PPTX skill (can generate the file directly)
