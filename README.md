# 🎭 Playwright Cloud Status Dashboard (Documentation)

## Project Summary
This repository is a **documentation + portfolio landing page** for a Playwright UI automation suite that tests a live, deployed Cloud Status Dashboard (SUT).

If you want to run the tests, use the automation repo linked below.

---

## 🔗 Links

- **Automation Repo (Run the tests here):** https://github.com/vivaciousdove/testsplaywright  
- **Live Dashboard (SUT):** https://vivaciousdove.github.io/cloud-status-dashboard/

---

## ✅ What Is Being Tested (High-Level Coverage)

- Dashboard loads successfully
- Cloud providers (AWS, Azure, GCP) are visible
- Status updates and timestamps change on user action
- Cross-browser behavior is consistent

---

## 🎯 Why This Project Exists
This dashboard is intentionally mocked to create a safe, repeatable environment for **QA automation**, **UI testing**, and **DevOps-style validation** without relying on real cloud outages or provider APIs.

It enables deterministic testing while still behaving like a production UI.

---

## 🧰 Tech Stack
- **Playwright** — UI automation
- **GitHub Actions** — CI execution (in the automation repo)
- **GitHub Pages** — hosting for the live SUT dashboard
- **TypeScript / JavaScript** — test and UI logic

---

## 🧠 Acronym + Origin

**QA = Quality Assurance**  
Origin: Emerged in 1940s manufacturing/defense quality programs; later adopted in software to prevent defects early.

**DevOps = Development + Operations**  
Origin: Popularized in 2009 to reduce silos between software delivery and infrastructure operations.

**SUT = System Under Test**  
Origin: Common testing term describing the application being validated by tests.

---

## ▶️ How to Run (Automation Repo)

Run the suite from the automation repo:

```bash
git clone https://github.com/vivaciousdove/testsplaywright.git
cd testsplaywright
npm ci
npx playwright install --with-deps
npx playwright test
npx playwright show-report
```
---
🧾 Evidence

Primary proof artifacts (from the automation repo CI runs):

Playwright HTML report (playwright-report)

Traces / screenshots / videos (when enabled)

Tip: Download the playwright-report artifact from GitHub Actions and open index.html locally.

---


