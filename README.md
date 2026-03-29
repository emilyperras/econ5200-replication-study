# ECON 5200 — Replication Study and Extension, Emily Perras

**Card, D., & Krueger, A. B. (1994)**  
*Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania.*

This project replicates and extends one of the most impactful papers in labor economics, which challenged the original theory that minimum wage increases reduce employment. Using fast food restaurant data from New Jersey and Pennsylvania, this study evaluates whether the 1992 minimum wage increase was passed through to employment or consumer prices.

---

## Issue and Findings

The primary finding is that increasing the minimum wage did not lead to job losses. In New Jersey, employment rose slightly from about 20.4 to 21.0 workers per restaurant, while in Pennsylvania it declined from about 23.3 to 21.2. This results in a net increase of approximately 2.75 workers per restaurant following the policy change.

Aditionally, there is no evidence that restaurants raised prices to offset higher labor costs. Across soda, fries, and entrée items, price changes are close to zero, indicating little to no price pass-through.

---

## Methodology

This analysis applies a difference-in-differences (DiD) research design to compare changes in outcomes between two groups: fast food restaurants in New Jersey (treatment group) and those in Pennsylvania (control group).

To implement this, the dataset is structured with observations before and after the policy change for each restaurant. Employment is measured using full-time equivalent (FTE) workers, which combines full-time employees, managers, and part-time workers into a collective figure. A regression framework is then used to estimate the treatment effect by interacting a treatment indicator (New Jersey and Pennsylvania) with a time indicator (before and after the policy).

For the extension, the same DiD framework is applied to price outcomes (soda, fries, and entrée prices) to test for cost pass-through. We also ran additional checks using a data-driven method (Lasso) to select which variables to include. The results stayed the same, suggesting they are not driven by missing factors but instead reflect the actual impact of the policy change rather than differences between stores.

---

## Visual Analysis

The main graph presents estimated price effects across different fast food chains following the minimum wage increase. Each point represents the estimated treatment effect, and the horizontal lines represent the corresponding confidence intervals.

The key takeaway is that nearly all estimates are centered around zero. For example, the overall estimated change in soda prices is approximately -0.0001, and after incorporating additional controls, it remains near zero at +0.0004. Most chains show no meaningful change, while one chain (Wendy’s) shows a small decrease of about -0.05. This evidence indicates no consistent pattern of price increases following the policy.

---

## What This Means

These findings suggest that moderate increases in the minimum wage may not reduce employment or lead to higher consumer prices, contrary to standard theoretical predictions.

For policymakers, this implies that wage increases can improve worker earnings without necessarily harming job availability. For businesses, the results suggest that firms may have adjusted through alternative profit margins or operational improvement rather than reducing employment or raising prices.
These findings highlight the importance of data-driven evidence, as real-world business operations and restaurant economics are not always as clear-cut as theory implies.
