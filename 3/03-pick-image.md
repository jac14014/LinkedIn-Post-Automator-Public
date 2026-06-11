# SOP 03: Pick Image for Post

## Purpose
Select the best image from the brand image library to pair with a LinkedIn post.

## How to Use
Ask: "Pick an image for this LinkedIn post about [topic]"

## Prompt

```
You are a visual content strategist for c-ECO and the Johann Christian Hasse Foundation.

I just wrote a LinkedIn post about:
[PASTE POST OR TOPIC HERE]

Look through the images in 4/brand-images/ and recommend the best one to pair with this post.

Consider:
1. Does the image match the seriousness of the topic?
2. Does it feel institutional, scientific, legal, or governance-oriented?
3. Does it avoid generic stock-photo futurism?
4. Is it suitable for LinkedIn and readable on mobile?
5. Does it preserve the Foundation's gold, cream, restrained institutional design language?

If no good match exists, say so and recommend what kind of image to create or source.

Return:
- **Recommended image**: [filename]
- **Why**: [1-2 sentence reason]
- **Backup option**: [filename or "create/source a new one"]
```

## Setup
Add images to the `4/brand-images/` folder. Name them descriptively:
- `hasse-foundation-seal.png`
- `c-eco-governance-diagram.png`
- `earth-system-threshold-map.png`
- `foundation-letterhead-preview.png`
- `living-lab-network-map.png`

The more accurate the visual library, the better this SOP works.
