# Projects

A series of independent projects in R, Python, and SQL: statistics and 
machine learning applied to various fields.

---

## Probability & Statistics (R)

**[Convergence rate of the Poisson approximation to the Binomial](https://rpubs.com/VladyslavBarskyi/poisson-binomial-approx)**
Tests the accuracy of the Poisson approximation to the Binomial across a range of λ, using Total Variation Distance as the error metric. Finds the approximation holds within 3% error at λ = 12, and traces the residual error to the variance gap Var(X_Bin) = λ(1−p) < λ = Var(X_Pois).
`R` `Total Variation Distance` `MGF`

**[Empirical verification of the memoryless property of the Geometric distribution](https://rpubs.com/VladyslavBarskyi/geometric-memoryless-simulation)**
50,000-trial Monte Carlo simulation confirming P(Y > a+b | Y > a) = P(Y > b) numerically, by conditioning on survival past a cutoff and comparing against a fresh baseline distribution.
`R` `Monte Carlo Simulation`

---

## Regression & Machine Learning (Python, SQL)

**[Forecasting inflation using macroeconomic indicators](link)**
*(to be added)*

---

## Libraries and Tools

`R`, `Python` (NumPy, pandas, scikit-learn, matplotlib), `SQL` (SQLite), `R Markdown`, `Jupyter`
