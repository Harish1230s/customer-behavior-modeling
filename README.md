# Customer Behavior Modeling

This project explores customer purchase behavior using various statistical models including Poisson, Negative Binomial (NBD), Zero-Inflated models, and Finite Mixture models. The goal is to analyze and predict purchasing patterns based on historical transactional data and evaluate model effectiveness using MLE, AIC, BIC, and Log-Likelihood tests.

## 📊 Part 1: Classical and Regression Models
- Modeled purchase frequency using Poisson and NBD distributions
- Evaluated model fit via log-likelihood and residual comparison
- Compared Poisson Regression and NBD Regression
- Key takeaway: NBD Regression outperformed others for count prediction

## 📈 Part 2: Advanced and Mixture Models
- Implemented Zero-Inflated and Mixture of Poisson/NBD models
- Conducted segmentation to identify customer purchase patterns
- Used AIC/BIC to select optimal model complexity
- Key takeaway: Finite mixture models helped uncover hidden customer segments

## 🧰 Technologies Used
- Python, Jupyter Notebook
- NumPy, SciPy, StatsModels
- R, Word (for reporting)
- Datasets: books, billboard, khakichinos

## 📌 Insights
- NBD Regression consistently had the best fit metrics (AIC/BIC)
- Key predictors of purchasing: household size, income, and age
- Recommended segmentation strategies for personalized marketing

## 📄 Authors
This project was completed as a team submission for BUAN 6383. Contributions were made in modeling, coding, and report preparation.
