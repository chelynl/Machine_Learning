# Machine Learning Predictive Modeling

### Overview
We are provided data with 3 targets and 127 attributes (v1-v127). Multiple machine learning models will be explored to best predict one of the target variables. We will only be focusing on Binary Target 2 for this project.

### Targets
- cont.target (continuous target variable)
- binary.target1 (binary target)
- binary.target2 (binary target)

For the 2 binary targets, false positives are more costly than false negatives - certainty regarding predicted events is paramount and thus the accuracy of the model might best be scored using positive predictive value or lift at depth of 10-20%. Area under the ROC curve and Averaged Squared Error are also sound and common error metrics used in this application.



|          Model        |    Accuracy   |    AUC    |
| --------------------- | ------------- | --------- |
|  Logistic Regression  |     83.23%    |   0.6463  |
|      Random Forest    |     83.64%    |   0.6226  |
|        XGBoost        |     84.00%    |   0.5702  |
|        LightGBM       |     83.02%    |   -.----  |
|        CatBoost       |     --.--%    |   0.7779  |
|  K-Nearest Neighbors  |     80.72%    |   0.6107  |
