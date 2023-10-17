# Algerian-Forest-Fire-Prediction-R
This Git repository houses the codebase for the Algerian Forest Fire Prediction project, a comprehensive data analysis and prediction system designed to anticipate and assess forest fire incidents in Algeria. 

# Algerian Forest Fire Prediction

This repository contains the codebase for the Algerian Forest Fire Prediction project, focusing on accurate forest fire prediction and analysis in Algeria. Through this project, we aimed to develop robust models that accurately predict forest fire incidents based on various environmental factors. We employed advanced statistical techniques, hypothesis testing, and machine learning algorithms to achieve this goal.

## Project Highlights

- **Data Preprocessing and Analysis:** The project started with extensive data preprocessing and exploratory data analysis. We loaded the dataset, handled missing values, and converted variables into appropriate data types. Additionally, we performed in-depth analysis using visualizations, scatter plots, histograms, and QQ plots to understand the data distribution and relationships between variables.

- **Feature Selection:** To address multicollinearity issues, we applied feature selection techniques such as removing highly correlated variables and Variable Inflation Factor (VIF) analysis. This step aimed to enhance the models' accuracy and interpretability.

- **Modeling:**
  - **Logistic Regression: Trained a Logistic Regression model using selected features to predict forest fire incidents. The model performed well, demonstrating the significance of chosen variables in predicting fire occurrences.
  - **K-Nearest Neighbors (KNN):** Explored different values of k and employed cross-validation to fine-tune the model, utilizing the KNN models. The best-performing KNN model was chosen based on accuracy and validated on the test set.
  - **Random Forest:** The Random Forest model was optimized through a thorough tuning process, selecting appropriate hyperparameters. Feature importance analysis revealed critical variables impacting forest fire incidents.

## Repository Structure

- **`DA_Project_Data Preprocessing and Analysis.Rmd`:** This file contains the initial data preprocessing steps, exploratory data analysis, feature extraction, and visualization techniques used in the project.

- **`ModelingLogisticRForest.RMd`:** Contains Logistic Regression and Random Forest models for forest fire prediction. The file includes feature selection, model training, evaluation, and performance metrics analysis.

- **`ModelingKNN.Rmd`:** In this file, the K-Nearest Neighbors (KNN) algorithm is implemented, fine-tuning the model for optimal k, and evaluating its performance on the test dataset.

## Usage Guide

1. **Clone the Repository:**
   ```
   git clone https://github.com/username/Algerian-Forest-Fire-Prediction.git
   ```

2. **Run the Notebooks:**
   - Open `DA_Project_Data Preprocessing and Analysis.Rmd`, `ModelingLogisticRForest.RMd`, and `ModelingKNN.Rmd` in your preferred R environment (RStudio, Jupyter Notebook, etc.).
   - Execute the code cells sequentially to reproduce the analysis, model training, and evaluation.

3. **Explore Results:**
   - Analyze the generated visualizations, performance metrics, and model insights to gain a comprehensive understanding of the forest fire prediction process.

## Conclusion

Through rigorous data analysis, feature selection, and machine learning modeling, this project provides valuable insights into forest fire incidents in Algeria. The implemented models serve as powerful tools for prediction and analysis, aiding in proactive measures and decision-making to mitigate the impact of forest fires.
