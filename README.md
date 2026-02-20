# PowerTechs — The 10-Year Workforce Outlook

[![Deploy static content to Pages](https://github.com/amlfarhad/powertechs-outlook-site/actions/workflows/static.yml/badge.svg)](https://github.com/amlfarhad/powertechs-outlook-site/actions/workflows/static.yml)

A proactive, data-driven gap analysis of the impending shift in the industrial workforce. This site maps 89 validated emerging tasks against the current certification landscape to highlight the massive skills gap approaching by 2035.

**View the Live Site:**
- 🌍 **[The 2035 Outlook (Landing Page)](https://amlfarhad.github.io/powertechs-outlook-site/)**
- 📊 **[Full Database Analysis & 255 Transition Pathways](https://amlfarhad.github.io/powertechs-outlook-site/analysis.html)**

---

## 🚀 The Pivot: Exposing the Gap

Rather than proposing hypothetical credentials, this platform uses validated O*NET-style task data to explicitly highlight *why* the current certification system is failing against upcoming technology trends.

### Key Features
1. **The 89-Task Database:** A massive, detailed table of emerging tasks across Construction, Energy, and Transportation, broken down by specific Subsectors (e.g., Heavy Civil, Modular Prefab, Utilities) and Time Horizons (Near, Mid, Long).
2. **The Certification Gap:** Visual proof that major technological shifts (like Digital Twins, Advanced Composites, and Hydrogen Fuel Cells) require specific skill shifts that are completely unaddressed by existing credentials.
3. **255 Dynamic Transition Pathways:** An interactive, filterable database modeling exactly what it takes to pivot the current workforce into the future. We map 5 core worker "Archetypes" (e.g., Coal Miners, Military Logistics, Refinery Operators) against every single potential target occupation.
4. **Learn vs. Unlearn:** Each transition pathway details exactly which existing certifications the worker holds, which ones they need to buy (with cost/time estimates), and specifically what behaviors they must **Learn** vs. **Unlearn** to succeed.

---

## 🛠 Repository Structure

This is a standalone, static HTML/CSS deployment repository extracted from the core Python/JSON data engine. The dynamic HTML was generated natively from the validated database.

- `/index.html` - The main stakeholder landing page (The 2035 Outlook).
- `/analysis.html` - The deep-dive page containing the interactive task tables and the 255 collapsible transition pathways.
- `/.github/workflows/static.yml` - The GitHub Actions workflow that automatically builds and deploys the site to GitHub Pages on every push to the `main` branch.

---

## 🌐 Automated Deployment

This site is automatically hosted for free via GitHub Pages.

Any commits pushed directly to the `main` branch will automatically trigger the `Deploy static content to Pages` GitHub Action. The live site usually updates within 1-2 minutes of a successful push. No manual build steps are required.
