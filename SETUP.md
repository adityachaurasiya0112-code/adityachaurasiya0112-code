# Setup Instructions

## 1. Create the special profile repo
GitHub profile READMEs only work in a repo that has the **exact same name as your username**.
- Go to GitHub → New repository
- Name it exactly: `adityachaurasiya0112-code`
- Make it **Public**
- Check "Add a README file"

## 2. Upload the files
Push/upload these files to the root of that repo, keeping the folder structure:

```
adityachaurasiya0112-code/
├── README.md
├── welcome-banner.svg
└── .github/
    └── workflows/
        └── snake.yml
```

## 3. Enable the snake workflow
1. Go to your repo → **Settings → Actions → General**
2. Under "Workflow permissions", select **Read and write permissions** → Save
3. Go to the **Actions** tab → select "Generate Snake Animation" → click **Run workflow** (to trigger it the first time manually, don't wait for the midnight cron)
4. After it finishes (~1 min), it will auto-create an **`output`** branch containing the animated snake SVG
5. Refresh your repo — the snake animation in the README will now render your real contribution graph

## 4. Done
Your profile page (`github.com/adityachaurasiya0112-code`) will now show:
- The ocean/blue animated header
- The welcome banner with your photo
- Typing animation, stats, tech stack, trophies
- A live animated contribution snake that auto-refreshes every 24 hours

## Notes
- All the `github-readme-stats`, `streak-stats`, `activity-graph` widgets pull live data automatically — no setup needed, just make sure your username is correct everywhere (`adityachaurasiya0112-code`) which it already is in the files provided.
- If any stats widget shows "Error" temporarily, it's usually just that free hosted API being asleep/rate-limited — refresh after a minute.
