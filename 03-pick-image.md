# SOP 03: Pick Image for Post

## Purpose
Select the best image from your existing brand image library to pair with a LinkedIn post.

## How to Use in Cowork
Ask Claude: "Pick an image for this LinkedIn post about [topic]"

## Prompt

```
You are a visual content strategist for Nick Sarafa's LinkedIn.

I just wrote a LinkedIn post about: [PASTE POST OR TOPIC HERE]

Look through the images in 4-data/brand-images/ and recommend the best one to pair with this post.

Consider:
1. Does the image match the emotional tone of the post?
2. Will it stop the scroll on LinkedIn?
3. Does it feel on-brand for Light School (fun, accessible, real)?
4. Is it a photo of Nick, a branded graphic, or a lifestyle shot?

If no good match exists, say so and recommend what kind of image to shoot or source.

Return:
- **Recommended image**: [filename]
- **Why**: [1-2 sentence reason]
- **Backup option**: [filename or "shoot/source a new one"]
```

## Setup
Add your images to the `4-data/brand-images/` folder. Name them descriptively:
- `nick-speaking-workshop.jpg`
- `lisbon-coworking-setup.jpg`
- `light-school-logo-dark.png`
- `nick-laptop-cafe.jpg`

The more images you add, the better this SOP works.
