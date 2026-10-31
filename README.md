**# Sleep \& Lifestyle Analytics \& Predictive Modeling**



\## Project Overview

This project is an end-to-end Data Science analysis and machine learning solution focused on exploring the relationship between lifestyle habits, daily metrics, and sleep disorders. By leveraging the Sleep Health and Lifestyle Dataset, the project uncovers key behavioral and physiological indicators of sleep quality and builds a predictive model to identify individuals at risk.



\---



**## Data Preprocessing \& Feature Engineering**

\- \*\*Blood Pressure Parsing:\*\* Split the composite Blood Pressure feature into independent numeric Systolic\_BP and Diastolic\_BP columns for quantitative analysis.

\- \*\*Data Standardization:\*\* Cleaned and standardized categorical variables (such as unifying BMI categories).

\- \*\*Missing Value Handling:\*\* Handled missing values in target columns (e.g., treating missing sleep disorders as 'None').

\- \*\*Feature Encoding:\*\* Applied One-Hot Encoding (`pd.get\_dummies`) to prepare categorical variables for machine learning models.



\---



**## Exploratory Data Analysis (EDA) \& Insights**

An extensive exploratory data analysis was conducted to uncover hidden patterns:

\- \*\*Sleep Duration vs. Disorders:\*\* Analyzed how variations in sleep hours correlate with conditions like Sleep Apnea and Insomnia.

\- \*\*Stress \& Lifestyle:\*\* Explored the strong negative correlation between sleep duration and high stress levels.

\- \*\*Occupational Stress:\*\* Highlighted high-stress professions using aggregated statistical analysis.

\- \*\*Physical Activity:\*\* Evaluated the impact of daily steps and physical activity on sleep quality.



\---



**## Machine Learning Model**

\- \*\*Algorithm:\*\* Trained a Random Forest Classifier to predict and classify sleep-related conditions based on lifestyle and health metrics.

\- \*\*Data Split:\*\* Split the dataset into training (80%) and testing (20%) sets to ensure rigorous evaluation.

\- \*\*Performance:\*\* Achieved an impressive 88% accuracy, evaluated using precision, recall, and F1-score via a detailed Classification Report.

\- \*\*Feature Importance:\*\* Extracted feature importance metrics to identify which physiological and lifestyle factors most heavily drive the model's predictions.



\---



**## Tech Stack \& Libraries**

\- \*\*Language:\*\* Python

\- \*\*Data Manipulation \& Analysis:\*\* Pandas, NumPy

\- \*\*Machine Learning:\*\* Scikit-learn (Random Forest)

\- \*\*Data Visualization:\*\* Matplotlib, Seaborn

\- \*\*Environment:\*\* Jupyter Notebook

