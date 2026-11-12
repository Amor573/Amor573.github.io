# Vercel launch checklist — Muhammed Akintola Portfolio

## What is in GitHub

- Repo: `Amor573/Amor573.github.io`
- Site folder: `portfolio-v2/`
- Default branch: `main`
- Site: `portfolio-v2/index.html` (single-page static site with shareable in-page case-study views)
- Configuration: `portfolio-v2/vercel.json`

Your existing root `index.html` is preserved, so importing the repository's root into Vercel would deploy the old website. **Set Root Directory to `portfolio-v2`.**

## Import steps

1. Connect Vercel to the GitHub account that owns `Amor573/Amor573.github.io`.
2. In Vercel, select **Add New → Project → Import** the repository.
3. Under Root Directory, select `portfolio-v2`.
4. Framework: **Other**. The site is static; no Node build or environment variables are needed.
5. Deploy and verify the generated `*.vercel.app` URL.
6. After deployment, check the desktop and mobile layout, portfolio category filters, 12 case studies, GitHub source links, LinkedIn CTA and browser console.
7. Link a custom domain only after the live preview is accepted.

The Vercel integration is an **account authorization step**, so GitHub commits alone cannot assert that the site is deployed.

## Current evidence and deployment status — 12 November 2026

Nine curated screenshots are published in `evidence/`, with exact crops, solid redactions, captions and explicit limits. Two IBM shared-session candidates remain local and are not published. No AWS/EKS execution, AKS apply, completed VPN migration or cargo/data screenshot was selected.

The Vercel connector is available but not installed/authorized in this session. No Vercel deployment status was returned for the portfolio commit. A new Vercel deployment and live verification have not been performed. Connect Vercel with access to this repository, then import it with Root Directory `portfolio-v2`.

## Security and operational rules

- No real customer data, firewall configurations, VPN secrets, access keys or private IPs in screenshots.
- Security-review the `tojuresto` repository before treating it as production ready. Its new `.gitignore` does not purge earlier tracked data or repository history.
- Label CI verification separately from production deployment.
- Keep the old GitHub Pages homepage unchanged until a verified Vercel preview is ready.