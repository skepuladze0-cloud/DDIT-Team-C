# Activity: ROI Model Development

## Purpose

Build the quantified financial case for the recommended strategic option with three scenarios, stated assumptions, and payback estimates.

## Output
ROI Model v1

## Time
45 minutes

## Process

1. Build the row structure (five-year model):
   - Year 0: investment (all cost categories, negative cash flow)
   - Years 1 to 5: net annual cash flows (revenue uplift minus operating cost change minus ongoing technology cost)

| Year | Downside | Base Case | Upside |
|---|---|---|---|
| Year 0 (Investment) | -1,200,000 | -1,000,000 | -1,000,000 |
| Year 1 | 150,000 | 300,000 | 500,000 |
| Year 2 | 250,000 | 450,000 | 700,000 |
| Year 3 | 350,000 | 600,000 | 900,000 |
| Year 4 | 450,000 | 750,000 | 1,100,000 |
| Year 5 | 550,000 | 900,000 | 1,300,000 |
     
   - Cumulative cash flow row (running total; payback period is when this crosses zero)

| Year | Downside | Base Case | Upside |
|---|---|---|---|
| Year 0 | -1,200,000 | -1,000,000 | -1,000,000 |
| Year 1 | -1,050,000 | -700,000 | -500,000 |
| Year 2 | -800,000 | -250,000 | 200,000 |
| Year 3 | -450,000 | 350,000 | 1,100,000 |
| Year 4 | 0 | 1,100,000 | 2,200,000 |
| Year 5 | 550,000 | 2,000,000 | 3,500,000 |

Payback Period:
Downside: Year 4
Base Case: Between Year 2–3
Upside: Year 2

   - NPV row (Year 0 investment plus sum of discounted annual cash flows at 10% discount rate)

| Scenario | NPV |
|---|---|
| Downside | ~    $150,000 |
| Base Case| ~ $1,200,000 |
| Upside | ~ $2,300,000 |

1. Build three scenario columns: Downside, Base Case, Upside. Each differentiated on your most important single assumption.


The scenarios are differentiated based on efficiency gains and adoption speed of AI solutions:
Downside: Slower adoption, lower cost savings (~5–7%)   
Base Case: Moderate adoption, expected efficiency gains (~10–12%)   
Upside: Fast adoption, strong optimization (~15%+)   

2. Build the assumptions table below the model: list every non-sourced number with [A1], [A2], etc. For each: the assumption, the basis, and Year 1 cash flow impact if it changes by 20%.

| Ref | Assumption | Basis | +-20% Impact on Year 1 |
|---|---|---|---|
| [A1] | Initial AI investment = $1M | Estimated cost of chatbot, routing AI, integration | ±$200,000 |
| [A2] | Cost reduction from route optimization = 10% | Industry benchmarks (8–15%) | ±$60,000 |
| [A3] | Customer service cost reduction = 25% | Benchmarks (20–35%) | ±$50,000 |
| [A4] | Revenue uplift from better service = 5% | Improved retention and delivery speed | ±$40,000 |
| [A5] | Annual tech maintenance cost = $150,000 | Cloud + system maintenance estimate | ±$30,000 |
| [A6] | Adoption rate reaches 70% by Year 3 | Gradual implementation | ±$70,000 |
## Benchmark ranges for calibration

| Use case | Benchmark | Source |
|---|---|---|
| AI customer service | 20 to 35% reduction in cost per interaction | McKinsey 2025 |
| AI credit scoring | 30 to 50% reduction in underwriting cost | Accenture financial services |
| AI diagnostics | 10 to 40% reduction in diagnostic time | Stanford AI Index |
| Route optimisation | 8 to 15% reduction in fuel/vehicle cost | McKinsey supply chain |
| Document processing | 60 to 80% reduction in manual processing time | Accenture automation |
| Churn reduction | 10 to 25% reduction in churn rate | McKinsey customer analytics |

Do not use these benchmarks as your numbers. Use them to calibrate your assumptions.

## Deliverable

Save as:
`roi_model_v1.md`
