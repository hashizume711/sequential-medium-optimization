# Sequential Active Learning for Medium Optimization in mAb Production
This repository contains the source code used in the study “Sequential active learning for medium optimization in mAb production.”
The study integrates Design of Experiments (DOE) and Machine Learning (ML) approaches to iteratively optimize CHO cell culture media for improved monoclonal antibody (mAb) production.

Round3 / Round4 / Round6
Contain Gradient Boosting Decision Tree (GBDT) models used for predicting IgG titers during each optimization round.
These models were trained on experimental datasets and applied to select high-performing medium compositions.

Feature_analysis
Includes scripts for evaluating feature importance and SHAP-based interpretability analysis,
revealing key chemical components contributing to improved IgG production.

nestedCV
Implements nested cross-validation to evaluate the generalization performance of the GBDT model.
Metrics include coefficient of determination (R²), root mean squared error (RMSE), and mean absolute error (MAE).
