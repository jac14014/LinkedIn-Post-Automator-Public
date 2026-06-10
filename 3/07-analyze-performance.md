# SOP 07: Analyze Past Post Performance

## Purpose
Review your recent LinkedIn posts to understand what's working and refine your strategy.

## How to Use in Cowork
Ask Claude: "Analyze my recent LinkedIn post performance"

## Prompt

```
You are a LinkedIn analytics strategist for Nick Sarafa.

Read these files for context:
- 1-strategy/strategy.md (current strategy)
- 4-data/past-posts/ (past post examples)

I'm going to share my recent LinkedIn post performance data. Analyze it and tell me:

1. **Top Performers**: Which posts got the most engagement? What do they have in common?
2. **Underperformers**: Which posts flopped? What patterns do you see?
3. **Hook Analysis**: Which hooks stopped the scroll best? Why?
4. **Content Type Breakdown**: Which content types (story, hot take, educational, etc.) perform best?
5. **CTA Effectiveness**: Which CTAs drove the most action?
6. **Posting Time**: Any patterns in when posts perform best?
7. **Recommendations**: 3-5 specific changes to make next week based on the data.

Be direct. Don't sugarcoat what's not working. Give me specific, actionable feedback.

DATA:
[PASTE YOUR LINKEDIN ANALYTICS DATA HERE]

You can get this data from:
- LinkedIn Analytics dashboard (linkedin.com/analytics)
- Screenshot your post stats
- Or manually list: Post title | Impressions | Likes | Comments | Reposts | CTR
```

## How to Collect Data
1. Go to your LinkedIn profile
2. Click on "Analytics" or view each post's stats
3. For each post from the last 2-4 weeks, note:
   - Post topic/hook
   - Impressions
   - Engagement (likes, comments, reposts)
   - Any link clicks or DMs received
4. Paste into the prompt above

## Tracking Template
Save your data in `4-data/past-posts/` using this format:

```
## [Date] - [Post Topic]
- Hook: [First line of the post]
- Type: [Story / Hot Take / Educational / etc.]
- Impressions: [number]
- Likes: [number]
- Comments: [number]
- Reposts: [number]
- DMs received: [number]
- Notes: [what you think worked or didn't]
```
