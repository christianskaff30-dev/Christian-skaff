# AURELLE — The Everyday Edit (Dashboard v2)

A React + Vite frontend prototype for AURELLE, organized around two main categories:
- Personal Studio
- Business Studio

## Run locally
Install Node.js LTS, open this folder in a terminal, then run:
```bash
npm install
npm run dev
```
Open the local Vite URL.

## Build
```bash
npm run build
```

## Deploy to Cloudflare Pages
Connect this GitHub repository to Cloudflare Pages. Set:
- Framework preset: Vite (or None if Vite is not listed)
- Build command: `npm run build`
- Build output directory: `dist`
- Root directory: `/`

## Included in this prototype
- Personal and Business category dashboards
- Health, study, finance, habits, goals, life organization
- Excel, accounting, audit assistance, financial analysis, research, reports and presentations
- AI Command Center interface with prompt suggestions
- Feature detail pages and request forms
- Basic task list saved in browser localStorage
- Responsive desktop and mobile design

## Important: prototype vs live AI
The interface and navigation are implemented, but AI functions are UI demonstrations only. The assistant does not yet analyze uploaded files, browse YouTube, perform web research, generate actual Excel/Word/PowerPoint files, or provide personalized health plans. Those require secure backend services and connected AI/search/file-processing APIs.

Before accepting real customer data, add authentication, secure file storage, database access controls, encryption, privacy and retention policies. Health and business/accounting outputs must be appropriately reviewed; this tool does not replace licensed medical, accounting, audit, legal or financial professionals. Never put secret API keys in frontend code.
