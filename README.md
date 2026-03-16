# Brand Content Generator 
### AI-Powered Twitter Strategy Tool | Google Forms + Zapier + GPT-4

---

## Overview

Brand Content Generator is an AI-powered no-code automation tool that generates a complete, agency-level Brand Twitter Strategy Report for any brand — delivered directly to the user's email inbox within 2-3 minutes of form submission.

---

## Live Tool

| Resource | Link |
|---|---|
| Google Form (Try it) | https://forms.gle/CVNpQdzKUzZgiWJy9 |
| Sample Output — Netflix | https://tinyurl.com/2krj68a6 |
---

## Workflow
```
Google Form → AI by Zapier (GPT-4o mini) → Google Sheets → Gmail
```

### Step-by-Step

1. **Trigger — Google Forms**
User submits brand details via Google Form. The Zap triggers automatically on every new response.

2. **Processing — AI by Zapier (GPT-4o mini)**
All form inputs are passed to the AI with a structured strategic prompt. The AI analyses the brand and generates a complete 8-section Brand Twitter Strategy Report.

3. **Storage — Google Sheets**
The AI-generated report along with all form inputs is saved automatically as a new row — maintaining a full log of every brand processed.

4. **Delivery — Gmail**
The complete report is sent directly to the email address provided in the form within 2-3 minutes of submission.

---

## Input Fields (Google Form)

| Field | Purpose |
|---|---|
| Email Address | Report delivery destination |
| Brand Name | Core identity signal for AI inference |
| Industry / Category | Sets competitive context and content norms |
| Campaign Objective | Shapes content mix (Engagement / Promotion / Awareness) |
| About Products | Provides themes and value proposition context |
| Preferred Tone | Anchors language style across all 8 report sections |

---

## Output — 8-Section Brand Twitter Strategy Report

| Section | Content |
|---|---|
| 1. Brand Voice Summary | Tone, target audience, communication style, social media uniqueness |
| 2. Brand Dos and Donts | 3 content guardrails for what to do and avoid |
| 3. Competitor Landscape | 3 competitors analysed with differentiation strategy |
| 4. Content Pillar Strategy | 4 pillars with content type and example tweet per pillar |
| 5. 10 On-Brand Tweets | Each with purpose label and optimal IST posting time |
| 6. Viral Tweet Ideas | Meme angle, hot take, interactive tweet |
| 7. Hashtag Bank | 10 curated hashtags — branded, trending, and niche |
| 8. Brand Voice Scorecard | Rated out of 10 across 4 strategic dimensions |

---

## Brand Voice Analysis Approach

To generate truly on-brand content, I identified what actually defines a brand's voice — not just tone, but personality, audience relationship, competitive positioning, and social media uniqueness.

1. **Voice is more than tone** — I approached brand voice as a combination of personality, audience relationship, and competitive positioning. This ensured analysis went beyond surface-level descriptors like "witty" or "bold."

2. **Strategic input design** — The intake form was designed to capture the exact signals a brand strategist would gather in a client onboarding — industry context, product details, campaign goal, and preferred tone — kept minimal so any brand could complete it in minutes.

3. **Context-driven inference** — The AI combines all inputs simultaneously rather than treating tone in isolation. A food delivery brand and a luxury brand can both be "witty" — but surrounding context makes their voice completely different.

4. **Brand Voice Summary as foundation** — Section 1 defines tone, audience, communication style, and social media uniqueness first — so every tweet, content pillar, and hashtag generated afterwards stays strategically consistent.

5. **Competitor context built in** — Brand voice only means something relative to competitors. The competitor landscape section shows how the brand should differentiate its voice on Twitter — not just what to say, but how to sound differently from others in the same space.

---

## Prompt Design

The prompt was engineered to simulate a senior brand strategist receiving a client brief — forcing the AI to produce strategic, agency-quality output rather than generic content.

**Key prompt engineering decisions:**

1. **Role framing** — "You are a senior brand strategist at a top social media agency" sets the quality standard for the entire output.

2. **Plain text enforcement** — Output explicitly instructed to avoid asterisks and markdown to ensure clean, readable email delivery.

3. **India-specific timing** — Best posting times specified in IST targeting Indian audience behaviour: 6-9pm evening peak, 8-9am morning commute, 12-1pm lunch break.

4. **Purpose labelling** — Every tweet tagged as Awareness / Engagement / Conversion / Retention to demonstrate funnel thinking.

5. **8-section structure** — Mirrors a real agency deliverable covering every dimension from voice analysis to scorecard.

---

## Full Prompt Used
```
You are a senior brand strategist at a top social media agency. A client has submitted their brand details. Generate a complete professional Brand Twitter Strategy Report. Output in plain text only. No asterisks, no hashtags, no markdown, no special characters.

Brand Name: [Brand Name]
Industry: [Industry/Category]
Campaign Objective: [Campaign Objective]
About Products: [Tell us about your products]
Preferred Tone: [Preferred Tone]

SECTION 1 - BRAND VOICE SUMMARY
- Tone & Personality (2 lines)
- Target Audience (1 line)
- Communication Style (1 line)
- What makes this brand unique on social media (1 line)

SECTION 2 - BRAND DOS AND DONTS
Dos: 3 things this brand should always do on Twitter
Donts: 3 things this brand should never say or do

SECTION 3 - COMPETITOR LANDSCAPE
Name 2-3 competitor brands on Twitter.
For each competitor:
- Their tone in one line
- One thing they do well
Then write: How [Brand Name] should differentiate itself on Twitter

SECTION 4 - CONTENT PILLAR STRATEGY
Define 4 content pillars for this brand.
For each pillar:
- Pillar name
- What type of content goes here
- Example tweet idea

SECTION 5 - 10 ON-BRAND TWEETS
For each tweet:
Tweet: [under 280 characters with hashtags]
Purpose: [Awareness / Engagement / Conversion / Retention]
Best day and time to post (India audience, IST timezone):
Mix: 3 engaging, 3 promotional, 2 witty/meme-style, 2 informative

SECTION 6 - VIRAL TWEET IDEAS
3 high-potential viral tweets:
- 1 meme/pop culture angle
- 1 hot take (brand safe)
- 1 interactive (poll or fill in the blank)

SECTION 7 - HASHTAG BANK
10 best hashtags (mix of branded, trending, niche)

SECTION 8 - BRAND VOICE SCORECARD
Rate out of 10:
- Clarity of voice: /10
- Audience connection: /10
- Content variety: /10
- Viral potential: /10
- Overall score: /10
2 lines of reasoning for overall score.
```

---

## Tools Used

| Tool | Purpose |
|---|---|
| Google Forms | User input interface |
| Zapier | No-code workflow automation |
| AI by Zapier (GPT-4o mini) | Brand analysis and report generation |
| Google Sheets | Response logging and storage |
| Gmail | Automated report delivery |

---
