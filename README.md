# Playwright Cloud Status Dashboard

## Project Summary
This project demonstrates a real-world Playwright UI automation suite built against a live, deployed cloud dashboard. It validates provider visibility, UI behavior, and dynamic updates across browsers using industry-standard automation practices.

## What Is Being Tested
- Dashboard loads successfully
- Cloud providers (AWS, Azure, GCP) are visible
- Status updates and timestamps change on user action
- Cross-browser behavior is consistent

## Why This Project Exists
This dashboard is intentionally **mocked** to create a safe, repeatable environment for QA automation, UI testing, and DevOps-style validation without relying on live cloud outages.

## Tech Stack
- **Playwright** (UI Automation)  
- GitHub Pages (Hosting)  
- JavaScript / TypeScript  

### Acronym + Origin
**QA = Quality Assurance**  
Origin: Emerged in 1940s manufacturing and defense programs to prevent defects before production; later adopted by software engineering.

**DevOps = Development + Operations**  
Origin: Coined in 2009 to break down silos between software development and infrastructure teams.

## Automation Coverage
- Cross-browser testing (Chromium, Firefox, WebKit)
- BaseURL configuration
- Traces, screenshots, and reporting
- Deterministic UI assertions

## How to Run
```bash
npm install
npx playwright test
npx playwright show-report
