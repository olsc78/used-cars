# Used cars analysis
Build a model to predict the prices of used cars in order to identify the most relevant factors that drive the price.

## Dataset
- The CSV dataset can be found here: data/vehicles.csv
- It contains more than 425,000 samples of used cars and their features

## Notebook and Repository
- The analysis of the data supporting the findings can be found in the "used cars - olsc.ipynb" notebook
- Git Repository is located at https://github.com/olsc78/used-cars.git

## Summary of findings

### Data
The data exploration analysis revealed that the dataset needed a lot of cleaning, preparation and engineering. Among other things, the dataset contained:
- duplicated rows and many missing values in various proportions, 
- erroneous data and outliers
- high-cardinality categorical features
- skewed distributions
- non-linear relationship
- correlated independant variables
  
Multiple transformation, imputation and engineering techniques have been used to preserve the informative power of the dataset.

### Models
Several models have been tested (Linear regression, Ridge regularization) as well as several hyperparameters and cross validation methods (holdout and k-fold).

### Findings
- Regarding the factors that drive the price, some brands are obviously playing in different groups (luxury cars, entry-level, etc.). Nonetheless, regardless of these categories of cars, some features have been identified as having an impact on price, whether positive or negative. 
- As such and not surprisingly, less mileage is an important factor to keep the price as high as possible, as well as a clean status.
- Other statuses can also be interesting which speak to other type of customers
- Gas, diesel, automatic transmission are to be preferred, as well as black and white cars
- Some other findings are listed in the notebook
