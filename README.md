# Mike Akey — Personal Portfolio Site

A GitHub Pages site hosting my professional documents, built with plain HTML and deployed automatically via GitHub Actions.

## Live Site

| Page | URL |
|------|-----|
| Resume | https://makey06.github.io/Resume/ |
| Cover Letter | https://makey06.github.io/Resume/cover-letter/ |

## Structure

```
/
├── index.html              # Resume
├── cover-letter/
│   └── index.html          # Cover letter
└── .github/
    └── workflows/
        ├── deploy.yml          # Auto-deploys to GitHub Pages on push to main
        └── update-repos.yml    # Auto-updates Other Projects section daily
```

## Deployment

Any push to `main` automatically triggers a GitHub Actions workflow that deploys the latest version to GitHub Pages. No build step required — the site is plain HTML/CSS.

## About

Senior Product Manager with 10+ years at Alteryx, spanning Customer Support, UX, and Product. Based in Scottsdale, AZ.

## Other Projects

<!-- REPOS_START -->
| Repo | Description |
|------|-------------|
| [SummerScholar](https://github.com/makey06/SummerScholar) | (no description) |
| [Fun-WIP](https://github.com/makey06/Fun-WIP) | Fun side projects and idea dumping ground |
<!-- REPOS_END -->

*This section is automatically updated daily by GitHub Actions.*
