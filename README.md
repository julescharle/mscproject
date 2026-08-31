R code reproducing the simulation study and empirical study from the MSc project
*Shifted Moving Block Bootstrap for Granger Causality Testing*.

Tables and Figures numbered are to cross-reference from report. Below are descriptions of each file, by folder.

### Simulation study

| File | Contents |
| --- | --- |
| `Power plots.R` | Figures 2, 7, 8 |
| `QQ plot + 0.95 quantile convergence plot.R` | Figures 3, 4 |
| `QQ naive vs regression row plot.R` | Figure 5 |

#### Simulation study/Comparison study

| File | Contents |
| --- | --- |
| `Simulation function.R` | Core simulation function: `cluster_runner()` |
| `Function run.R` | Runs `cluster_runner()` to produce Tables 2, 3 |
| `Results as R objects/` | Saved `.rds` outputs from `Function run.R` |
| `Table to view results.R` | Formats the saved results into tables |
| `SUPMAT - boot f stat distribution.R` | Figure 11 |

### CAMELS-GB study

| File | Contents |
| --- | --- |
| `Test evaluation function.R` | Evaluates rejections for each test at each station |
| `pval_matrix.rds`, `pval_matrix.csv` | Output of the above |
| `Rejection map plot.R` | Figures 6, 15; BH FDR rejections quoted in the supplement |
| `SUPMAT - skewness and kurtosis stats.R` | Table 6 |
| `SUPMAT - qqplots.R` | Figure 12 |
| `SUPMAT - acf plus variance plots.R` | Figure 13 |
| `SUPMAT - AIC histogram.R` | Figure 14 |
