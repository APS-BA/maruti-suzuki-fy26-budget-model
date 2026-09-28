# Driver-Based FY2026 Budget · Maruti Suzuki India

**Caplexus Capital FP&A Analyst live project (Jul–Aug 2026) · FP&A certification**

A fully linked, driver-based FY2026 budget for India's largest passenger-vehicle
maker: P&L, balance sheet and cash flow, built as an FP&A analyst would have built
it at the start of the year, using only information available as of Q1 FY2026.

![Excel](https://img.shields.io/badge/Excel-driver--based%20model-217346)
![FP&A](https://img.shields.io/badge/FP%26A-budgeting%20%7C%20sensitivity-555)

---

## Headline budget (consolidated)

| Line | FY2026 budget | vs FY2025 |
|---|---:|---|
| Revenue from operations | ₹1,69,389 Cr | +10.8% (≈5.5% volume × ≈5.0% realisation/mix) |
| EBITDA | ₹22,021 Cr | 13.0% margin (13.2% in FY2025) |
| Profit after tax | ₹15,194 Cr | 9.0% margin (9.5% in FY2025) |
| Operating cash flow | ₹24,789 Cr | funds ₹5,570 Cr capex, investments and dividends |

## The number that matters most

A cost-of-materials overrun of just **+0.8%** relative to budget (COGS moving from
71.3% to ~71.9% of revenue) erases the entire year's budgeted PAT growth. The
year's profit growth rests on a margin of safety of well under one percentage
point on the largest cost line.

## How the model is built

```
Historical financials (FY2022–25) → metrics & drivers → macro assumptions
  → line-item assumptions → revenue budget (volume × realisation) → cost budget
  → budgeted P&L → budgeted balance sheet → budgeted cash flow → sensitivity
```

- Every budget line flows from a named driver on the assumptions sheet
- The balance sheet balances by construction; cash flow is derived, not plugged
- Operating expenses split into materials, employee and other costs using the company's own historical cost structure (method documented in the workbook)
- Ratio analysis, revenue and EBITDA bridges, and illustrative quarterly phasing

## Sensitivity

| Scenario | PAT (₹ Cr) |
|---|---:|
| Bear: volume −5 pp, raw material +10%, employee cost +8% together | 5,463 |
| **Base budget** | **15,194** |
| Bull: mirror-image upside | 25,776 |

Each of the three risks is also shown on its own; raw-material cost is the largest
single swing factor.

## Repository contents

```
FY26_Budget_Model.xlsx   14-sheet linked model: historicals, drivers, assumptions,
                         revenue and cost budgets, P&L, balance sheet, cash flow,
                         sensitivity, ratios, quarterly phasing, charts
FY26_FPA_Report.pdf      Full 34-page report: business overview, historical analysis,
                         assumptions, budget build, sensitivity and recommendation
FY26_FPA_Report.docx     Editable report
```

All inputs come from the company's published consolidated results and public
macro and industry sources.
