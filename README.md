# Titanic-survival-prediction
Exploratory data analysis and hypothesis testing on the Titanic dataset to analyze survival factors using Python.

<br>

## Objective
To explore and analyze the Titanic dataset to uncover patterns in survival, using statistics, visualizations, and a hypothesis test.

<br>

## 🔍 Step-by-Step Workflow
1. Data Exploration
   - Loaded the dataset and checked the shape and column names.
   - Found missing values in Age, Cabin, and Embarked.
  
<br>

2. Data Cleaning
   - Filled missing Age values with the median.
   - Dropped the Cabin column due to too many missing entries.
   - Filled Embarked missing values with the mode.
   - Converted categorical features like Sex and Embarked to numeric format.

<br>

3. Descriptive Analysis
   - Calculated average age of survivors vs. non-survivors.
   - Found survival percentages by gender and passenger class.

<br>

4. Visualizations
   - Bar plot of survival by gender.
   - Histogram of age distribution for survivors vs. non-survivors.
   - Hypothesis Testing
  
<br>

---

<br>

### Question: Does gender affect survival rate?

<br>

Null Hypothesis (H₀): Gender and survival are independent.

Alternative Hypothesis (H₁): Gender and survival are dependent.

<br>


Test Used: Chi-Square Test
Result:

χ² Statistic: 260.71

p-value: 1.197e-58 (≪ 0.05)

✅ We reject the null hypothesis — gender had a statistically significant impact on survival.

<br>

---

<br>

## 📊 Key Insights

1. Females had a much higher survival rate than males.

2. 1st class passengers had better chances of survival.

3. Younger passengers had higher survival likelihood.

<br>

## 🧠 What I Learned

1. How to handle missing data and encode categorical variables.

2. Basics of statistical analysis & hypothesis testing.

3. How to draw insights from data using visualizations.
