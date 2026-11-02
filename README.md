# Ramesh Mandamanedi — Engineering Portfolio

An original, responsive static portfolio for AI, backend and infrastructure engineering job applications.

## What's included

- Three interactive visual interfaces: **Studio** (dark product aesthetic), **Terminal** (monospace engineer view) and **Editorial** (warm light reading view)
- Project category filters, searchable project text, expandable engineering notes
- Skill groups, education, contact mail link, resume PDF
- Public GitHub links and two deployed search demonstrations
- Responsive, accessible controls, keyboard focus, reduced-motion preference
- No framework, server, API key, build pipeline or paid service required

## Run locally

Open `index.html` in a browser, or serve the directory for full browser features:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish using GitHub Pages (free)

Create a **new public repository** (for example `ramesh-portfolio`) and put these files in its root. In repository Settings → Pages, choose Deploy from a branch, `main` / root, and save. GitHub will show the resulting public URL when the site is ready. This is a separate website, not the special `Ramesh-codex/Ramesh-codex` GitHub profile README repository.

For a custom username domain (`https://Ramesh-codex.github.io/`), the repository must be named exactly `Ramesh-codex.github.io`; that name is optional.

## Maintain projects and skills

All project cards and skill categories are simple HTML in `index.html`. Update the visible text, GitHub links and demos there, then upload the changed file. `styles.css` contains the three design systems; `app.js` contains filtering and UI behavior. `resume.pdf` is the general-purpose updated resume; replace it when you revise your resume.

## Accuracy note

The 100,000-article search benchmark was conducted separately from the public curated-data demo. The hosted shard processes are co-located on one free instance. The developer-docs dataset is a snapshot. Benchmark numbers come from the user's submitted resume, not claims of production service-level guarantees.

This website's content is authored for Ramesh. Its design is independent of the inspiration site: https://shreevm.github.io/Portfolio/ .