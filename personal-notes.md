# What is A/B Testing?
A/B testing is an experimental method that uses statistical analysis to compare two variants (A and B) to determine which performs better. Participants are randomly assigned to Control (A) and Treatment (B) groups, and the impact of a change is measured using statistical tests such as Chi-square, t-test, or logistic regression.

# Key Elements of A/B Testing
- Randomization: Participants must be randomly assigned to Control (A) and Treatment (B) groups to avoid selection bias.
- Hypothesis Definition: Clearly state null hypothesis (H₀) and alternative hypothesis (H₁) before running the test.
- Independent Groups: Each participant should only belong to one group (no overlap).
- Sufficient Sample Size: Ensure enough data points to achieve statistical power and minimize random errors.
- Statistical Testing: Use appropriate tests based on the data type
- Assumption Validation: Check homogeneity of variance (Levene’s Test) and independence between groups before applying statistical tests.
- Effect Size Measurement: Evaluate the impact of the test using Risk Ratio, Cohen’s d, or Odds Ratio to quantify the difference.
- Significance Level & Confidence Interval: Typically, p < 0.05 indicates statistical significance, and confidence intervals help assess result reliability.
- Business Interpretation: Translate statistical results into actionable insights for decision-making.

# Statistical Method Used
- Chi-square test → For comparing categorical outcomes between groups.  
- t-test / Mann-Whitney U test → For comparing numerical outcomes (e.g., time spent on site).  
- Logistic Regression (Logit Model) → For binary outcomes (e.g., whether a customer opens a deposit account or not). It allows for adjusting covariates and estimating the direct impact of the treatment.  