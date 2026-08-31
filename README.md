This repository contains R code for reproducing the simulation study and empirical study for the MSc project _Shifted Moving Block Bootstrap for Granger Causality Testing_.

julescharle/mscproject/Simulation study:
* Power plots - Figures 2,7,8
* QQ plot + 0.95 quantile convergence plot           --- Figures 3,4
* QQ naive vs regression row plot                    --- Figure 5
* Comparison study/Simulation function               --- Main function for comparison study
* Comparison study/Function run                      --- Uses cluster_runner function from Simulation function to create Tables 2,3
* Comparison study/Results as R objects/             --- Folder containing outputs from Function run as .rds files
* Comparison study/Table to view results             --- Useful code to output table from results in Function run
* Comparison study/SUPMAT - boot f stat distribution --- Using results from Function run to create Figure 11

julescharle/mscproject/CAMELS-GB study:
* Test evaluation function             --- Evaluated the rejections for each test on each station as detailed in report
* pval_matrix.rds, pval_matrix.csv     --- Output of Test evaluation function
* Rejection map plot                   --- Figures 6,15 & BH fdr rejections quoted in supmat
* SUPMAT - skewness and kurtosis stats --- Table 6
* SUPMAT - qqplots                     --- Figure 12
* SUPMAT - acf plus variance plots     --- Figure 13
* SUPMAT - AIC histogram               --- Figure 14

