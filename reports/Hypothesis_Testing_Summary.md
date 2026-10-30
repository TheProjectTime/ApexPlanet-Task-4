# Hypothesis Testing Summary

## 1. Research Question

Is there a statistically significant difference in average order revenue per customer between Electronics and Fashion?

## 2. Hypotheses

- **Null Hypothesis (H₀):** There is no statistically significant difference in average order revenue per customer between Electronics and Fashion.
- **Alternative Hypothesis (H₁):** There is a statistically significant difference in average order revenue per customer between Electronics and Fashion.

## 3. Statistical Method

Welch's Independent-Samples T-Test was used to compare the average order revenue per customer between the two categories.

To improve the independence of the observations, the seven customers who purchased from both categories were excluded. The final comparison included customers who purchased exclusively from one of the two categories.

The significance level was set at 0.05.

## 4. Results

| Measure                            | Electronics-only | Fashion-only |
| ---------------------------------- | ---------------: | -----------: |
| Number of customers                |              344 |          149 |
| Average order revenue per customer |      ₹143,621.03 |  ₹129,713.92 |

**Statistical results:**

- T-statistic: 1.3045
- P-value: 0.193027
- Mean difference: ₹13,907.12
- 95% Confidence Interval: -₹7,069.57 to ₹34,883.80
- Significance Level: 0.05

## 5. Interpretation

The p-value (0.193027) is greater than the significance level (0.05). Therefore, we fail to reject the null hypothesis.

Although Electronics has a higher observed average order revenue per customer than Fashion, the difference is not statistically significant.

The 95% confidence interval includes zero, which is consistent with this finding.

## 6. Business Conclusion

The analysis does not provide sufficient statistical evidence of a difference in average order revenue per customer between Electronics-only and Fashion-only customers.

Therefore, the business should not assume that Electronics customers generate significantly higher average order revenue based on this analysis.

Further research using additional customer, product, and transaction information may help identify factors influencing revenue.

## 7. Final Finding

The analysis demonstrates that a higher observed average does not necessarily indicate a statistically significant difference. Statistical testing helps businesses make more reliable, data-driven decisions.

**Limitation:** Seven customers who purchased from both categories were excluded from the final comparison. The findings therefore apply to customers who purchased exclusively from Electronics or Fashion, rather than all customers.
