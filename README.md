# Stack Overflow Developer Survey Analysis

Survey-based analysis of developer compensation, work mode, education, and role patterns using the Stack Overflow developer survey.

## Project summary

This project analyzes the Stack Overflow developer survey with a focus on salary distributions, work mode differences, education level effects, and role-based summaries. The notebook combines exploratory analysis with statistical inference, including bootstrap-based confidence intervals and hypothesis tests.

## Problem

This project explores the 2025 Stack Overflow Developer Survey to understand:

> 1. distinctions between remote and hybrid job modes in technology and information sectors; and
> 2. the effects of education on income level.

The required analysis includes EDA, descriptive statistics, two-sample salary comparisons between hybrid and remote workers, bootstrap inference, confidence intervals, median testing, and ANOVA-based education-level comparisons for North American respondents.

## Data

- Stack Overflow developer survey responses
- numeric salary fields such as `ConvertedCompYearly`
- categorical survey fields such as work mode, education, and developer type

## Techniques

- pandas data cleaning and filtering
- exploratory data analysis and summary statistics
- box plots and distribution plots
- bootstrap resampling
- Welch and pooled t-tests
- ANOVA and bootstrap hypothesis testing
- category-level comparisons across developer groups

## Achievements

- analyzed 20,407 cleaned Stack Overflow survey responses with salary and age anomaly checks
- handled extreme salary values before inference using percentile-based trimming or winsorization depending on the statistical test
- found a statistically robust salary difference between remote and hybrid workers after trimming, with remote workers earning about USD 15,231 more on average
- validated the remote-versus-hybrid salary result using Welch's t-test, bootstrap confidence intervals, and Mood's median test
- showed that North American salary means differ across Bachelor's, Master's, and Professional degree groups using ANOVA and bootstrap validation
- practiced concise statistical reporting with visual evidence under a strict report-length constraint

## Repository structure

| File | Role |
| --- | --- |
| `xu_1007901512_assignment1.ipynb` | Main analysis notebook |
| `xu_1007901512_assignment1.pdf` | Exported report version of the notebook |

## Skills practiced

This project practices survey-data analysis, robust outlier handling, parametric and non-parametric hypothesis testing, bootstrap simulation, confidence-interval construction, ANOVA, and evidence-based statistical writing.
