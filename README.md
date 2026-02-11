# Zhonghao Chen — Academic Website

This repository contains my personal academic website/CV, built with Hugo and HugoBlox.

## Develop locally

Prerequisites:

- Hugo **extended** v0.136.5 (matches `netlify.toml` and `.github/workflows/publish.yaml`)
- Node.js (used to generate the Pagefind search index)

Commands:

- Run a local server: `hugo server`
- Build the site: `hugo --gc --minify`
- Generate search index: `npx pagefind --site public`

## Deploy to GitHub Pages

This repo includes a GitHub Actions workflow at `/.github/workflows/publish.yaml` that builds and deploys on every push to the `main` branch.

1. Push this repository to GitHub.
2. In GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. After the Actions workflow completes, your site will be available at:
   - `https://<GitHubUsername>.github.io/` (if the repo name is `<GitHubUsername>.github.io`)
   - `https://<GitHubUsername>.github.io/<RepoName>/` (otherwise)

## Where to edit content

- Profile / CV data: `content/authors/admin/_index.md`
- Homepage sections: `content/_index.md`
- Publications: `content/publication/`
- Projects: `content/project/`
- CV PDF download: `static/uploads/resume.pdf`
- Site settings: `config/_default/`

