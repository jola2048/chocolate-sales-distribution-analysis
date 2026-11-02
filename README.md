# Chocolate Sales Distribution Analysis

## About the Project
This project was created for the **Introduction to Statistical Inference** course. The main objective is to find the appropriate probability distribution for the number of shipped boxes (`Boxes.Shipped`) in a chocolate sales dataset. 

The analysis walks through descriptive statistics, visual inspections (histograms, box plots, QQ plots), and formal hypothesis testing to reject normality. Finally, it compares the log-normal and gamma distributions using goodness-of-fit statistics to determine the optimal model for the underlying data.

## Key Findings
* **Descriptive Statistics:** The data is right-skewed and leptokurtic (median: 135 boxes).
* **Normality Tests:** Both Shapiro-Wilk and Anderson-Darling tests return extremely small p-values, strongly rejecting the null hypothesis of normal distribution.
* **Distribution Fitting:** Based on the Cullen and Frey graph, log-normal and gamma distributions were tested. 
* **Conclusion:** The **gamma distribution** provides a significantly better fit for the data, outperforming the log-normal distribution across Kolmogorov-Smirnov, Cramer-von Mises, and Anderson-Darling statistics, as well as yielding lower AIC and BIC values.

## Technologies and Libraries
* **Language:** R (RMarkdown)
* **Libraries:** `e1071`, `ggplot2`, `nortest`, `rattle`, `ggpubr`, `goftest`, `fitdistrplus`

## Authors
* Jolanta Sułkowska
* Gabriela Machaj
* Kaja Trojanowicz
* Wiktor Łach
