# Attrition_Analytics

📌 Project Overview
This project focuses on Employee Attrition Analysis using Machine Learning techniques.  
The goal is to analyze employee data, understand the factors influencing attrition, and build predictive models to classify whether an employee is likely to leave the organization.

The project covers the complete data analytics pipeline, including data cleaning, exploratory data analysis (EDA), preprocessing, and model training.


📂 Dataset Description
The dataset contains employee-related information such as demographic details, job role, salary, and work experience.

🔢 Features
- Numerical attributes such as income, experience, age, and other HR metrics
- Categorical attributes such as department, gender, job role, etc.

🎯 Target Variable
- Attrition 
  - 0 → Employee stayed  
  - 1 → Employee left  


⚙️ Data Preprocessing
The following preprocessing steps were performed:
- Handling missing values using median imputation for numerical features
- Duplicate record removal
- Outlier treatment using the Interquartile Range (IQR) method
- Encoding categorical variables using Label Encoding
- Feature scaling using StandardScaler


📊 Exploratory Data Analysis (EDA)

🔹 Univariate Analysis
- Count plot for Attrition distribution
- Histograms with KDE for numerical features
- Boxplots for outlier detection

🔹 Bivariate Analysis
- Boxplots of numerical variables
- Scatter plots to observe feature distributions

🔹 Multivariate Analysis
- Pair plot to analyze relationships between numerical variables

EDA helped in understanding data distribution, skewness, and relationships between features before model building.


🤖 Machine Learning Models Implemented
The following classification models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)

Train–test split was performed with an 80:20 ratio, and model performance was evaluated using accuracy scores on both training and testing data.



📈 Results
- Tree-based models such as **Random Forest** performed well due to their ability to handle non-linear relationships and outliers.
- The comparison of multiple models helps in selecting the best-performing algorithm for attrition prediction.



🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab




