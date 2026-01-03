# Lead Conversion Prediction

## 📌 Project Overview
This project focuses on predicting which leads are most likely to convert into paying customers. With the rapid growth of online education, companies require data-driven insights to optimize marketing, enhance resource allocation, and boost customer acquisition efficiency.  

As the data scientist, I analyzed the dataset, applied machine learning models, and provided actionable insights to identify high-value leads.

## 🎯 Objectives
- Build a machine learning model to predict lead conversion.
- Identify the key drivers influencing conversion.
- Create lead profiles to support targeted marketing strategies.

## 📊 Dataset
The dataset contains:
- **Demographics** (e.g., age, occupation).
- **Engagement details** (website visits, profile completion, interactions).
- **Channel interactions** (ads, referrals, campaigns).
- **Target**: Whether the lead converted (`status`).

*(Dataset not included here due to confidentiality, but a similar structure can be found in kaggle.)*

## 🛠️ Technologies Used
- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (Decision Trees, Random Forests, Hyperparameter Tuning)
- Jupyter Notebook
- Data visualization tools

## 🔑 Key Steps
1. **Exploratory Data Analysis (EDA)** – Univariate, bivariate, and multivariate analysis.
2. **Data Preprocessing** – Handling missing values, encoding categorical features, and scaling.
3. **Modeling** – Built Decision Tree and Random Forest models, with hyperparameter tuning via GridSearchCV.
4. **Evaluation** – Focused on recall to minimize false negatives (losing real customers).
5. **Insights** – Time spent on the website, profile completion, and first interaction channel were the strongest predictors of conversion.

## 📈 Results
- **Best Model**: Tuned Random Forest Classifier.
- **Performance**: Achieved higher recall compared to baseline models, making it effective for reducing missed customer opportunities.
- **Insights**: Personalized campaigns targeting users with high website engagement and complete profiles can significantly improve conversions.

