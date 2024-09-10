# Distributed Regression Modeling on Apache Spark

## Overview

Predicting the Mohs hardness of minerals based on their properties.

## Dataset

### Kaggle Playground Series - Season 3

- **Competition Start:** Nov 14, 2023
- **Competition End:** Dec 4, 2023
- **Evaluation Metric:** Median Absolute Error (MedAE)

### Data Description

- **Train Data:** Used to train the regression model.
- **Test Data:** Used to evaluate the performance of the model.
- **Evaluation Metric:** Median Absolute Error (MedAE), which is calculated as:
  \[
  \text{MedAE}(y, \hat{y}) = \text{median}(|y_i - \hat{y}_i|, \ldots, |y_n - \hat{y}_n|)
  \]
  where \(\hat{y}_i\) is the predicted value and \(y_i\) is the ground truth for each observation \(i\).

Code in regression.ipynb
