# LinkedIn-Post-Automator-Public
An open-source system for automating LinkedIn content creation using Claude Cowork (or any AI tool). Built by Nick Sarafa / Light School.

What This Is

A folder-based system that turns your brain dump into one great LinkedIn post. No code required. Just files, prompts, and Claude.

The idea is simple: instead of staring at a blank LinkedIn post every morning, you set up your context once, write your SOPs (prompts), and let AI do the heavy lifting while you keep the creative control.

One post at a time. That's how you 10x your output without burning out.

How It Works

This system has 4 layers (just like any good automation):

1-strategy/     Your game plan. Goals, content types, cadence.
2-context/      Who you are, what you do, how you sound. (Reusable for ANY automation)
3-sops/         Step-by-step prompts for each task in the pipeline.
4-data/         Your raw material. Ideas, past posts, images, blog content.
The Core Pipeline

The default workflow produces one post:

Generate Ideas (SOP 01)    "Give me 5 post ideas"
       |
   Pick One
       |
  Write Post (SOP 02)      Hook + Body + CTA, in your voice
       |
  Post to LinkedIn (SOP 06)
Optional add-ons (when you need them):

SOP 03: Pick an image from your library
SOP 04: Generate an AI image
SOP 05: Generate a carousel (use with Canva connector)
SOP 07: Analyze past post performance
Quick Start (5 minutes)

Step 1: Customize Your Context

Edit the files in 2-context/ to match YOUR brand:

me.md - Your bio, story, values, and beliefs
business.md - What your business does, who you serve, your offers
product.md - Your specific products/programs and CTAs
brand-guidelines.md - Your tone of voice, copywriting rules, design guidelines
Step 2: Add Your Data

Drop files into 4-data/:

content-ideas.md - Brain dump all your post ideas here
past-posts/ - Add your best-performing past posts for reference
posts-i-like/ - Save LinkedIn posts from others that inspire you
brand-images/ - Your photos, logos, graphics
blog-posts/ - Any long-form content to repurpose
Step 3: Write a Post

Open Claude Cowork (or any AI chat), point it at this folder, and say:

"Write me a LinkedIn post."
That's it. Claude reads your context, picks an idea from your bank, writes it in your voice, and gives you a post ready to copy-paste.

Want more control? Try:

"Write a LinkedIn post about [specific topic from your ideas bank]."
Or start from scratch:

"Generate 5 post ideas, then write one about whichever is best for engagement."
Using with Claude Cowork

This system is designed to work beautifully with Claude Cowork:

Select this folder as your workspace in Cowork
Claude automatically has access to all your context, SOPs, and data
Just talk to it naturally: "Write me a LinkedIn post about AI being like anger"
It reads your tone of voice, strategy, and content ideas automatically
When you're happy with the post, say "post it to LinkedIn" (requires Claude in Chrome)
Scheduling (Advanced)

You can use Cowork's /schedule feature to automate daily:

Every weekday at 8am:
- Pick the next unused content idea
- Write a post in my voice
- Save it for my review
Folder Structure

LinkedIn-Post-Automator/
|
|-- README.md                          # You are here
|-- 1-strategy/
|   |-- strategy.md                    # Goals, content types, cadence, what NOT to do
|
|-- 2-context/
|   |-- me.md                          # Your bio, story, values
|   |-- business.md                    # Your business info and offers
|   |-- product.md                     # Your products and CTAs
|   |-- brand-guidelines.md            # Tone of voice, design rules
|
|-- 3-sops/
|   |-- 01-generate-post-ideas.md      # Brainstorm post ideas
|   |-- 02-write-post.md               # Write the post (hook + body + CTA)
|   |-- 03-pick-image.md               # Pick image from your library
|   |-- 04-generate-image.md           # Generate AI image
|   |-- 05-generate-carousel.md        # Create carousel slides
|   |-- 06-post-to-linkedin.md         # Publish or schedule
|   |-- 07-analyze-performance.md      # Review what's working
|
|-- 4-data/
    |-- content-ideas.md               # Your idea bank
    |-- past-posts/                    # Past posts for reference
    |-- posts-i-like/                  # Inspiration from others
    |-- brand-images/                  # Your image library
    |-- blog-posts/                    # Long-form content to repurpose
Why This Approach Works

Context is everything. Most people fail at AI content because they give zero context. This system front-loads all your context (who you are, how you sound, what you sell) so every prompt produces on-brand output.

SOPs are just prompts. If you do something repeatedly, write the prompt once, save it as an SOP, and reuse it forever. This is the new way of working.

One post at a time. Don't overcomplicate it. Generate ideas, pick one, write it, post it. That daily habit is what 10x's your content output over time.

Data compounds. The more past posts, content ideas, and brand images you add, the better the system gets. It learns what works for YOU.

It's portable. This isn't locked into any one tool. Works with Claude, ChatGPT, Gemini, or any AI that can read files. The context and prompts are universal.

Demo Script (For the Lecture)

Show the folder structure - Explain the 4 layers (strategy, context, SOPs, data)
Open Claude Cowork - Select this folder as workspace
Say "Write me a LinkedIn post" - Show it reading context and writing in your voice
Tweak it - "Make the hook punchier" or "add a personal story"
Post it - Copy-paste to LinkedIn or use Claude in Chrome
Show the /schedule feature - "Schedule this to run every morning"
Key takeaway: "You set this up ONCE. Then it works forever. And you can fork this repo and customize it for YOUR brand in 30 minutes."
Fork It, Make It Yours

This is open source. Fork it, customize the context files for your brand, and you have your own LinkedIn automation system in under an hour.

The context files in 2-context/ are designed to be reusable across ANY content automation (newsletters, Instagram, X/Twitter, email sequences). Set them up once, use them everywhere.
