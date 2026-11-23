# Tata Motors – 3-Statement Financial Model & DCF Valuation

## Project overview

This project builds a historical financial analysis, an integrated three-statement forecast, and a Discounted Cash Flow (DCF) valuation for the **Tata Motors consolidated group on a pre-demerger basis**.

The model uses FY2021–FY2025 historical financial information and projects FY2026E–FY2030E. The valuation date is **31 March 2025**. All financial figures are in **INR crore**, unless stated otherwise.

> **Scope note:** This is a historical, pre-demerger group valuation using FY2025 balances. It is not a valuation of either post-demerger listed company and should not be interpreted as a current share-price target.

## Workbook

The Excel workbook is the main deliverable:

- `Tata_Motors_3_Statement_DCF_Model.xlsx`

It contains 11 worksheets:

| Worksheet | Purpose |
|---|---|
| Historical Data | Summary of historical financial data |
| Assumptions | Forecast drivers and valuation inputs |
| Income Statement | Historical and projected income statement |
| Balance Sheet | Historical and projected balance sheet |
| Cash Flow | Historical cash flow and forecast cash movements |
| DCF Valuation | FCFF forecast, discounting and valuation bridge |
| Checks | Historical tie-outs and forecast balance checks |
| Sensitivity | WACC / terminal-growth sensitivity tables |
| Comparability | Historical ratios and comparability notes |
| Statement Detail | Annual-report statement inputs and source notes |
| Notes | Scope, definitions and modelling caveats |

## Methodology

### 1. Historical financial analysis
- Compiles FY2021–FY2025 consolidated financial information.
- Uses annual-report statement inputs documented in the `Statement Detail` worksheet.
- Calculates operating metrics such as revenue growth, EBITDA margin, EBIT margin, capital expenditure and working capital ratios.
- Highlights changes in reporting and consolidation that affect year-on-year comparability.

### 2. Three-statement modelling
- Forecasts revenue, EBITDA, depreciation and amortisation, EBIT, tax and net income.
- Projects key balance-sheet items using operating assumptions.
- Links net income, depreciation, working capital movements, capital expenditure, debt repayment and dividends into the cash-flow forecast.
- Includes balance-sheet and cash-flow consistency checks.

### 3. DCF valuation
The valuation uses the **Free Cash Flow to Firm (FCFF)** approach:

`FCFF = EBIT × (1 − tax rate) + D&A − Capital Expenditure − Change in Net Working Capital`

Projected FCFF is discounted using WACC. A terminal value is calculated using the Gordon Growth method:

`Terminal Value = Final Forecast Year FCFF × (1 + terminal growth rate) / (WACC − terminal growth rate)`

Enterprise value is then bridged to equity value using the workbook's FY2025 debt, cash, other liquid investments and non-controlling interests inputs. The per-share calculation uses the FY2025 weighted diluted share count.

### 4. Sensitivity analysis
The workbook includes sensitivity tables showing the effect of changes in WACC and terminal growth on:
- Implied value per share
- Enterprise value

## Base-case valuation outputs

The following figures are the outputs displayed in the submitted workbook:

| Metric | Model output |
|---|---:|
| Valuation date | 31 March 2025 |
| WACC | 13.7231% |
| Terminal growth rate | 4.00% |
| Present value of forecast FCFF | ₹52,415.08 crore |
| Terminal value | ₹240,478.36 crore |
| Present value of terminal value | ₹126,424.88 crore |
| Enterprise value | ₹178,839.96 crore |
| Equity value | ₹166,258.96 crore |
| Implied value per share | ₹470.46 |
| Terminal value / enterprise value | 70.69% |

These are model outputs, not independently verified fair values or investment recommendations.

## Key forecast assumptions

The submitted base case includes:
- Revenue growth tapering from 5.0% in FY2026E–FY2028E to 4.5% in FY2029E and 4.0% in FY2030E.
- EBITDA margin held at 12.0%.
- D&A held at 5.5% of revenue.
- Capital expenditure declining gradually from 8.5% to 6.5% of revenue.
- A 27.0% forecast tax rate.
- Trade receivables, inventory and trade payables forecast using revenue-based assumptions.
- Annual net debt repayment of ₹5,000 crore.

Please refer to the `Assumptions` worksheet for the complete inputs and explanatory notes.

## Important limitations and items to review

1. **Cost of capital inputs:** The risk-free rate, equity beta and equity risk premium are marked as provisional/placeholders in the workbook. They should be independently sourced, dated and validated before relying on the WACC.
2. **Share-count and corporate-structure scope:** The workbook uses FY2025 weighted diluted shares and a pre-demerger group scope. These should not be used to infer a current per-share value for a post-demerger company.
3. **Terminal value dependence:** Approximately 70.69% of enterprise value comes from the present value of terminal value, so the result is sensitive to long-term assumptions.
4. **Forecast simplifications:** Certain balance-sheet categories are held flat or treated as balancing items, and forecast exceptional items are assumed to be nil. Review the relevant worksheet notes before using the model for a live transaction or investment decision.
5. **Market price comparison:** The optional market-price input is blank in the submitted workbook, so upside/downside is not calculated.

## Model checks

The submitted workbook's `Checks` worksheet reports:
- Historical income-statement tie-outs within the stated tolerance.
- Historical cash-flow and balance-sheet cash reconciliation checks.
- Balance-sheet balance checks for historical and forecast periods.
- Forecast cash-flow-to-balance-sheet cash checks.

The displayed overall historical status is `OK` for FY2021–FY2025.

## Tools

- Microsoft Excel / compatible spreadsheet software
- Financial statement analysis
- Three-statement financial modelling
- FCFF-based DCF valuation
- WACC and terminal-growth sensitivity analysis

## Disclaimer

This project is for educational and portfolio demonstration purposes only. It is not investment research, financial advice, or a recommendation to buy, sell or hold any security. The model depends on assumptions and historical reporting choices that may materially affect the outputs. Users should independently verify source data, valuation inputs, corporate structure and share count before drawing conclusions.

## Author

**Ayush Raipure**

- GitHub: [ayushraipure](https://github.com/ayushraipure)
