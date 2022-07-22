# BreakPointCovarianceQFM

## Break Detection in Large Covariance Matrices of High-Dimensional Quantile Factor Models

$\textbf{Abstract}$ The paper proposes a framework for structural break testing and estimation in the structure of large covariance matrices for high-dimensional quantile factor models. The structural break testing utilizes a CUSUM-based detection technique which is flexible to various econometric conditions. The testing methodology relies on vectorized model residuals which captures fluctuations in the underline stochastic processes. Furtherore, we propose a novel data segementation and window estimation procedure which captures the covariance structure and allows to estimate the break-point locations based on the entries of the matrix from both the common components of the high-dimensional quantile factor model as well as the corresponding error components of the model. 

# Installation (under development)

The R package ‘BreakPointCovarianceQFM’ will be able to be installed from Github.

## Usage 

```R

# After development the package will be able to be installed using
install.packages("BreakPointCovarianceQFM")
library("BreakPointCovarianceQFM")

```


# Key References

[1] Aue, A., Hörmann, S., Horváth, L., & Reimherr, M. (2009). "Break detection in the covariance structure of multivariate time series models". The Annals of Statistics, 37(6B), 4046-4087.

[2] Anastasiou, Andreas, and Piotr Fryzlewicz. "Detecting multiple generalized change-points by isolating single ones." Metrika (2021): 1-34.

[3] Anastasiou, Andreas, Ivor Cribben, and Piotr Fryzlewicz. "Cross-covariance isolate detect: a new change-point method for estimating dynamic functional connectivity." Medical image analysis 75 (2022): 102252.

[4] Barigozzi, M., Cho, H., & Fryzlewicz, P. (2018). "Simultaneous multiple change-point and factor analysis for high-dimensional time series". Journal of Econometrics, 206(1), 187-225.

[5] Baltagi, B. H., Kao, C., & Wang, F. (2021). "Estimating and testing high dimensional factor models with multiple structural changes". Journal of Econometrics, 220(2), 349-365.

[6] Li, Y. N., Li, D., & Fryzlewicz, P. (2022). "Detection of multiple structural breaks in large covariance matrices". Journal of Business & Economic Statistics, (just-accepted), 1-43.

[7] Chen, L., Dolado, J. J., & Gonzalo, J. (2021). "Quantile factor models". Econometrica, 89(2), 875-910.

## Bibliography

- Csörgö, M., and Horváth, L. (1997). Limit theorems in change-point analysis.

- De Gooijer, J. G. (2006). Detecting change-points in multidimensional stochastic processes. Computational statistics & data analysis, 51(3), 1892-1903.

- Vostrikova, L. Y. E. (1981). Detecting “disorder” in multidimensional random processes. In Doklady Akademii Nauk (Vol. 259, No. 2, pp. 270-274). Russian Academy of Sciences.

# Code of Coduct

Please note that the ‘BreakPointCovarianceQFM’ project will be released with a Contributor Code of Coduct (under construction). By contributing to this project, you agree to abide by its terms. 

# Declarations

The author declares no conflicts of interest. 

In particular, the author declares that has no affiliations with or involvement in any organization or entity with any financial interest (such as honoraria; educational grants; participation in speakers’ bureaus; membership, employment, consultancies, stock ownership, or other equity interest; and expert testimony or patent-licensing arrangements), or non-financial interest (such as personal or professional relationships, affiliations) in the subject matter discussed in the manuscript and implemented in the R package.
