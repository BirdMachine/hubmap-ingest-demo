# HuBMAP Ingest UI — interactive portfolio demonstration

Public portfolio demo of workflows from the NIH-funded HuBMAP Data Ingest Portal.

**Live URL (after GitHub Pages is enabled):** https://birdmachine.github.io/hubmap-ingest-demo/

## What it demonstrates

- Search/filter fictional scientific entities; inspect selected records; export CSV.
- Preview local CSV or TSV metadata in the browser.
- Create simulated upload records without authenticating or calling any production API.

All records are fictional; this standalone demo does not connect to HuBMAP services. It is a simplified demonstration, **not** a deployment of the original React code.

## Historical source

Based on examination of the public HuBMAP ingest-ui source as of July 30, 2026, commit [c7a5bad](https://github.com/hubmapconsortium/ingest-ui/tree/c7a5bad29efdcc52caf68c37765c70a49e9113dc). Relevant original components include Search.jsx, bulkMetaTable.jsx, and Uploads.jsx.

This portfolio project is independent and is not an official HuBMAP site. Consult the upstream repository for its licensing and notices.

## Deploy

In repository **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source. Then open **Actions → Deploy GitHub Pages → Run workflow** if needed.

The live URL is only valid after a successful deployment.
