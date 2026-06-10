# SOP 06: Post / Schedule to LinkedIn

## Purpose
Take the final post (text + image/carousel) and publish or schedule it to LinkedIn.

## How to Use in Cowork
Ask Claude: "Post this to LinkedIn" or "Schedule this post for tomorrow at 9am"

## Option A: Manual Post
1. Open LinkedIn (linkedin.com or the app)
2. Click "Start a post"
3. Paste the post text from SOP 02 output
4. Attach the image (from SOP 03/04) or carousel PDF (from SOP 05)
5. Click "Post" or use LinkedIn's built-in scheduler (clock icon)

## Option B: Automated via Claude Cowork + Browser
If you have Claude in Chrome connected:

```
Go to LinkedIn and create a new post.
Paste this text:
[PASTE POST TEXT]

Attach this image: [path to image file]

Schedule it for [DATE] at [TIME] or post it now.
```

## Option C: Automated via Scheduling Tool
Use a tool like:
- **Buffer** (buffer.com) - Free tier available
- **Typefully** (typefully.com) - Great for LinkedIn
- **Publer** (publer.io)
- **Hootsuite** (hootsuite.com)

Copy the post text + image, paste into the scheduling tool, pick your date/time, and schedule.

## Option D: Claude Cowork Scheduled Task
Use the /schedule skill to set up a daily automation:
```
Every weekday at 8:00 AM:
1. Read the next unused post idea from 4-data/content-ideas.md
2. Run SOP 02 to write the post
3. Run SOP 03 to pick an image
4. Save the output to a "ready-to-post" folder
5. Notify me to review and publish
```

## Best Practices
- Post between 8-10am in your target audience's timezone
- One post per day, every weekday
- Engage with comments within the first hour (algorithm boost)
- Don't edit the post after publishing (resets the algorithm)
