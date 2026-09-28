# mazed-siddiki.github.io

Source for my personal site, live at **https://mazed-siddiki.github.io**

A single static page covering my background, research, projects, skills and languages. No framework and no build step: one `index.html` with the stylesheet inline, plus assets.

## Deployment

GitHub Pages, built from the `main` branch by GitHub Actions. `.github/workflows/static.yml` uploads the repository as a Pages artifact and deploys it, so any push to `main` publishes the site.

## Editing it

Edit `index.html` and push. The page is organised as one `<section>` per part of the site (`about`, `education`, `experience`, `projects`, `awards`, `languages`), each with the same card and timeline classes, so a new entry means copying an existing block and changing the text inside it.
