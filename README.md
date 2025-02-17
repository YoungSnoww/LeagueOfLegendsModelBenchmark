### Specification Statement

**Title: Benchmarking Models for Predicting League of Legends Game Outcomes**

**Objective:**
The objective of this project is to benchmark various machine learning models to predict the outcome of League of Legends (LoL) games using in-game data. The goal is to identify the most accurate and efficient model for predicting game outcomes based on features such as the number of kills, gold earned, and other relevant in-game statistics.

**Context**:
League of Legends is a multiplayer online battle arena (MOBA) game in which two teams, the blue team and the red team, compete against each other. The game features three lanes, a jungle area, and five distinct roles for players. The primary objective is to destroy the opposing team's Nexus to secure victory.

**Feasibility**:
To ensure the project feasibilty a Proof of Concept (PoC) has been realised and is accessible on Github [here](https://github.com/YoungSnoww/poc-lol-prediction/tree/main).

**Group Composition:**
The project will be conducted by a group of 5 people, each responsible for different aspects of the benchmarking process, including data preprocessing, model training, evaluation, and documentation.

The group is made of:
- Valentin Woehrel - vw207@kent.ac.uk
- Quentin Erdinger - qe3@kent.ac.uk
- Simon Bandiera - sb2440@kent.ac.uk
- Hugo Galan - hg310@kent.ac.uk
- Timothée Lesellier, PM - tl456@kent.ac.uk

**Datasets:**

This datasets was created by scraping the official RIOT API. 
The data is composed of 200,000 games with 109 features each. The features include in-game statistics such as kills, deaths, assists, gold earned, and other relevant information. 

[Url](https://epitechfr-my.sharepoint.com/:f:/g/personal/hugo_galan_epitech_eu/Ersjm19Jx6dJroDmOviZyssBvaW9g4kKFzqm0-2fxcz46A?e=NW2ezW)

**Models to Benchmark:**
The following models will be benchmarked to predict the outcome of LoL games:
1. **Logistic Regression**: A baseline model to establish a performance benchmark.
2. **Decision Trees**: To capture non-linear relationships in the data.
3. **Random Forest**: An ensemble method to improve the performance of decision trees.
4. **Gradient Boosting Machines (GBM)**: Including XGBoost and LightGBM for robust performance.
5. **Support Vector Machines (SVM)**: With different kernel functions to handle complex data patterns.
6. **Neural Networks**: Including Multi-Layer Perceptrons (MLP) and Convolutional Neural Networks (CNN) for capturing intricate data relationships.
7. **k-Nearest Neighbors (k-NN)**: To evaluate the performance of instance-based learning.
8. **Naive Bayes**: To assess the performance of probabilistic classifiers.
9. **AdaBoost**: An ensemble method to boost the performance of weak classifiers.
10. **CatBoost**: A gradient boosting library that handles categorical features efficiently.

**Evaluation Metrics:**
The performance of each model will be evaluated using the following metrics:
- **Accuracy**: The proportion of correctly predicted game outcomes.
- **Precision**: The proportion of correctly predicted positive outcomes (wins) out of all predicted positive outcomes.
- **Recall**: The proportion of correctly predicted positive outcomes out of all actual positive outcomes.
- **F1-Score**: The harmonic mean of precision and recall.
- **AUC-ROC**: The area under the Receiver Operating Characteristic curve to evaluate the model's ability to distinguish between positive and negative outcomes.
- **Confusion Matrix**: To visualize the performance of the model in terms of true positives, true negatives, false positives, and false negatives.

**Methodology:**
1. **Data Preprocessing**: Clean and preprocess the datasets to handle missing values, outliers, and normalize the features.
2. **Feature Engineering**: Create new features that may improve the predictive power of the models.
3. **Model Training**: Train each model using the preprocessed datasets.
4. **Hyperparameter Tuning**: Optimize the hyperparameters of each model using techniques such as grid search or random search.
5. **Evaluation**: Evaluate the performance of each model using the specified evaluation metrics.
6. **Comparison**: Compare the performance of all models to identify the most accurate and efficient model for predicting LoL game outcomes.

**Deliverables:**
1. **Benchmarking Report**: A detailed report comparing the performance of all models.
2. **Codebase**: A repository containing the code used for data preprocessing, model training, and evaluation.
3. **Presentation**: A presentation summarizing the findings and recommendations.

