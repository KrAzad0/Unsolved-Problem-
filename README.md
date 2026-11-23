# Open Problems — Research Notebook

A lightweight research index by Kumar Azad, built from scratch as a **static GitHub Pages website**.

## Website

**https://krazad0.github.io/Unsolved-Problem-/**

## What is inside

- `index.html` — complete standalone site (HTML, CSS, JavaScript). The eight research entries are written directly into the HTML so they remain visible without JavaScript.
- `.nojekyll` — tells GitHub Pages to serve the static files directly.
- `README.md` — documentation and setup instructions.

There is **no Node.js, React, Python backend, dependency installation, build command, or custom deployment workflow**. This avoids the earlier Actions failure.

## Publish with GitHub Pages (one-time repository setting)

1. Open **Settings → Pages**: https://github.com/KrAzad0/Unsolved-Problem-/settings/pages
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose **Branch: main** and **Folder: /(root)**, then select **Save**.
4. Open the website URL above after GitHub reports the site is published.

**Important:** Committing code alone cannot enable Pages if repository Pages is disabled. Only someone with repository Settings access can make that one-time selection. All subsequent pushes to `main` are automatically published by GitHub Pages.

## Research scope

The notebook contains eight early-stage entries about:
- Quantum biology and isotope effects
- Hydrogen in toroidal confinement and stationary states
- Moving-boundary quantum dynamics and quantum-to-classical crossover
- Ultrafast driving and spectroscopy

Every entry distinguishes a question, a starting model and a next verification step. The entries are exploratory and must not be represented as peer-reviewed discoveries.

## Updating the site

Edit `index.html` directly. Each research item is an HTML `<article class="problem">` element with a `data-topic` attribute. The small inline search/filter script discovers these cards automatically.

## License and credit

Author: Kumar Azad. Repository: https://github.com/KrAzad0/Unsolved-Problem-
