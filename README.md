# Task 2
## Exploratory Data Analysis (EDA)

Here I performs detailed **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand patterns, distributions, correlations, and outliers that influence passenger survival.

---

## Objectives of EDA

- Generate descriptive statistics
- Visualize feature distributions
- Detect outliers and anomalies
- Analyze correlations and feature relationships
- Make feature-level inferences

---

## EDA Tasks Performed

### 1. Summary Statistics

- Used `.describe()`, `.info()`, and `.median()` to explore:
  - Mean, median, standard deviation, min/max
  - Data types and null values

### 2. Visualizations

#### 🔹 Histograms
- Showed distribution of numerical features like `Age`, `Fare`, `SibSp`, `Parch`

![image](https://github.com/user-attachments/assets/de53c958-42d4-4b87-be5e-a38ad6bf014d)


#### 🔹 Boxplots
- Detected outliers in numerical features
  
![image](https://github.com/user-attachments/assets/df01c9c0-7f3d-41b6-9734-06056e5f57a4)
![image](https://github.com/user-attachments/assets/32e0805b-ec5d-4f8d-b063-b5b8d458a9c3)
![image](https://github.com/user-attachments/assets/bc3b6887-f2d4-44e5-8dba-92de4b921da8)
![image](https://github.com/user-attachments/assets/3f816aae-59f7-4fa7-9921-84895ed8a40c)


#### 🔹 Correlation Heatmap
- Identified relationships between numeric features

![image](https://github.com/user-attachments/assets/68cc8651-b951-4609-8e75-98763b4d1b50)

#### 🔹 Pairplot
- Visualized pairwise relationships with `Survived` as hue

![image](https://github.com/user-attachments/assets/0bae509c-0bd3-45e3-9750-1bcb62aa930f)

#### 🔹 Count Plots
- Analyzed survival count by `Sex`, `Age`, `Fare`  

![image](https://github.com/user-attachments/assets/03edad2f-b87e-4b8f-b473-2f225bce1d90)
![image](https://github.com/user-attachments/assets/fa71cd0e-a84b-4da3-8b74-6c66ecb19c4c)
![image](https://github.com/user-attachments/assets/a38e36bc-fab0-4928-a6da-c3f9b7d718fe)


---

## Key Insights

- **Sex**: Females had higher survival rates
- **Fare**: Higher-paying passengers were more likely to survive
- **Age**: Young children had slightly better survival rates
- **Pclass**: 1st class passengers had a higher chance of survival
- Some features like `SibSp` and `Parch` showed complex effects depending on family size


---

## Files
- `task2.ipynb`: Full notebook with step-by-step Exploratory Data Analysis (EDA)

- `Titanic-Dataset.csv`: Original Titanic dataset from Kaggle


