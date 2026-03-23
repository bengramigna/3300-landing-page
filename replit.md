# 3300 Landing Page

## Project Overview
A minimal static HTML website ("Hello World" landing page), originally configured for Azure Static Web Apps deployment.

## Tech Stack
- **Frontend:** Plain HTML5 (no build system, no framework)
- **Server (dev):** Python `http.server` on port 5000

## Project Structure
- `index.html` — Main (and only) page
- `README.md` — Project name
- `.github/workflows/` — Azure Static Web Apps CI/CD pipeline (original)

## Running Locally
The workflow "Start application" serves the site with:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a **static** deployment with `publicDir: "."`.
