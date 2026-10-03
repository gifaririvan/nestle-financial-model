# Nestlé S.A. — Financial Model & Valuation (FY2023A–2030F)

Independent portfolio project by **Mohammad Rivan Gifari, CMA** — an integrated 3-statement model, DCF and comparable company valuation of Nestlé S.A., with a Power BI dashboard for financial statement analysis across Best / Base / Worst scenarios.

## Valuation Summary (Base Case)

| Method | Value per share (CHF) | vs. current price (CHF 74.63) |
|---|---:|---:|
| DCF – perpetuity growth (WACC 5.1%, g 1.5%) | 97.4 | +30.5% |
| DCF – exit multiple (13.5x) | 82.4 | +10.4% |
| Trading comps – EV/EBITDA 2026F (mid) | 76.1 | +2.0% |
| **Blended fair value (50% DCF / 50% comps)** | **84.2** | **+12.9% → fairly valued** |

*Share price and peer data as of early October 2026.*

## Financial Analysis Highlights (Base Case 2026F)

- **Stabilisation, not yet recovery:** revenue of CHF 90.3bn (+0.5%) ends two years of decline, while EBITDA margin eases to 17.5%.
- **Cash resets lower:** FCF falls 18.4% to CHF 9.0bn as associate dividends normalise; the dividend absorbs 89% of FCF.
- **Gradual deleveraging:** net debt/EBITDA moves from 3.32x to 2.82x by 2030F, unlocking buybacks late in the plan.
- **Structural working-capital strength:** a negative cash conversion cycle (−14.2 days) means suppliers fund the operating cycle.
- **Severe downside:** in the Worst Case (2028F), revenue 10.2% below Base cuts net profit by 52%, so a downside playbook is needed in advance.

📑 **Full page-by-page insights:** [README_Insights.md](dashboard/README_Insights.md)

## Repository Contents

| File | Description | View online |
|---|---|---|
| [3-Statement Model](models/%282023-2030%29_3Statement_Model_Nestle.xlsx) | Integrated income statement, balance sheet and cash flow, FY2023A–2030F, three scenarios | [Open in Excel](https://1drv.ms/x/c/038256bdca3178ad/IQBOhNh-KomGRZiSNpl3_zkPAUxkFBE9cEhjFVJqBeGO0SM?e=8Iy8CU) |
| [DCF Model](models/%282023-2030%29_DCF_Model_Nestle.xlsx) | Unlevered FCF, WACC build-up, perpetuity growth and exit multiple methods, sensitivity tables | [Open in Excel](https://1drv.ms/x/c/038256bdca3178ad/IQAUfyvjEfzzRZ58XRwqAvfNASMn-xX506PdcSzR527r1Fk?e=ew5Xet) |
| [Comparable Valuation](models/%282023-2030%29_Comparable_Valuation_Nestle.xlsx) | Trading comps (8 peers), precedent transactions, valuation summary | [Open in Excel](https://1drv.ms/x/c/038256bdca3178ad/IQCCc_J4QRl9RoNcClvpKfhPAX91R7Jw_M-wVJrr1HBaC0U?e=tMdSwN) |
| [Power BI Dashboard (PDF)](dashboard/Executive%20Financial%20Analysis%20Dashboard.pdf) | 11-page financial analysis: statements, ratios, DuPont, working capital, scenarios | Opens in GitHub |

## Model Design

- One scenario switch (Best / Base / Worst) drives the forecast across the models
- Clear Input → Model → Output structure
- Rationale for each key assumption documented next to the driver

## Tools

Microsoft Excel · Power BI Desktop

## How to View

- **Excel models:** click **Open in Excel** to view in your browser (no sign-in or download needed), or click the file name to download it from this repository.
- **PDF dashboard:** opens directly in GitHub.

## Disclaimer

Independent portfolio project prepared in a personal capacity to demonstrate financial modeling and analysis skills. Historical figures come from Nestlé's public reports; forecasts and scenarios are the author's own illustrative assumptions. Not affiliated with or endorsed by Nestlé S.A., and not investment advice.
