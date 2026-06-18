# fcbayern-poisson-analysis
Statistical analysis of FC Bayern's goal scoring using a Poisson distribution
# Bayern Munich Goal Scoring Analysis

## Objective

To investigate whether Bayern Munich's goals scored per match follow a Poisson distribution.

## Dataset

- Matches analysed: 60
- Total goals scored: 200

## Methodology

1. Collected goal-scoring data.
2. Calculated the mean number of goals per match.
3. Fitted a Poisson distribution.
4. Computed expected frequencies.
5. Performed a Chi-square goodness-of-fit test.

## Results

| Statistic | Value |
|------------|--------|
| Mean (λ) | 3.33 |
| Chi-square Statistic | 0.81947 |
| Degrees of Freedom | 4 |
| p-value | 0.93582 |

## Charts

### Observed vs Expected Frequencies

![Observed vs Expected](images/Observed%20vs%20Expected%20Frequencies.png)

## Conclusion

The Poisson distribution with λ = 3.33 provides an excellent fit to Bayern Munich's goal-scoring data. The Chi-square goodness-of-fit test produced a p-value of 0.93582, indicating no significant difference between the observed and expected frequencies.

## Full Report

[View Report](report.pdf)

## Skills Demonstrated

- Probability Distributions
- Poisson Modelling
- Chi-Square Goodness-of-Fit Testing
- Statistical Data Analysis
- Data Visualization
