# Diabetes Prediction using Machine Learning

This project uses a machine learning model to predict whether an individual is diabetic or non-diabetic based on specific medical features. The classification is binary:
- `0` = Non-diabetic
- `1` = Diabetic

##  Dataset

The dataset used in this project is the **Pima Indians Diabetes Dataset**, which can be found on [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

### Features Included:

| Feature                   | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| Pregnancies               | Number of times pregnant                                                    |
| Glucose                   | Plasma glucose concentration after 2 hours in an oral glucose tolerance test |
| BloodPressure             | Diastolic blood pressure (mm Hg)                                           |
| SkinThickness             | Triceps skin fold thickness (mm)                                           |
| Insulin                   | 2-Hour serum insulin (mu U/ml)                                             |
| BMI                       | Body mass index (weight in kg/(height in m)^2)                             |
| DiabetesPedigreeFunction  | Diabetes pedigree function (family history influence)                      |
| Age                       | Age in years                                                               |
| Outcome                   | Class variable: 0 (Non-diabetic), 1 (Diabetic)                             |

##  Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn (sklearn)

## Model Details

- **StandardScaler**: Used to normalize the feature data, improving model performance and training stability.
- **train_test_split**: Splits the dataset into training and testing sets (typically 80/20) to evaluate generalization performance.
- **Support Vector Machine (SVM)**: Trained using a linear kernel to classify diabetic vs non-diabetic samples.
- **accuracy_score**: Evaluates how well the model predicts the correct labels on the test set.

  
##  Requirements

Install the required Python libraries:

```bash
pip install numpy pandas scikit-learn

