Menstrual Fluid RNA-seq Analysis in Endometriosis

Overview:

This project re-analyzes publicly available RNA-seq data from Schwalie et al. (2024) to explore whether gene-expression patterns in menstrual fluid can help distinguish women with endometriosis from healthy controls.

A key focus is accounting for multiple samples contributed by the same woman.

Dataset: The dataset contains menstrual fluid RNA-seq data from women with endometriosis and healthy controls.
It includes:
1.Fresh and cultured samples.
2.Different cell populations (CD45+ and CD45-).
3.Multiple samples from some donors.

Data: https://zenodo.org/records/11105267
Original Paper: Schwalie et al. (2024)

Analysis:
The project includes:
  1.Data exploration and quality checks.
  2.Gene expression normalization and PCA.
  3.Logistic regression to classify patients and controls.
  4.Comparison of random splitting and leave-one-woman-out validation.
  5.Sensitivity analysis with and without blood-related genes.
  6.Differential gene expression analysis (ongoing).

Preliminary Results:
Random library-level split: AUC = 0.86
Leave-one-woman-out validation: AUC = 0.46
The results suggest that repeated samples from the same woman may influence model performance. The small number of participants also limits the conclusions.

Tools:
Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

Project Status:
In progress. Initial data exploration, PCA, and predictive modelling are complete. Differential expression analysis and comparison with the original study are next.

Acknowledgements:
Data from Schwalie et al. (2024), Single-cell characterization of menstrual fluid at homeostasis and in endometriosis.
