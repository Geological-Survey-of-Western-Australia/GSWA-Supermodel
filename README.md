# GSWA Supermodel

This repository contains the source code for the GSWA Supermodel which is an enterprise data model of data held by the [Geological Survey of Western Australia](https://www.wa.gov.au/organisation/department-of-mines-petroleum-and-exploration/geological-survey-of-western-australia) within the [Department of Mines, Petroleum and Exploration](https://www.wa.gov.au/organisation/department-of-mines-petroleum-and-exploration).

Please see the model documentation online at:

* <https://geological-survey-of-western-australia.github.io/GSWA-Supermodel/>

## License & Rights

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

This repository uses the [MkDocs](https://www.mkdocs.org/) tool to build a static website - just HTML pages, no database etc. - from simple [Markdown](https://www.markdownguide.org/) text files and images stored in the `docs/` folder which is published online via GitHub's Pages system.

MkDocs uses [Python](https://www.python.org/) scripting to compile the Markdown files, images etc. into HTML. It can be run locally - on a desktop/laptop - to test documentation changes, and pushed to GitHub to be auto-deployed.

To serve this content as a static site locally, run:

`mkdocs serve`

### Data

The model data in this repository is contained within the `rdf/` folder and is packaged using the [Prez Manifest](https://prez.dev/manifest) system for automated deployment to Knowledge Graph systems.

