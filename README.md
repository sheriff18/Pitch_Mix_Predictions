**Predicting Pitch Types for Each Batter: A Machine Learning Approach**

**Overview**
This project aims to develop a predictive model that forecasts the types of pitches (Fastball, Breaking Ball, Off-Speed) faced by each batter in the 2024 MLB season. The model is built using historical data from the 2021 to 2023 MLB seasons, providing actionable insights for batters based on their expected pitch distribution.


**Introduction**
The ability to accurately predict pitch types significantly impacts a batter's success in baseball. This project leverages machine learning techniques to build a model that predicts pitch categories, helping batters anticipate the types of pitches they will face during games.

**Data**
The dataset used for this analysis spans the 2021 to 2023 MLB seasons and includes data on 314 MLB players. It contains over one million rows and 56 columns. Features irrelevant to pitch type prediction, such as post-pitch events and variables with high missing rates (e.g., base runners), were excluded to focus on relevant information.

**Approaches to Prediction**
This analysis employs two approaches to predict pitch mixes for the 2024 season:

**Naïve Approach**: This method calculates the average occurrence of each pitch type for every batter using historical data, serving as a baseline for evaluation.
Modeling Approach: This approach uses advanced modeling techniques, including Random Forest and XGBoost, to predict pitch types based on various game features.
Modeling Techniques
Random Forest: An ensemble learning method that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting.
XGBoost: An advanced implementation of gradient boosting that builds trees sequentially, learning from the errors of previous trees and incorporating regularization techniques to enhance robustness.


**Limitations**
The naïve prediction method assumes that past performance will directly predict future outcomes, potentially overlooking changes in player performance and situational factors.
Random Forest and XGBoost models may not fully capture nuances influenced by game context or batter-pitcher matchups.
Class imbalances in the dataset may still affect model performance despite mitigation efforts.

**Future Work**
Refinement of models to enhance predictive accuracy.
Exploration of additional features that may provide critical context for pitch selection.
