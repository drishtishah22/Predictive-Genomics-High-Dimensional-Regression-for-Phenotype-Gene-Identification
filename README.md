# Predictive-Genomics-High-Dimensional-Regression-for-Phenotype-Gene-Identification
This project, a highlight from a Johnson & Johnson hackathon, dives deep into the complex world of high-dimensional genetic data. Our core mission was to pinpoint the specific genes that significantly influence a given phenotype, analyzing a dataset of 2000 gene expressions from 50 mice.

Tackling the challenge of 'more features than samples' (p>>n), we engineered a robust analytical pipeline:

We started by intelligently screening down the vast number of genes to a more manageable, yet still high-dimensional, subset of 200.

Utilized Lasso Regression for its ability to perform automatic feature selection, resulting in a sparse, interpretable model, alongside Ridge Regression to effectively manage multicollinearity within the data.

Investigated Bayesian Regression to understand its unique advantages and suitability for high-dimensional genomic analysis.

We successfully identified key genes driving the observed phenotype, providing valuable insights. The project also delivered a clear comparison of regularized regression techniques, showcasing their power in both feature selection and predictive accuracy for complex biological datasets.

Tech Stack: Python (NumPy, pandas, scikit-learn, matplotlib, seaborn), Statistical Modeling (OLS, Ridge, Lasso, Bayesian Regression).
