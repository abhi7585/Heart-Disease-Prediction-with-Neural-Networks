# Heart-Disease-Prediction-with-Neural-Networks

## Introduction
This project aims to predict the likelihood of a person's survival based on various health indicators using neural networks. The dataset used for this analysis is `HEART.csv`, containing features relevant to heart health.

## Dataset
- **File**: `HEART.csv`
- **Features**: 
  - `AgeAtStart`: Age at the start of the study
  - `Sex`: Gender (1 = male, 0 = female)
  - `Cholesterol`: Cholesterol level
  - `Chol_Status`: Cholesterol status
  - `Smoking`: Smoking status (0 = nonsmoker, 1 = past smoker, 2 = current smoker)
  - `Smoking_Status`: Smoking status
  - `AgeCHDdiag`: Age at coronary heart disease diagnosis
  - `Height`: Height in inches
  - `Weight`: Weight in pounds
  - `MRW`: Metropolitan relative weight
  - `Weight_Status`: Weight status
  - `Status`: Survival status (0 = alive, 1 = dead)
  - `DeathCause`: Cause of death
  - `AgeAtDeath`: Age at death

## Instructions
1. **Setup**: Ensure you have the required libraries installed (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `tensorflow`).
2. **Data Loading**: Load the dataset `HEART.csv`.
3. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Scale numerical features.
4. **Model Building**:
   - Construct a neural network model using TensorFlow/Keras.
   - Train the model on the training data.
5. **Model Evaluation**:
   - Evaluate the model's performance on the test data.
   - Calculate metrics like accuracy and error rate.
6. **Prediction**:
   - Make predictions using the trained model.
   - Compare predicted labels with actual labels.

## Usage
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
   ```
2. Run the Jupyter Notebook `heart_disease_prediction.ipynb`.
3. Follow the instructions within the notebook to preprocess data, build, train, and evaluate the model.
4. Experiment with different architectures or hyperparameters for better performance.

## Contributors
- [Abhishek Tripathi](https://www.linkedin.com/in/abhishek-tripathi-analyst/)

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README with additional details or sections as per your preference!
