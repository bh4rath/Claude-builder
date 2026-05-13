# Claude Builder Portal

A 21-day AI learning portal. Built with vanilla HTML/CSS/JS — no frameworks, no build tools.

## Structure

```
claude-builder/
├── index.html   ← full portal (CSS + JS embedded)
└── data.json    ← 21 days of content
```

## Adding content

Edit `data.json`. Each day has five fields:

```json
{
  "day": 1,
  "title": "Problem Framing",
  "idea": "The core concept...",
  "howToClaude": "Prompt template to paste into Claude",
  "stepByStep": ["Step 1", "Step 2", "Step 3", "Step 4", "Step 5"],
  "deploy": "What to share with the cohort",
  "reflection": "The reflection question",
  "status": "pending",
  "date": "2026-05-13"
}
```

Set `"status": "complete"` to mark a day done.

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages → Source: Deploy from branch → main / root**
3. Site will be live at `https://bh4rath.github.io/claude-builder/`
