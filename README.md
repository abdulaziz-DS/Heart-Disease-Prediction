# Heart Disease Prediction

This project focuses on predicting heart disease using machine learning techniques. The dataset includes various health indicators such as age, cholesterol levels, and exercise-induced angina. Multiple classification models were implemented, and a Gradio-based web application was deployed for real-time predictions.

## Features

- **Exploratory Data Analysis (EDA):**
  - Visualization and statistical analysis of dataset features.
  - Identification of outliers and feature distributions.

- **Data Preprocessing:**
  - Handling categorical and numerical data.
  - Label encoding for categorical variables.
  - Splitting the dataset into training and testing sets.

- **Machine Learning Models Implemented:**
  - **Logistic Regression (Accuracy: 83%)**
  - **Support Vector Machine (SVM) (Accuracy: 85%)**
  - **Decision Tree (Accuracy: 78%)**

- **Model Evaluation:**
  - Performance metrics such as accuracy and classification reports.
  - Comparison of different models to determine the most effective predictor.

- **Deployment with Gradio:**
  - An interactive web-based UI for heart disease prediction.
  - Users can input health parameters and receive instant predictions.

## Dataset

The dataset used contains various health parameters such as:
- **Age**
- **Sex**
- **Chest Pain Type**
- **Resting Blood Pressure**
- **Cholesterol Levels**
- **Fasting Blood Sugar**
- **Resting ECG**
- **Maximum Heart Rate**
- **Exercise-Induced Angina**
- **Oldpeak (ST depression)**
- **ST Slope**
- **Heart Disease Diagnosis (Target Variable)**

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the dataset in CSV format and place it in the appropriate directory.

## Usage

### Running the Jupyter Notebook
1. Open `Heart Disease Prediction.ipynb` in Jupyter Notebook.
2. Run all cells to:
   - Perform data preprocessing and EDA.
   - Train and evaluate different classification models.
   - Compare accuracy metrics.

### Running the Gradio Web App
1. Start the Gradio interface:
   ```bash
   python heart_disease_prediction.py
   ```
2. Enter health parameters in the UI.
3. Receive an instant prediction on the likelihood of heart disease.

## Results

- **SVM achieved the highest accuracy (85%)**, making it the most effective model in this case.
- **Logistic Regression performed well (83%)** and provides a simpler, interpretable model.
- **Decision Tree had the lowest accuracy (78%)**, likely due to overfitting.

## Conclusion

This study highlights the importance of choosing the right classification model for medical predictions. SVM outperformed the other models, demonstrating its robustness in heart disease prediction. The Gradio-based web app provides a user-friendly interface for real-time predictions, making the model accessible to non-technical users.

## Future Enhancements

- Implementing ensemble models for improved accuracy.
- Expanding the dataset to enhance model generalization.
- Integrating the model into a full-scale web or mobile application.

## Acknowledgments

- **Gradio** for enabling easy web deployment.
- **Scikit-learn** for robust machine learning tools.


## Contact

For any queries or collaboration opportunities, please contact:
- **Name:** Abdul Aziz Shaikh
- **Email:** shaikhaziz9920@gmail.com

