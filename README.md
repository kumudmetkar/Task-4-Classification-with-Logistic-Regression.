**Logistic Regression Binary Classifier - Breast Cancer Detection**

**Objective**

To build a binary classifier using **Logistic Regression** to predict whether a tumor is **malignant** or **benign** using the **Breast Cancer Wisconsin Diagnostic Dataset**.

**Dataset**

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data 
file - data.csv 

**Tools & Libraries**
- Python
- Pandas
- Scikit-learn (sklearn)
- Matplotlib
- Seaborn

 **Steps Performed**

1. **Loaded and preprocessed data**
   - Dropped irrelevant columns (e.g., ID)
   - Converted categorical target (`M`/`B`) to numeric (`1`/`0`)

2. **Exploratory Data Analysis (EDA)**
   - Checked for missing values
   - Reviewed distributions and correlations

3. **Train/Test Split**
   - 80% training and 20% testing data

4. **Standardized Features**
   - Scaled features using `StandardScaler`

5. **Built Logistic Regression Model**
   - Trained using `LogisticRegression()` from `sklearn`

6. **Evaluated the Model**
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC-AUC Score & ROC Curve

7. **Threshold Tuning**
   - Explained sigmoid function
   - Adjusted classification threshold from 0.5 to 0.4
  
**What I Learned**

- Basics of binary classification
- How logistic regression works
- Use of sigmoid function 
- Evaluation of models using confusion matrix, ROC-AUC
- How to tune threshold for better performance

