# EDAA — Risk & Information Security System (Interactive Demo)

Pre-sales demonstration prepared by **ABATS (Ali Bin Ali Technology Solutions)** for **EDAA — Qatar Central Securities Depository**, simulating a **Microsoft Power Platform** solution (Power Apps · SharePoint Online · Power Automate · Power BI · Microsoft Entra ID).

> ⚠️ **Demonstration only** — this is a self-contained front-end mockup, not the production system.

## ▶️ Live demo
Once GitHub Pages is enabled: **https://marouaboutalbi8-source.github.io/EDAARisk-InformationSecuritySystem/**

Or open `index.html` locally in any modern browser.

## What's inside
- **7 personas / role-based access** (Entra ID SSO simulation): Employee, PMO, Risk Representative, Risk Management, Department Head, CEO, IT Administrator
- **6 modules**: Emerging Risks (L01), Incidents (L02), Project Risk Assessments (L03), Operational Register (L04), Enterprise Register (L05), Reference Data (L06)
- **Live Likelihood × Impact scoring** with rating bands (Low / Medium / High / Critical)
- **4 Power BI–style dashboards**: Department Overview (row-level security), Enterprise Summary, Executive KPI (+ 5×5 heatmap, trend, top risks), Risk Aging
- **5 Power Automate flows** (FLW-01…05) firing live notifications
- **SharePoint list schema**, **Entra roles/permissions matrix**, **recommended solution architecture**
- **Bilingual EN / AR** with full RTL, responsive desktop + mobile
- Built-in **Presenter guide** walking the end-to-end demo scenario

## How to present it
1. Use the **persona switcher** (top-right) to sign in as each role — navigation and data scope change per Entra ID identity.
2. Toggle **EN / ع** to show full Arabic + RTL support.
3. Open the **Presenter guide** (bottom-left) and use *Jump to this step* to run the scenario.

## Tech
Single HTML file, vanilla JS + inline SVG charts. No build step, no dependencies.
