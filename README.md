# GSWA Supermodel

This repository contains the source code for the GSWA Supermodel which is an enterprise data model of data held by the [Geological Survey of Western Australia](https://www.wa.gov.au/organisation/department-of-mines-petroleum-and-exploration/geological-survey-of-western-australia) within the [Department of Mines, Petroleum and Exploration](https://www.wa.gov.au/organisation/department-of-mines-petroleum-and-exploration).

Please see the model documentation online at:

* <https://geological-survey-of-western-australia.github.io/GSWA-Supermodel/>

## Licence & Rights

This repository's content is available for reuse according to the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

This content is copyright as follows:

&copy; Government of Western Australia, 2025

## Contacts

For use and governance matters, please contact:

**Geological Survey of Western Australia**  
<https://dmp.wa.gov.au/Geological-Survey/Geological-Survey-262.aspx>

For technical matters, please contact:

**Nicholas Car**  
_[KurrawongAI](https://kurrawong.ai)_  
_Contractor to GSWA_  
<nick@kurrawong.ai>

## Technical Operations

### Documentation 

This repository uses [Zensical](https://zensical.org/) to build a static website from
[Markdown](https://www.markdownguide.org/) files and images in `docs/`. GitHub Pages hosts the generated site.

Install [uv](https://docs.astral.sh/uv/getting-started/installation/) to manage Python and project dependencies.
Run these commands from the repository root; uv installs the Python version recorded in `.python-version` when needed:

```sh
uv sync --locked
uv run zensical serve
```

To build the site locally, run `uv run --locked zensical build --clean`. Configuration is in `zensical.toml`, and
generated files are written to `site/`.

Push changes to `main` to build and deploy automatically through `.github/workflows/deploy.yml`, or run the workflow
manually from GitHub Actions. CI installs dependencies from `uv.lock` using `uv sync --locked`.

### Data

The model data in this repository is contained within the `rdf/` folder and is packaged using the [Prez Manifest](https://prez.dev/manifest) system for automated deployment to Knowledge Graph systems.

