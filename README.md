# pharmaverse-onboarding

A Quarto website for onboarding clinical SAS programmers into R and the pharmaverse open-source ecosystem.

**Live site:** [*Pharmaverse Onboarding*](https://jeffreyad.github.io/pharmaverse-onboarding/)

## Contents

| Page | Description |
|---|---|
| `index.qmd` | Home page and overview |
| `steps.qmd` | Step-by-step getting started guide |
| `hackathon.qmd` | 2026 Pharmaverse Hackathon calendar and preparation |
| `resources.qmd` | Curated additional resources |

## Local Development

Prerequisites: [Quarto](https://quarto.org/docs/get-started/) installed.

```bash
# Clone the repo
git clone https://github.com/YOUR_ORG/pharmaverse-onboarding.git
cd pharmaverse-onboarding

# Preview locally
quarto preview

# Build to /docs
quarto render
```

## GitHub Pages Deployment

This site is configured to render output to `/docs`, which works directly with GitHub Pages.

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set Source to **Deploy from a branch**, Branch to `main`, Folder to `/docs`
4. The site will be live at `https://YOUR_ORG.github.io/pharmaverse-onboarding/`

## Maintenance

Update `hackathon.qmd` as sign-up links become available for each 2026 event. Update `resources.qmd` as the pharmaverse ecosystem evolves.

## License

Content licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
