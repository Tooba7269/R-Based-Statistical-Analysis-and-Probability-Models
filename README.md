# R-Based-Statistical-Analysis-and-Probability-Models
This holds solutions to an advanced statistical and probability-based test. Discussed issues are probability theory, Poisson and normal distributions, Bayes Theorem, and statistical hypothesis testing (simple and multiple ANOVA). The project also consists of the detailed quantitative analyses and visualizations of the real-world situations/data.
## Overview
This repository contains solutions to a series of statistical and probability-based problems solved using R. The tasks include probability analysis, modeling distributions (Poisson and Normal), applying Bayes’ Theorem, and performing hypothesis testing with ANOVA. Each question is solved programmatically with R scripts and includes visualizations and results.

---

## Features
1. **Probability Analysis**:
   - Construct contingency tables.
   - Calculate conditional probabilities and analyze event independence.

2. **Poisson Distribution Modeling**:
   - Calculate probabilities of football team scores (e.g., exact, cumulative).
   - Extend Poisson models for multiple games.

3. **Normal Distribution Analysis**:
   - Find probabilities for heart rate thresholds.
   - Determine thresholds for high-risk groups (90th percentile).

4. **Bayes’ Theorem**:
   - Analyze customer satisfaction probabilities by guitar brands.
   - Use posterior probabilities to interpret real-world scenarios.

5. **Lens Coating Performance**:
   - Perform descriptive statistics (mean, standard deviation).
   - Create visualizations (boxplots).
   - Conduct ANOVA and post-hoc tests to recommend the best lens coating.

---

## Repository Structure
- **`scripts/`**: Contains R scripts for solving each problem.
- **`data/`**: Includes input datasets like `lenses.csv`.
- **`results/`**: Contains outputs such as tables, plots, and summary statistics.
- **`reports/`**: Final report (`Assessment2024_Solutions.pdf`) documenting all solutions.

---

## Getting Started

### Prerequisites
Ensure you have R installed on your system. Install required packages by running:
```R
install.packages(c("ggplot2", "dplyr", "stats", "TukeyC", "reshape2"))
