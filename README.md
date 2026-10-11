# FRESHY — AI-Powered Grocery Inventory & Waste Prevention

A responsive, single-page concept website for FRESHY, an AI-powered grocery inventory co-pilot. The site explains the problem, end-to-end workflow, specialist AI agents, orchestration, human-in-the-loop approval, evaluation metrics, and includes an interactive synthetic inventory demo.

## What's included

- `index.html` — complete website (HTML, CSS, and JavaScript in one file)
- `assets/freshy-workflow.png` — project workflow infographic used in the page
- `.nojekyll` — helps GitHub Pages serve files without Jekyll processing

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a browser.
3. No build step, framework, package install, API key, or server is required.

## Deploy with GitHub Pages

1. Create a GitHub repository, for example `freshy-inventory-demo`.
2. Upload `index.html`, `README.md`, `.nojekyll`, and the `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site and open the URL shown in Settings → Pages.

## Important demo notes

- All inventory records, metrics, confidence scores, and suggested actions are fictional examples.
- The approve/modify/reject interactions change only the page's local demo state. They do not connect to point-of-sale, ERP, inventory, pricing, or logistics systems.
- The page does not claim measured waste reduction or validated forecasting performance.

## Production implementation roadmap

To turn the concept into a real application, add a backend API, authenticated user roles, a database, validated forecasting and shelf-life models, agent orchestration, audit logging, integrations with retailer systems, monitoring, and a secure human-approval workflow. Validate recommendations in simulation before any production execution.

## Suggested stack for a production version

- Front end: React / Next.js or the current HTML prototype
- API: Python FastAPI or Node.js
- Data: PostgreSQL plus a time-series or analytics store as needed
- Forecasting: benchmarked time-series models with confidence intervals
- Agent orchestration: explicit typed outputs, constraints, retries, and audit trails
- Deployment: GitHub Actions plus a hosting platform and managed database
