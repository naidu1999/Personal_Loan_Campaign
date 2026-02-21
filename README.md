# Personal_Loan_Campaign
# 🏦 AllLife Bank – Personal Loan Prediction Project

## 📖 Project Overview

AllLife Bank is a US-based bank with a large customer base consisting mainly of **liability customers (depositors)**. However, only a small portion of these customers have taken **personal loans**, which limits the bank’s ability to generate interest-based revenue.

To increase profitability, the bank wants to **identify liability customers who are most likely to accept a personal loan offer** and target them through focused marketing campaigns.

This project uses **Machine Learning techniques** to predict whether a customer will purchase a personal loan and to understand the **key factors influencing loan acceptance**.

---

## 🎯 Business Objective

The objectives of this project are:

- Predict whether a customer will accept a personal loan
- Identify the most important customer attributes influencing loan purchases
- Segment customers based on their likelihood of accepting a loan
- Help the marketing team run **targeted and efficient campaigns**

---

## 🗂 Dataset Description

The dataset contains customer demographic, financial, and banking behavior information collected from AllLife Bank’s existing customers.

Each row in the dataset represents **one customer**.

---

## 📘 Data Dictionary

| Column | Description |
|------|------------|
| ID | Unique customer ID |
| Age | Customer age in years |
| Experience | Years of professional experience |
| Income | Annual income (in thousand USD) |
| ZIP Code | Customer’s residential ZIP code |
| Family | Family size |
| CCAvg | Average monthly credit card spending (in thousand USD) |
| Education | 1: Undergrad, 2: Graduate, 3: Advanced/Professional |
| Mortgage | Mortgage value (in thousand USD) |
| Personal_Loan | Target variable (1 = Accepted, 0 = Not Accepted) |
| Securities_Account | Whether the customer has a securities account |
| CD_Account | Whether the customer has a CD account |
| Online | Uses internet banking (Yes/No) |
| CreditCard | Uses a credit card from another bank |

---

## 🛠 Tools & Technologies Used

- **Programming Language:** Python  
- **Environment:** Google Colab / Jupyter Notebook  
- **Libraries:**
  - pandas – data manipulation
  - numpy – numerical computations
  - matplotlib & seaborn – visualization
  - scikit-learn – machine learning models and evaluation

---

## 🔍 Project Workflow & Work Done

The project is structured into clear and logical stages.

---

### 1️⃣ Data Understanding & Exploration

- Loaded the dataset and reviewed its structure
- Checked dataset dimensions and data types
- Generated statistical summaries for numerical variables
- Checked for missing values and data inconsistencies

This step ensured the dataset was clean and ready for analysis.

---

### 2️⃣ Exploratory Data Analysis (EDA)

EDA was performed to understand customer behavior and relationships between variables.

Key analysis included:
- Distribution of age, income, experience, and credit card spending
- Comparison of customers who accepted vs did not accept loans
- Impact of education, income, and family size on loan acceptance
- Relationship between banking products (CD account, securities account) and loan purchase

Visualizations such as **histograms, boxplots, bar charts, and count plots** were used.

---

### 3️⃣ Data Preprocessing

- Dropped non-informative columns such as Customer ID and ZIP Code
- Converted categorical variables into numerical format where required
- Separated features (X) and target variable (Personal_Loan)
- Split data into training and testing sets

---

### 4️⃣ Model Building

Multiple machine learning models were built and evaluated, such as:

- Logistic Regression
- Decision Tree Classifier
- (Optional) Other classification models

Each model was trained on the training dataset and tested on unseen data.

---

### 5️⃣ Model Evaluation

Models were evaluated using:
- Accuracy score
- Confusion matrix
- Precision, recall, and F1-score

This helped determine which model performs best in predicting loan acceptance.

---

## 📊 Key Insights from the Analysis

- Customers with **higher income** have a significantly higher probability of accepting personal loans
- Customers with **advanced or professional education** are more likely to accept loans
- Having a **CD account or securities account** increases the likelihood of loan acceptance
- Credit card spending (CCAvg) is a strong indicator of loan purchase behavior
- Age alone is not a strong predictor compared to income and education

---

## 💡 Business Recommendations

Based on the analysis and model results, the following recommendations are suggested:

- Target customers with **high income and higher education levels**
- Focus marketing campaigns on customers holding **CD and securities accounts**
- Use model predictions to reduce marketing costs by avoiding low-probability customers
- Personalize loan offers based on customer financial behavior

---

## 📁 Repository Structure
AllLife-Bank-Personal-Loan-Prediction/
│
├── W_AIML_ML_Project_Personal_Loan.ipynb
├── W_AIML_ML_Project_Personal_Loan.html
└── README.md
└── Loan_Modelling.csv

---

## 📌 Conclusion

This project demonstrates how **machine learning classification models** can be used to solve real-world business problems in banking. By predicting loan acceptance probability, AllLife Bank can improve marketing efficiency, increase loan conversions, and enhance overall profitability.

The project combines **EDA, preprocessing, modeling, and business insights**, making it a complete end-to-end data science solution.

---

## 👤 Author

**Rahul Naidu**  
B.Tech – Computer Science (2022)  
Aspiring Data Scientist / Business Analyst  

---

⭐ If you found this project useful, feel free to star the repository!
