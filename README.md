# Diabetes Prediction — Machine Learning Models in R

An academic machine-learning course project comparing classical statistical and machine-learning methods on a diabetes classification dataset.

## Project overview

- **Problem:** Predict the binary diabetes outcome from clinical-style tabular features.
- **Approach:** Data inspection and preprocessing, followed by model fitting and comparison.
- **Methods explored:** Linear regression, logistic regression, linear discriminant analysis (LDA), k-nearest neighbors (KNN), PCA and K-means, decision trees, random forests, and support vector machines (SVM).
- **Language:** R, with analysis written in R Markdown.

## Project files

- [R Markdown source](./期末報告.Rmd) — analysis code and visualizations
- [Final PDF report](./機器學習_期末報告.pdf) — project write-up and reported results
- [Word report](./期末報告.docx) — editable report

## Reproducing the analysis

1. Install R and the packages used in the source: `readr`, `MASS`, `class`, `tree`, `randomForest`, and `e1071`.
2. Obtain the diabetes dataset used for the original coursework. The CSV is **not included in this repository**.
3. Edit the local file path in `期末報告.Rmd` (currently a Windows example path) to point to your copy of `diabetes.csv`.
4. Run the R Markdown analysis in RStudio or render it using your R Markdown environment.

**Limitations:** This repository archives a course project rather than a turnkey reproducible benchmark. Model comparisons and numeric results should be read in the attached report; this README does not claim independent clinical validation.

## Academic context

Team coursework project (December 2024). Both contributors are credited in the original R Markdown report.
