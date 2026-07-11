# GitHub Profile README — Setup Guide

## Quick Deploy Checklist

Follow these steps after cloning/downloading this repository to make everything work immediately on GitHub.

---

### Step 1 — Update Your Personal Details

Open `README.md` and replace the placeholder values:

| Placeholder | Replace With |
|---|---|
| `ayantika2006@example.com` | Your real email address |
| `ayantika-jana` (LinkedIn URL) | Your actual LinkedIn username |
| `ayantika2006` (HackerRank URL) | Your actual HackerRank username |
| `ayantika2006` (LeetCode URL) | Your actual LeetCode username |
| Each project `href` link | Your actual repository URLs |

---

### Step 2 — Enable GitHub Actions Permissions

For the contribution snake to work:

1. Go to your `Ayantika2006` repository on GitHub
2. Navigate to **Settings → Actions → General**
3. Under **Workflow permissions**, select **Read and write permissions**
4. Check **Allow GitHub Actions to create and approve pull requests**
5. Click **Save**

---

### Step 3 — Run the Snake Workflow

1. Go to the **Actions** tab in your repository
2. Select **"Generate Contribution Snake"**
3. Click **"Run workflow"** → **"Run workflow"**
4. Wait ~2 minutes for it to complete
5. A new branch called `output` will be created with your snake SVGs

After this, the snake animation in your README will display automatically.

---

### Step 4 — Push Everything

```bash
git add .
git commit -m "feat: premium cybersecurity profile README"
git push origin main
```

---

### Step 5 — Verify Your Profile

Visit: `https://github.com/Ayantika2006`

All widgets should load within a few minutes. If any widget shows an error, see the Troubleshooting section below.

---

## File Structure

```
Ayantika2006/
├── README.md                          # Your profile README (main file)
├── assets/
│   └── banner.svg                     # Custom cyber-themed hero banner
├── .github/
│   └── workflows/
│       ├── snake.yml                  # Generates contribution snake daily
│       └── update-stats.yml           # Keeps stats widgets refreshed
├── .gitignore
└── SETUP.md                           # This file
```

---

## Widgets Used

| Widget | Service | Theme Applied |
|---|---|---|
| Typing Animation | readme-typing-svg.demolab.com | Purple `#9D4EDD` |
| GitHub Stats | github-readme-stats.vercel.app | Dark transparent |
| GitHub Streak | github-readme-streak-stats.herokuapp.com | Purple ring/fire |
| Top Languages | github-readme-stats.vercel.app | Dark transparent |
| Activity Graph | github-readme-activity-graph.vercel.app | Dark purple |
| Contribution Snake | Platane/snk GitHub Action | Purple palette |
| GitHub Trophies | github-profile-trophy.vercel.app | Discord dark theme |
| Profile Views | komarev.com/ghpvc | Purple badge |
| Tech Icons | skillicons.dev | Dark theme |
| Social Badges | shields.io | Dark `#0A0015` |

---

## Troubleshooting

**Snake animation not showing?**
→ Run the workflow manually (Step 3). The `output` branch must exist first.

**Stats showing "Not Found"?**
→ Make sure your GitHub username in the URLs is exactly `Ayantika2006` (case-sensitive).

**Streak widget broken?**
→ Try the alternative URL: `https://streak-stats.demolab.com/?user=Ayantika2006` with the same parameters.

**Activity graph not loading?**
→ The graph requires at least some public repository activity to display.

**Banner not showing?**
→ Ensure `assets/banner.svg` is committed and pushed to your repository root.

---

*Built with the Cyber Purple aesthetic. Secured by design.*
