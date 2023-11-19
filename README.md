# DID-Estimate-Analysis-econometrics-

### Difference in difference 

Difference-in-differences (DiD) is a statistical method used in econometrics and social sciences to estimate the causal effect of a treatment, policy, or intervention on an outcome of interest. It is particularly useful when conducting observational studies, where researchers cannot randomly assign subjects to treatment and control groups.

The key idea behind the difference-in-differences approach is to compare changes in the outcome variable over time between two or more groups, one of which is exposed to the treatment or intervention (the "treatment group"), while the other(s) serve as a control group. By comparing the differences in outcomes before and after the treatment between these groups, researchers can estimate the causal effect of the treatment.

Here's a basic outline of how the difference-in-differences method works:

1. Identify two or more groups: You need to have at least two groups - one that receives the treatment (the treatment group) and one that does not (the control group).
2. Measure the outcome: Collect data on the outcome variable of interest for both groups before and after the treatment is implemented.
3. Calculate the differences: Compute the difference in outcomes for each group before and after the treatment. This will give you four difference values: the change in the treatment group's outcome before and after treatment and the change in the control group's outcome before and after treatment.
4. Calculate the "difference in differences": The main estimate of the treatment effect is obtained by subtracting the change in the control group's outcome from the change in the treatment group's outcome. This difference in differences represents the causal effect of the treatment.
5. Assess statistical significance: Conduct statistical tests to determine whether the observed difference in differences is statistically significant, which helps determine if the treatment had a real impact.

Difference-in-differences helps control for time-invariant unobservable factors that may affect the outcome by comparing changes within each group over time and then comparing the differences between groups. It is a quasi-experimental method commonly used to study the impact of policies, interventions, or events when randomized controlled trials (RCTs) are not feasible or ethical.

### Problem statement 

In this project we are asked to estimate the announcement effect of Volcker Rule (new banking regulation in US) on US banks. More specifically, analyze at least:

(i) Did the banks decrease their trading assets after the announcement of the new regulation?

(ii) If they responded to the regulation, which banks responded most and which banks least?
Why?

(iii) Remember robustness, and how should banks or regulators use these results?


## Volcker Rule

The Volcker Rule is mandated as one of the core elements in the larger financial reform legislation of the Dodd-Frank Act that was signed into law on July 21, 2010.

The Volcker Rule prohibits banks from engaging in certain non-banking activities such as proprietary trading or hedge fund and private equity investments.

Banks with the trading ratio more than 3 is probably going to be the most affected with this act.

## Propensity Score

ropensity score is a statistical concept and methodology used in observational studies to address issues related to confounding variables when estimating the causal effect of a treatment, intervention, or exposure on an outcome. It is particularly useful when conducting observational research, where researchers cannot control the assignment of subjects to treatment groups as they can in randomized controlled trials (RCTs).

The propensity score is essentially the probability of an individual or unit being assigned to a particular treatment group, based on their observed characteristics or covariates. The idea is to create a single scalar value (the propensity score) for each subject that summarizes their likelihood of receiving the treatment. This score is calculated using a logistic regression model or other suitable statistical methods, where the treatment assignment (binary: 1 or 0 for treated or not treated) is the dependent variable, and the covariates are the independent variables.

Once the propensity scores are calculated, researchers can use them in various ways, such as:

1. Matching: Pairing or matching individuals with similar propensity scores between the treatment and control groups. This helps create balanced groups in terms of observed covariates, reducing the impact of confounding variables.

2. Stratification: Dividing the sample into strata or subgroups based on similar propensity scores and then comparing treatment effects within each stratum. This allows for more precise comparisons.
3. Weighting: Assigning weights to each observation based on their propensity score. This gives more weight to observations that are less common in the treatment or control group, which can help correct for imbalances.
4. Regression adjustment: Including the propensity score as a covariate in outcome analyses to control for the probability of treatment assignment.

## Documentations

[Difference in difference](https://www.publichealth.columbia.edu/research/population-health-methods/difference-difference-estimation) 

[Propensity score](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4267761/)

[Python](https://docs.python.org/3/)

[Volcker Rule](https://www.investopedia.com/terms/v/volcker-rule.asp)

[Regression for DID](https://timeseriesreasoning.com/contents/introduction-to-the-difference-in-differences-regression-model/)

## Authors

- [@Anshumaan - <anshuphukan031@gmail.com>](https://github.com/Anshumaan031)
