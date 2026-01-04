# Task-02-Prodigy-InfoTech

# Titanic Survival Analysis & Data Visualization Project

A data analysis and visualization project exploring passenger survival patterns on the Titanic using historical data.

## Project Overview

This project demonstrates **data cleaning, exploratory data analysis (EDA), and data visualization** techniques using Python on the Titanic dataset.
The goal is to identify key demographic and socio-economic factors that influenced passenger survival during the Titanic disaster.

The analysis focuses on survival trends based on **gender, age, passenger class, fare, and family size**, using visual and statistical methods.

---

## Features

* **Survival Distribution Analysis**: Visualization of overall survival vs non-survival
* **Gender-Based Survival Analysis**: Comparison of survival rates between males and females
* **Passenger Class Analysis**: Survival trends across 1st, 2nd, and 3rd class passengers
* **Age & Fare Distribution Analysis**: Understanding survival patterns across age groups and ticket fares
* **Family Size Impact**: Analysis of how traveling alone or with family affected survival
* **Data Cleaning & Preprocessing**: Handling missing values and irrelevant features
* **Correlation Analysis**: Identifying relationships between numerical features and survival

---

## Technologies Used

* **Python 3.x**
* **Pandas**: Data manipulation and analysis
* **NumPy**: Numerical computations
* **Matplotlib**: Data visualization
* **Seaborn**: Statistical and comparative visualizations
* **Jupyter Notebook**

---

## Dataset

**Source**: Kaggle – Titanic: Machine Learning from Disaster

### Columns Description:

* `PassengerId`: Unique passenger identifier
* `Survived`: Survival status (0 = No, 1 = Yes)
* `Pclass`: Passenger class (1st, 2nd, 3rd)
* `Name`: Passenger name
* `Sex`: Gender of the passenger
* `Age`: Age of the passenger
* `SibSp`: Number of siblings/spouses aboard
* `Parch`: Number of parents/children aboard
* `Ticket`: Ticket number
* `Fare`: Passenger fare
* `Cabin`: Cabin number (mostly missing)
* `Embarked`: Port of embarkation (C, Q, S)

---

## 📈 Visualizations

### 1. Survival Distribution

* **Type**: Count Plot
* **Purpose**: Shows proportion of survived vs non-survived passengers
* **Insights**: Highlights the overall low survival rate

### 2. Gender-Based Survival Analysis

* **Type**: Count Plot / Bar Chart
* **Purpose**: Compare survival rates between males and females
* **Insights**: Females had a significantly higher survival probability

### 3. Passenger Class vs Survival

* **Type**: Bar Chart
* **Purpose**: Analyze survival based on socio-economic class
* **Insights**: First-class passengers were more likely to survive

### 4. Age Distribution & Survival

* **Type**: Histogram
* **Purpose**: Understand survival across age groups
* **Insights**: Children had higher survival rates

### 5. Fare Distribution Analysis

* **Type**: Histogram
* **Purpose**: Examine how ticket fare impacted survival
* **Insights**: Higher fare correlated with higher survival chances

### 6. Correlation Heatmap

* **Type**: Heatmap
* **Purpose**: Identify relationships between numerical variables
* **Insights**: Fare and passenger class showed correlation with survival

---

## Code Structure

```
Task_02.ipynb
├── Import Libraries
├── Load Dataset
├── Initial Data Inspection
├── Data Cleaning
│   ├── Handle missing values
│   ├── Drop irrelevant columns
│   └── Encode categorical variables
├── Exploratory Data Analysis (EDA)
│   ├── Survival Analysis
│   ├── Gender & Class Analysis
│   ├── Age & Fare Distribution
│   └── Family Size Impact
├── Correlation Analysis
└── Insights & Conclusion
```

---

## Key Insights

* Females had a **much higher survival rate** than males
* Passengers in **1st class** were more likely to survive
* **Children** had better survival chances compared to adults
* Passengers traveling with **small families** survived more than solo travelers
* Higher ticket **fare** showed a positive correlation with survival

---

## Sample Output

The project generates:

1. **Count Plots** showing survival distribution across categories
2. **Histograms** for age and fare distribution
3. **Bar Charts** comparing survival by class and gender
4. **Heatmap** visualizing correlations among numerical features

---

## Conclusion (Business / Product Perspective)

This project demonstrates how historical data can be used to identify **key drivers of outcomes** through structured analysis.
By segmenting passengers based on demographic and socio-economic attributes, the analysis highlights patterns that explain survival probability.

From a business and product analytics perspective, this mirrors real-world decision-making where data is used to:

* Identify high-impact user segments
* Validate assumptions with evidence
* Translate raw data into actionable insights

The project showcases strong fundamentals in **data cleaning, EDA, and insight communication**, making it highly relevant for **Data Analyst, Product Analyst, and Product Management roles**.

---

## Contributing

Contributions are welcome! Feel free to submit a Pull Request for improvements or additional analyses.

---

## 📧 Contact

**Aditya Gaur**

* Email: [work.adityagaur@gmail.com](mailto:work.adityagaur@gmail.com)
* LinkedIn: [linkedin.com/in/adityamnnit03](https://linkedin.com/in/adityamnnit03)

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Acknowledgments

* Dataset provided by Kaggle
* Created as part of data analysis practice and internship preparation
* Inspired by real-world exploratory data analysis workflows

---

⭐ **Star this repository if you found it helpful!**

 
