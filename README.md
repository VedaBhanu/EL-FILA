# EL-FILA
Ensemble Learning based Fault-Model for Interconnection Links in ASNoCs. Please do not copy the code, it is currently in review. Once the manuscript gets accepted, you may browse through it. Thanks for your kind coperation.  

# **Dataset Information**

# .csv files
* Data_lwf.csv - Main Dataset with length, width and bandwidth as input attributes.
* Error_Metrics.csv - To store error metrics outcomes for each algorithm
* Errors_FT.csv - To store error metrics outcomes after fine-tuning

# Libraries
* Pandas
* matplotlib
* seaborn
* scikit-learn

# Algorithms
## Individual Techniques:
* Linear Regression
* SVR-Linear
* SVR-Quadratic
* SVR-Cubic
* Gaussian Process Regression 

## Ensemble Techniques:
*  Bagging Meta-Estimator
* Bagging - Random Forest
* Bagging - AdaBoost
* Boosting - Gradient Boost
* Boosting - XG Boost

# Future Work
- [ ] Get More Attributes
- [ ] Expand the dataset considering more floorplan data
