# PayPal Equity Valuation

A fundamental equity valuation of PayPal Holdings, Inc. using historical financial statement analysis, a five-year operating forecast, discounted cash flow valuation, comparable-company analysis, and sensitivity testing.

## Project Overview

This project evaluates PayPal's historical financial performance and estimates its equity value using multiple valuation approaches.

The analysis focuses on:

- Revenue growth
- Operating profitability
- Net income and EPS
- Free cash flow generation
- Capital structure
- Share repurchases
- Five-year financial forecasting
- Discounted Cash Flow valuation
- Comparable-company valuation
- WACC and terminal-value sensitivity

## Key Results

| Valuation Method | Implied Share Price |
|---|---:|
| DCF | $87.08 |
| Forward P/E | $92.74 |
| P/FCF | $65.67 |
| EV/EBITDA | $49.17 |
| Reference Market Price | $52.53 |

The wide valuation range illustrates how strongly equity valuation depends on assumptions regarding future growth, profitability, discount rates, and comparable-company selection.

## Historical Performance

PayPal generated revenue of approximately:

- 2021: $25.4B
- 2022: $27.5B
- 2023: $29.8B
- 2024: $31.8B
- 2025: $33.2B

Revenue grew at approximately a 6.9% CAGR from 2021 through 2025.

However, annual revenue growth slowed over the period, reaching approximately 4.3% in 2025.

### Profitability

Operating margin increased from approximately 16.8% in 2021 to 18.3% in 2025.

Net income increased from approximately $4.2B in 2021 to $5.2B in 2025.

Diluted EPS increased from $3.52 to $5.41 over the same period, representing approximately 11.3% annualized growth.

EPS growth exceeded revenue growth partly because PayPal materially reduced its diluted share count through share repurchases.

### Free Cash Flow

Free cash flow remained strong but more volatile than revenue:

| Year | Free Cash Flow |
|---|---:|
| 2021 | $4.9B |
| 2022 | $5.1B |
| 2023 | $4.2B |
| 2024 | $6.8B |
| 2025 | $5.6B |

2025 free cash flow margin was approximately 16.8%.

PayPal also repurchased approximately $6.1B of shares during 2025, exceeding annual free cash flow for the period.

## Financial Forecast

The model includes a five-year forecast from 2026E through 2030E.

Base-case assumptions include:

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

The forecast assumes moderate revenue growth combined with gradual operating-margin improvement.

## Discounted Cash Flow Valuation

Unlevered free cash flow is calculated as:

```text
NOPAT
+ Depreciation & Amortization
- Capital Expenditures
- Change in Net Working Capital
= Unlevered Free Cash Flow
```

The projected cash flows are discounted using WACC.

### WACC

The model estimates a WACC of approximately 9.2%.

The calculation incorporates:

- Risk-free rate
- PayPal equity beta
- Equity risk premium
- Cost of debt
- Corporate tax rate
- Market-value capital structure

### Terminal Value

The base case uses:

```text
WACC: ~9.2%
Terminal Growth Rate: 2.5%
```

Using these assumptions, the DCF produces an implied equity value of approximately:

**$87.08 per share**

## Sensitivity Analysis

Because terminal value represents a significant portion of DCF enterprise value, the project tests different combinations of:

- WACC
- Terminal growth rate

The sensitivity analysis demonstrates that relatively small changes in long-term assumptions can materially affect implied share price.

This reinforces why a DCF should be interpreted as a valuation range rather than a single precise estimate.

## Comparable Company Analysis

PayPal was compared with payment and financial-technology companies including:

- Block
- Fiserv
- Global Payments
- Visa
- Mastercard

Primary valuation metrics considered include:

- Forward P/E
- EV / Sales
- EV / EBITDA
- Price / Free Cash Flow

Block, Fiserv, and Global Payments were used as the closer operating peer group when calculating selected median multiples.

Visa and Mastercard were retained as reference companies but were treated separately because their payment-network business models and profitability profiles differ materially from PayPal's.

## Valuation Cross-Check

Different valuation methodologies produced substantially different results:

```text
Forward P/E     $92.74
DCF             $87.08
P/FCF           $65.67
EV/EBITDA       $49.17
Market Price    $52.53
```

The DCF and Forward P/E approaches produced the highest values, while the EV/EBITDA methodology generated a result closer to the reference market price.

The difference highlights the importance of understanding what each valuation multiple captures rather than relying on a single methodology.

## Key Takeaways

The historical analysis suggests several important trends:

1. PayPal continues to grow, but revenue growth has slowed.

2. Operating profitability improved despite slower top-line growth.

3. EPS grew faster than revenue, partly because aggressive share repurchases reduced diluted shares outstanding.

4. Free cash flow remains substantial but has been more volatile than revenue.

5. PayPal's estimated value is particularly sensitive to long-term growth expectations and the discount rate.

6. Relative valuation varies substantially depending on which peer group and valuation multiple are used.

## Risks to the Valuation

Major risks include:

- Slower payment-volume or revenue growth
- Competitive pressure from other payment platforms
- Margin deterioration
- Higher-than-expected capital requirements
- Changes in consumer spending
- Regulatory changes affecting digital payments
- Higher interest rates and discount rates
- Share repurchases creating less value if executed at unattractive prices
- Terminal-growth assumptions proving too optimistic

## Project Structure

```text
paypal-equity-valuation/
│
├── README.md
│
├── data/
│
├── models/
│   └── paypal_valuation_model.xlsx
│
├── analysis/
│   └── charts/
│
└── report/
```

## Excel Model

The full model is available here:

`models/paypal_valuation_model.xlsx`

The workbook contains:

- Historical financial statements
- Key financial metrics
- Five-year forecast
- WACC calculation
- DCF valuation
- Terminal-value analysis
- Sensitivity analysis
- Comparable-company analysis
- Valuation summary

## Tools Used

- Microsoft Excel
- Financial statement analysis
- Discounted Cash Flow modeling
- Comparable-company valuation
- CAPM / WACC analysis
- SEC filings
- GitHub

## Disclaimer

This project was created for educational and portfolio purposes. It is not investment advice or a recommendation to buy or sell PayPal securities.