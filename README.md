# Engineering-Flight-With-Paperclips
A factorial experimental study analyzing how paperclip placement affects paper airplane flight distance utilizing regression modeling and permutation tests. 


## Objective
The goal of this study is to determine whether the placement of paperclips on a paper airplane significantly impacts flight distance and to identify which configurations lead to improved performance.

## Experimental Design
- Factorial design with multiple paperclip placement configurations
- Controlled indoor testing environment
- Randomized throw order to reduce systematic bias
- Multiple replications per treatment to ensure reliable inference

## Methodology
- Exploratory visualizations (boxplots and jitter plots)
- Linear regression modeling with treatment indicators
- Assumption diagnostics (residual plots, normality checks)
- Permutation tests to support inference under mild assumption violations
- Comparison of treatment effects using confidence intervals

## Key Findings
- Paperclip placement has a measurable impact on flight distance
- Certain configurations consistently outperform others
- Permutation tests reinforce conclusions drawn from parametric models
- Experimental design and randomization play a critical role in reliable inference

## Files
- `FinalProject.Rmd` — Full analysis and code
- `FinalProject.pdf` — Rendered report with results and discussion
- `data/` — Experimental data collected during the study

## Tools & Libraries
- R
- tidyverse
- knitr
- broom
- ggplot2

## Notes
This project was completed as part of a statistics course and refined to serve as a portfolio-quality example of experimental design, statistical modeling, and data-driven decision making.
