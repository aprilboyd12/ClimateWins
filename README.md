# ClimateWins
This project applies supervised learning and optimization techniques to evaluate weather station data and predict whether conditions are suitable for a picnic. By testing multiple models—including Decision Trees, Artificial Neural Networks (ANN), and K-Nearest Neighbors (KNN)—the project compares performance, identifies potential overfitting, and recommends the most reliable model for deployment.

Project Objectives

Evaluate accuracy of multiple machine learning models on weather station data.

Detect potential overfitting (e.g., Sonnblick station’s misleading 100% accuracy).

Assess the impact of dataset imbalance on predictive performance.

Recommend the best model for ClimateWins’ picnic-weather predictions.

Methods & Tools

Data preprocessing & bias check to account for imbalanced stations.

Optimization & hyperparameter tuning to reduce variance and improve performance.

Modeling techniques: Decision Trees, ANN, and KNN.

Comparison framework to assess accuracy, interpretability, and robustness.

Results

KNN achieved the highest overall accuracy across stations.

Sonnblick station showed overfitting due to lack of variation in outcomes.

Dataset imbalance is a major contributor to inflated performance metrics.

Recommendation

KNN is recommended as the primary model for predicting picnic-suitable weather. However, improving dataset balance will further strengthen model reliability and generalization.

Next Steps

Expand dataset to include more balanced weather outcomes.

Explore ensemble models for improved performance.

Refine optimization for real-world deployment.
