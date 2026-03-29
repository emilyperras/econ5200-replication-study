# ECON 5200 — Replication Study and Extension, Emily Perras

**Card, D., & Krueger, A. B. (1994)**  
*Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania.*

This project replicates and extends one of the most influential empirical papers in labor economics, which challenged the traditional prediction that minimum wage increases reduce employment. Using fast food restaurant data from New Jersey and Pennsylvania, this study evaluates whether the 1992 minimum wage increase was passed through to employment or consumer prices.

---

## Issue and Findings

The primary finding is that increasing the minimum wage did not lead to job losses. In New Jersey, employment rose slightly from about 20.4 to 21.0 workers per restaurant, while in Pennsylvania it declined from about 23.3 to 21.2. This results in a net increase of approximately 2.75 workers per restaurant following the policy change.

In addition, there is no evidence that restaurants raised prices to offset higher labor costs. Across soda, fries, and entrée items, estimated price changes are close to zero, indicating little to no price pass-through.

---

## Methodology

This analysis applies a difference-in-differences (DiD) research design to compare changes in outcomes between two groups: fast food restaurants in New Jersey (treatment group) and those in Pennsylvania (control group).

The core idea is to measure how outcomes change over time in both groups and then isolate the effect of the policy by comparing those changes. If both groups were following similar trends before the minimum wage increase, any divergence observed afterward can be attributed to the policy itself.

To implement this, the dataset is structured with observations before and after the policy change for each restaurant. Employment is measured using full-time equivalent (FTE) workers, which combines full-time employees, managers, and part-time workers into a consistent metric. A regression framework is then used to estimate the treatment effect by interacting a treatment indicator (New Jersey vs. Pennsylvania) with a time indicator (before vs. after the policy).

For the extension, the same DiD framework is applied to price outcomes (soda, fries, and entrée prices) to test for cost pass-through. Additional robustness checks are performed using a data-driven variable selection approach, which confirms that the results are not sensitive to omitted factors. This ensures that the estimated effects reflect the policy change rather than underlying differences between stores.

---

## Visual Analysis

The main graph presents estimated price effects across different fast food chains following the minimum wage increase. Each point represents the estimated treatment effect, and the horizontal lines represent the corresponding confidence intervals.

The key takeaway is that nearly all estimates are centered around zero. For example, the overall estimated change in soda prices is approximately -0.0001, and after incorporating additional controls, it remains near zero at +0.0004. Most chains show no meaningful change, while one chain (Wendy’s) shows a small decrease of about -0.05.

Overall, the visual evidence indicates no consistent pattern of price increases following the policy.

---

## What This Means

These findings suggest that moderate increases in the minimum wage may not reduce employment or lead to higher consumer prices, contrary to standard theoretical predictions.

For policymakers, this implies that wage increases can improve worker earnings without necessarily harming job availability. For businesses, the results suggest that firms may adjust through alternative margins rather than reducing employment or raising prices.

More broadly, this project demonstrates the importance of empirical analysis in evaluating economic policy, as real-world outcomes may differ from theoretical expectations.
