# Activity-Space Lab

[![Deploy Hugo site to Pages](https://github.com/ActivitySpaceLab/ActivitySpaceLab.github.io/actions/workflows/hugo.yml/badge.svg?branch=main)](https://github.com/ActivitySpaceLab/ActivitySpaceLab.github.io/actions/workflows/hugo.yml)
[![License](https://img.shields.io/github/license/ActivitySpaceLab/ActivitySpaceLab.github.io)](LICENSE)

Activity-Space Lab Website.

## About

The Activity-Space Lab is a small team of researchers looking at questions related to human mobility and the places where people spend time. Our interests range from neighborhood scale movement to global migration, with a focus on climate change, human-vector interactions, and health. The Activity-Space Lab is part of the [Sociodemography Research Group](https://www.upf.edu/web/demosoc) in the Department of Political and Social Sciences at Universitat Pompeu Fabra. The lab was created through the support of Grant CNS2022-135646, funded by MCIN/AEI/10.13039/501100011033 and by the European Union NextGenerationEU/PRTR. It is also funded by the AGAUR through the ICREA Acadèmia program.

## Site

- https://activityspacelab.com

## Local development

- Install the Hugo extended binary.
- Ensure the theme submodule is present:
  - `git submodule update --init --recursive`
- Run the dev server:
  - `hugo server`

## Deployment

Deployed automatically to GitHub Pages via GitHub Actions on pushes to `main`.

## License

- **Custom code**: GPLv3 (see [LICENSE](LICENSE)).
- **Content** (text, images, media): © Activity-Space Lab. All rights reserved unless otherwise indicated (see [CONTENT_LICENSE.md](CONTENT_LICENSE.md)).
- **Theme**: Apache-2.0 (see [themes/introduction/LICENSE](themes/introduction/LICENSE)).
