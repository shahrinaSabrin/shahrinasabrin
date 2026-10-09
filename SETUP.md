# Install your GitHub profile README

This folder contains a profile README, a custom hero SVG, and a GitHub Actions workflow for the contribution-snake animation.

## 1. Use your profile repository

Your profile repository must be named exactly:

`shahrinaSabrin`

If it does not exist yet, create a **public** repository with that exact name.

## 2. Copy these files into the repository

Copy:
- `README.md` to the repository root
- `assets/profile-hero.svg` to `assets/profile-hero.svg`
- `.github/workflows/snake.yml` to `.github/workflows/snake.yml`

Commit and push the changes.

## 3. Enable write permissions for Actions

In the repository, open **Settings → Actions → General → Workflow permissions** and select **Read and write permissions**. Save.

## 4. Run the animation workflow

Open **Actions → Generate contribution snake → Run workflow**.

After the workflow succeeds, it publishes the generated SVGs to the `output` branch. The README uses those files. The scheduled run refreshes them daily.

## 5. Personalize the portfolio link

The current README links to `https://portfolio-2-two-ashy.vercel.app/`. Replace it if your portfolio URL changes.

## Important limitation

GitHub Markdown does not support making every blank area and all text in a README act like one full-page link. This version makes the large hero/banner clickable and links the portfolio clearly. The rest of the README remains readable and interactive through its individual links.

The contribution snake is generated from GitHub's contribution calendar; it is not a fabricated contribution count. Public contribution visibility follows your GitHub settings.
