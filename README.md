# Unsolved Problems — Research in Progress

This is **Kumar Azad's active research notebook**: a public record of difficult problems and research questions I am working on across theoretical and mathematical physics, quantum mechanics, ultrafast science and quantum biology. The site presents my working questions, possible mathematical models and planned investigations rather than claiming completed solutions.

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

I am currently investigating eight research directions at different stages of formulation, modelling or numerical exploration:
- Quantum biology and isotope effects
- Hydrogen in toroidal confinement and stationary states
- Moving-boundary quantum dynamics and quantum-to-classical crossover
- Ultrafast driving and spectroscopy

Each entry records the scientific question I am investigating, a model under consideration, and the next step in my work. These topics are ongoing investigations, **not claims of solved problems, original discoveries or peer-reviewed results**. Some research questions may already have partial answers or prior solutions in the literature; verifying that history is part of the work.

## Updating the site

Edit `index.html` directly. Each research item is an HTML `<article class="problem">` with a `data-topic` attribute. Update its question, current model, next steps and investigation stage as the work develops. The search/filter script discovers these cards automatically.

## License and credit

Author: Kumar Azad. Repository: https://github.com/KrAzad0/Unsolved-Problem-
