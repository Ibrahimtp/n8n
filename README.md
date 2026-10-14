# n8n on Render

Infrastructure-as-code for self-hosting the [n8n](https://n8n.io/) workflow automation platform on Render, with a managed Postgres database.

## What it deploys (`render.yaml`)
- A web service that runs the official n8n Docker image
- A Render Postgres database for n8n data
- Free instance types by default

## Deploy
Create a new Blueprint in Render pointing at this repo; Render reads `render.yaml` and provisions both services. Full guide: https://render.com/docs/deploy-n8n

_Based on Render's official n8n template._
