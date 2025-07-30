
Spaceship Titanic Survival Prediction Using Machine Learning
========================================

This project addresses the Kaggle competition **"Titanic: Machine Learning from Disaster"**, aiming to predict passenger survival based on various features such as age, gender, passenger class, and more.


Project Objective
------------
The objective is to develop and assess multiple machine learning models to classify passengers as Survived or Not Survived based on the Titanic dataset.

Dataset
----------
The dataset includes:
- train.csv
- test.csv
- gender_submission.csv

Features include:
- Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, etc.

Technologies Used
---------------------
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Python Libraries 

Workflow
-----------
Here is a rewritten and refined version:

### 1. **Data Loading**

* Loaded the training and test datasets using **pandas**.
* Inspected the structure of the datasets and identified missing values.

### 2. **Data Preprocessing**

* Handled missing data:

  * Imputed missing values for **Age**, **Embarked**, and **Fare**.
* Encoded categorical features using **LabelEncoder**.
* Performed feature engineering:
    Performed Feature Engineering through PCA

### 3. **Exploratory Data Analysis (EDA)**

* Explored survival patterns based on key variables 

### 4. **Model Building**

* Trained and evaluated the following machine learning models:


  * **Logistic Regression**
  * **SVM**
  * **Random Forest Classifier**
  * **Gradient Boosting**

* Used **train\_test\_split** for model validation.
* Evaluated performance using **accuracy**, **confusion matrix**, and **classification report**.

### 5. **Submission**

* Chose the best-performing model based on evaluation metrics.
* Generated survival predictions on the test dataset.
* Created a `submission.csv` file for submission to Kaggle.

 Output
---------
The final output is a **CSV file named `submission.csv`**, containing two columns:

* **PassengerId**
* **Survived** (with values 0 or 1 indicating survival status)

 How to Run
-------------
1. Clone the repository or download the Jupyter notebook.
2. Open the notebook in **Google Colab** or **Jupyter Notebook**.
3. Make sure all required libraries are installed.
4. Execute all cells to perform data preprocessing, model training, and submission file generation.

Author
---------
Developed by Group 17 as part of Kaggle Titanic competition practice.
