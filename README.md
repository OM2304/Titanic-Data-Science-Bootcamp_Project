# Titanic-Data-Science-Bootcamp_Project

# Titanic Survival Prediction Project

## Project Description
[cite_start]This project focuses on analyzing the historical Titanic dataset to predict whether a passenger would have survived the disaster[cite: 1]. [cite_start]By using data science techniques, we explore the factors—such as gender, age, and passenger class—that influenced the chances of survival[cite: 1]. [cite_start]The project follows the complete data science pipeline, from cleaning raw data to training a predictive model[cite: 1].

## Objective & Learning Outcomes
* [cite_start]**Objective:** To build a reliable machine learning model that classifies Titanic passengers as "Survived" or "Not Survived" based on specific input features[cite: 1].
* **Learning Outcomes:**
    * [cite_start]**Data Cleaning:** Managing missing values and removing redundant information using Pandas[cite: 1].
    * [cite_start]**Data Visualization:** Identifying trends and patterns using Seaborn and Matplotlib[cite: 1].
    * [cite_start]**Feature Engineering:** Creating more descriptive data points to improve model performance[cite: 1].
    * [cite_start]**Machine Learning:** Implementing and training a Logistic Regression model[cite: 1].
    * [cite_start]**Model Evaluation:** Measuring accuracy and understanding results through a Confusion Matrix[cite: 1].

## Technologies & Libraries Used
[cite_start]The project was developed using **Python** in a **Google Colab** environment[cite: 1]. The following libraries were essential for the analysis:
* [cite_start]**Pandas:** For data manipulation and creating the DataFrame[cite: 1].
* [cite_start]**NumPy:** For handling numerical operations[cite: 1].
* [cite_start]**Matplotlib & Seaborn:** For generating graphs and visual heatmaps[cite: 1].
* [cite_start]**Scikit-Learn:** For splitting the data and implementing the Machine Learning algorithm[cite: 1].

## Project Workflow (Step-by-Step)
### Step 1: Data Collection
[cite_start]The Titanic dataset (CSV) was loaded into a Pandas DataFrame[cite: 1]. [cite_start]An initial inspection was performed using `.head()` and `.info()` to understand the columns and data types[cite: 1].

### Step 2: Data Cleaning
The dataset was cleaned to ensure accuracy:
* [cite_start]Missing **Age** values were filled with the average (mean) age[cite: 1].
* [cite_start]Missing **Embarked** values were filled with the most frequent port (mode)[cite: 1].
* [cite_start]The **Deck** column was removed due to excessive missing data[cite: 1].
* [cite_start]Redundant columns like **Alive**, **Class**, and **Who** were dropped to simplify the model[cite: 1].

### Step 3: Feature Engineering
[cite_start]A new feature, **FamilySize**, was created by combining the number of siblings, spouses, parents, and children on board[cite: 1]. [cite_start]This helped the model understand the impact of traveling with family[cite: 1].

### Step 4: Data Visualization
Visual patterns were identified:
* [cite_start]A **Count Plot** showed that females had a significantly higher survival rate[cite: 1].
* [cite_start]A **Bar Plot** confirmed that passengers in 1st Class were more likely to survive than those in 3rd Class[cite: 1].
* [cite_start]A **Correlation Heatmap** was used to see the mathematical relationship between different features[cite: 1].

### Step 5: Machine Learning (Model Building)
[cite_start]The data was split into an **80% Training Set** and a **20% Testing Set**[cite: 1]. [cite_start]A **Logistic Regression** model was chosen for its effectiveness in binary classification (Yes/No) tasks[cite: 1].

## Results & Evaluation
[cite_start]**Model Performance:** The trained model was tested on unseen data to ensure it could generalize its predictions[cite: 1].
* [cite_start]**Final Accuracy:** [Paste your Accuracy Percentage here, e.g., 81.25%] [cite: 1]
* [cite_start]**Confusion Matrix:** The confusion matrix was used to visualize the number of correct and incorrect predictions made by the model[cite: 1].

## Conclusion
[cite_start]This project successfully demonstrates the power of the data science workflow[cite: 1]. [cite_start]Through careful data cleaning and feature engineering, we were able to transform raw historical data into a predictive tool[cite: 1]. [cite_start]The results show that social status (class) and gender were the most significant predictors of survival on the Titanic[cite: 1]. [cite_start]This foundational project provides a strong understanding of how machine learning can be applied to real-world datasets to find hidden insights[cite: 1].
