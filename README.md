# RTV QC Analytics Dashboard

This repo contains a GitHub Pages-ready RTV QC dashboard.

The dashboard fetches the published Google Sheet CSV, auto-refreshes every 5 minutes, and renders the approved 3-tab structure:

## Screens

- Overview
- Channel Analysis
- SKU Deep-Dive

## Data Source

Published CSV:

`https://docs.google.com/spreadsheets/d/e/2PACX-1vSismHdOKJigedmrPENc8HXyW4TvqHek7e1ASCluZfi1s3jgQPZGhYJQjb_F5IoarAnOmybH7aIqrWG/pub?gid=1227720756&single=true&output=csv`

## Publishing

Enable GitHub Pages from the repository settings:

1. Go to `Settings` > `Pages`.
2. Select `Deploy from a branch`.
3. Choose `main` and `/root`.
4. Save.

The site will publish as:

`https://<github-username>.github.io/<repo-name>/`
