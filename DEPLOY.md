# Deploying this page (GitHub Pages, ~5 minutes)

`gh` CLI is not installed on this machine, so the repo has to be created in the browser once.
After that everything is `git push`.

## 1. Create the repo (browser, once)
github.com/new → repository name **exactly** `financebroski.github.io`
(must match the username `Finance-broski` — GitHub is case-insensitive here).
Public. Do NOT add a README, .gitignore or licence.

## 2. Push (from this folder)
    git init
    git add -A
    git commit -m "Backtest Audit service page"
    git branch -M main
    git remote add origin https://github.com/Finance-broski/financebroski.github.io.git
    git push -u origin main

## 3. Turn Pages on
Repo → Settings → Pages → Source: "Deploy from a branch" → Branch `main`, folder `/ (root)` → Save.
Live at **https://financebroski.github.io** within ~1-2 minutes.

## 4. Point everything at it
- Reddit / LinkedIn post CTAs
- LinkedIn Services section (append the URL)
- Saved DM reply
- Intake form intro text

## Updating later
Edit `index.html`, then `git add -A && git commit -m "..." && git push`. Live in ~60s.
