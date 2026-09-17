# Statistical Analysis in R

A collection of quantitative analyses in R demonstrating exploratory data analysis, statistical inference, regression modeling, and model evaluation across demographic, biological, and time-series datasets.

The projects progress from exploring and visualizing data to testing statistical hypotheses and building interpretable predictive models.

## Analyses

| Project                       | Focus                                                                       | Selected methods                                                                                                                                             |
| ----------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Exploratory Data Analysis** | Explore distributions, relationships, and structure across several datasets | Descriptive statistics, distribution analysis, correlation, visualization, time-series exploration, Simpson's paradox                                        |
| **Statistical Inference**     | Formulate and test hypotheses across biological and socioeconomic examples  | Assumption checking, t-tests, proportion tests, non-parametric tests, confidence intervals                                                                   |
| **Regression Modeling**       | Build, refine, and evaluate statistical models                              | Linear and multiple regression, transformations, multicollinearity, residual diagnostics, autoregression, logistic regression, Cook's distance, ROC analysis |

### Exploratory Data Analysis

Explores socioeconomic, demographic, and time-series datasets using reusable R functions, statistical summaries, distribution plots, and correlation analysis. The analysis also investigates Titanic survival patterns and Simpson's paradox.

**[View report](https://leonavracar.github.io/r-statistical-analysis/exploratory_data_analysis.html)** · [View source](analysis/exploratory_data_analysis.Rmd)

### Statistical Inference

Applies statistical testing to questions involving paired measurements, survival rates, biological growth, gene proportions, and salary distributions. Emphasis is placed on selecting appropriate tests, checking assumptions, formulating hypotheses, and interpreting statistical evidence.

**[View report](https://leonavracar.github.io/r-statistical-analysis/statistical_inference.html)** · [View source](analysis/statistical_inference.Rmd)

### Regression Modeling

Develops and evaluates regression models across demographic, socioeconomic, time-series, and biomedical datasets. Topics include data transformation, variable selection, multicollinearity, residual and influence diagnostics, autoregression, logistic regression, and ROC-based model evaluation.

**[View report](https://leonavracar.github.io/r-statistical-analysis/regression_modeling.html)** · [View source](analysis/regression_modeling.Rmd)

## Tools

**R** · **R Markdown** · **Statistical Modeling** · **Data Visualization**

Selected packages include `car`, `MASS`, and `pROC`.

## Repository Structure

```text
analysis/    Source R Markdown analyses
docs/        Rendered HTML reports and GitHub Pages site
```
