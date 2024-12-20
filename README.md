# CancerScope: Breast Cancer Subtype Classification Using Machine Learning

## Abstract
CancerScope is a machine learning project that classifies breast cancer subtypes using advanced techniques. The study employs Logistic Regression, Random Forest, Gradient Boosting Machines (GBMs), and Neural Networks to handle challenges like class imbalance, high-dimensional data, and subtype misclassification. Using a dataset of 1,500 samples from the American University of Beirut Medical Center (AUBMC), preprocessing techniques such as SMOTE, PCA, and normalization were applied. Results show Neural Networks achieving an F1-score of 93.52%, Random Forest yielding an F1-score of 94.71%, and Gradient Boosting achieving an F1-score of 93.66%.

## Directory Structure
* **Model Notebooks**:
  - `1-Final_LogisticRegression.ipynb`: Logistic Regression implementation.
  - `2-Final_NeuralNetwork.ipynb`: Neural Network implementation.
  - `3-Final_Random_Forest.ipynb`: Random Forest with hyperparameter tuning.
  - `4-Final_GradientBoosting.ipynb`: Gradient Boosting with optimized parameters.
* **Preprocessing**:
  - `Preprocessing_Code.ipynb`: Generates preprocessed datasets.
  - `Original_data_breast.csv`: Raw dataset.
  - `Version1_data_breast.csv`, `Version2_data_breast.csv`, `Version3_data_breast.csv`: Preprocessed datasets.
  - `Test_Set.csv`: Test dataset.
* **Final Datasets**:
  - `Final_Version_data_breast.csv`: Preprocessed dataset used in modeling.

## How to Run
1. **Preprocessed Data**:
   - The preprocessed datasets are already included; there is no need to re-run the preprocessing.
   - Run `Preprocessing_Code.ipynb` to regenerate the datasets if required.
2. **Run Models**:
   - Open the respective notebooks (`1-4`) and execute the code to train and evaluate models.

# Key Results

•⁠  ⁠*Logistic Regression*: F1-score of 58.56%, accuracy of 60%.
•⁠  ⁠*Random Forest*: F1-score of 94.71%, accuracy of 95%.
•⁠  ⁠*Neural Networks*: F1-score of 93.52%, accuracy of 90.20%.
•⁠  ⁠*Gradient Boosting Machines (GBMs)*: F1-score of 93.66%, accuracy of 94%.
