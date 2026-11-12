---
title: GitHub Partner Offers
description: Sample landing page deployed with Azure Static Web Apps and GitHub Actions.
---

## Sample site

[index.html](./src/index.html) is a responsive, self-contained landing page using
HTML and CSS. Open it in your browser to preview it locally; no dependencies
or build tools are required.

## Deployment

The [GitHub Actions workflow](./.github/workflows/azure-static-web-apps-icy-meadow-0b7a2260f.yml)
publishes the `src` folder to Azure Static Web Apps without an application
build step. A push or merge to `main` triggers deployment. Opened, updated,
and reopened pull requests targeting `main` trigger preview deployments.

The workflow requires the Azure deployment secret already referenced in its
configuration. Check the repository's Actions tab after merging to confirm
deployment succeeded.