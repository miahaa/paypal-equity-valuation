# PayPal Equity Valuation

Fundamental equity valuation of PayPal Holdings, Inc. using historical financial statement analysis, a five-year operating forecast, discounted cash flow valuation, comparable-company analysis, sensitivity testing, Excel, and Python.

**Project status:** Complete

[Excel valuation model](models/paypal_valuation_model.xlsx) · [Python analysis notebook](analysis/paypal_financial_analysis.ipynb) · [Equity research report](report/PayPal_Equity_Valuation_Report.pdf)

## Key Results

| Valuation Method | Implied Share Price |
|---|---:|
| DCF | $87.08 |
| Forward P/E | $92.74 |
| P/FCF | $65.67 |
| EV/EBITDA | $49.17 |
| Reference Market Price | $52.53 |

Reference market price used in the project: **September 30, 2026**.

The range illustrates how valuation changes with assumptions about growth, profitability, discount rates, and peer selection.

## Historical Performance

PayPal revenue increased from **$25.4B in 2021 to $33.2B in 2025**, representing approximately **6.9% CAGR**. Annual revenue growth slowed to approximately **4.3% in 2025**.

Operating margin improved from approximately **16.8% in 2021 to 18.3% in 2025**. Diluted EPS increased from **$3.52 to $5.41**, or approximately **11.3% annualized growth**.

Free cash flow remained substantial but more volatile:

| Year | Free Cash Flow |
|---|---:|
| 2021 | $4.9B |
| 2022 | $5.1B |
| 2023 | $4.2B |
| 2024 | $6.8B |
| 2025 | $5.6B |

PayPal also materially reduced diluted shares outstanding through repurchases, helping EPS grow faster than revenue.

## Forecast

The model forecasts 2026E–2030E using a moderate-growth base case.

| Assumption | Base Case |
|---|---:|
| 2026 Revenue Growth | 5.0% |
| 2027 Revenue Growth | 5.5% |
| 2028 Revenue Growth | 5.5% |
| 2029 Revenue Growth | 5.0% |
| 2030 Revenue Growth | 4.5% |
| 2030 Operating Margin | 19.3% |
| Normalized Tax Rate | 19.0% |
| D&A / Revenue | 2.8% |
| CapEx / Revenue | 2.6% |
| Change in NWC / Revenue | 1.0% |

## DCF Valuation

Unlevered free cash flow is modeled as:

```text
NOPAT
+ Depreciation & Amortization
- Capital Expenditures
- Change in Net Working Capital
= Unlevered Free Cash Flow
```

The base case uses approximately:

- **WACC:** 9.2%
- **Terminal growth rate:** 2.5%

The resulting DCF implied value is approximately **$87.08 per share**.

## Comparable Company Analysis

Peer companies include:

- Block
- Fiserv
- Global Payments
- Visa
- Mastercard

Block, Fiserv, and Global Payments are used as the closer operating peer group for selected median multiples. Visa and Mastercard are retained as reference companies because their network-based business models and margins differ materially from PayPal's.

Metrics considered include Forward P/E, EV/Sales, EV/EBITDA, and Price/FCF.

## Sensitivity Analysis

The model tests different combinations of WACC and terminal growth. Small changes in these assumptions can materially affect implied share price, so the DCF is best interpreted as a valuation range rather than a single precise estimate.

## Key Takeaways

1. Revenue continues to grow, but growth has slowed.
2. Operating profitability improved by 2025.
3. EPS growth exceeded revenue growth, partly because of share repurchases.
4. Free cash flow remains strong but is more volatile than revenue.
5. The valuation is sensitive to long-term growth and discount-rate assumptions.
6. Relative valuation depends meaningfully on peer selection and the multiple used.

## Risks

- Slower payment-volume or revenue growth
- Competitive pressure from other payment platforms
- Margin deterioration
- Higher capital requirements
- Changes in consumer spending
- Digital-payments regulation
- Higher interest rates and discount rates
- Poor capital allocation through share repurchases
- Overly optimistic terminal-growth assumptions

## Repository Structure

```text
paypal-equity-valuation/
├── README.md
├── analysis/
│   └── paypal_financial_analysis.ipynb
├── models/
│   └── paypal_valuation_model.xlsx
└── report/
    └── PayPal_Equity_Valuation_Report.pdf
```

## Tools and Skills Demonstrated

- Microsoft Excel
- Python
- pandas
- Matplotlib
- Financial statement analysis
- Financial forecasting
- DCF valuation
- CAPM / WACC
- Comparable-company analysis
- Sensitivity analysis
- SEC filing research
- Git / GitHub

## Disclaimer

This project was created for educational and portfolio purposes. It is not investment advice or a recommendation to buy or sell PayPal securities.
