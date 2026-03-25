# marketing-mix-modeling-channel-roi
Marketing Mix Modeling (MMM) project analyzing channel ROI, adstock effects, and budget optimization using Python.


# Marketing Mix Modeling (MMM): Channel ROI & Budget Optimization

## Objective
This project develops a Marketing Mix Model (MMM) to quantify the impact of different marketing channels on sales and provide data-driven budget allocation recommendations.

## Methodology

### 1. Baseline Model
- Built an OLS regression model using raw media spend.
- Identified initial channel contributions and limitations.

### 2. Adstock Transformation
- Incorporated carryover effects to capture delayed media impact.
- Improved model performance (R² increased from ~0.71 to ~0.83).

### 3. Saturation (Diminishing Returns)
- Modeled non-linear response to media spend.
- Captured realistic marketing behavior.

### 4. ROI Analysis
- Estimated channel-level contribution.
- Calculated ROI as contribution per dollar spent.

## Key Findings

- **Radio and TV** are the most effective channels with the highest ROI.
- **Search** acts as a lower-funnel conversion channel with moderate efficiency.
- **Social** shows low or negative ROI, suggesting inefficiency or need for optimization.

## Business Recommendations

- Increase investment in **Radio and TV** to drive growth.
- Optimize **Search** for efficiency rather than scale.
- Re-evaluate **Social strategy** (targeting, creatives, or measurement).

## Limitations

- No external control variables (seasonality, pricing, macro factors)
- Potential multicollinearity between channels
- Results based on aggregated data

## Tools Used
- Python (pandas, statsmodels, matplotlib, seaborn)

## Next Steps
- Introduce causal inference (incrementality testing)
- Add external variables (seasonality, promotions)
- Explore Bayesian MMM approaches
