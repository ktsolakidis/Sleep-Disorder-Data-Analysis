# Sleep Disorder Data Analysis

This repository contains a comprehensive analysis of the **Sleep Health and Lifestyle Dataset**. The goal is to uncover relationships between variables that influence sleep disorders.
Let's make a story out of our data!

---

### 1. `exploratory_data_analysis.ipynb`
In this file, we analyze the data from the `.csv` file and try to find correlations between variables to build a story around the dataset. By exploring relationships between variables such as **Sleep Duration**, **Quality of Sleep**, **Stress Level**, and **Daily Steps**, we aim to identify patterns and gain insights into the factors influencing sleep disorders.

#### Key Observations:
- **Sleep Duration and Quality of Sleep**: A positive correlation where longer sleep durations are linked to better sleep quality, especially among individuals with no sleep disorders.
- **Physical Activity Level and Daily Steps**: An intuitive relationship where increased physical activity corresponds to higher daily step counts.
- **Stress Level and Quality of Sleep**: Higher stress levels reduce both sleep quality and sleep duration, emphasizing the importance of stress management.
- **BMI and Lifestyle Indicators**: Overweight and obese individuals exhibit higher stress levels and shorter sleep durations.

These observations serve as a foundation for selecting important features to analyze further in the machine learning models.

---

### 2. `ada_model.ipynb`
In this file, we fit the data to an **Adaboost model** and analyze the feature importances to understand the model's decision-making process. By plotting feature importances, we compare the model's reliance on specific features to the relationships observed during exploratory data analysis.

#### Observations:
- The model identifies **Stress Level** and **Daily Steps** as the two most important features for predicting sleep disorders.
- These findings align with the EDA insights:
  - **Stress Level** is strongly linked to sleep quality and duration.
  - **Daily Steps** reflect an active lifestyle, which is critical for maintaining healthy sleep patterns.

---

### 3. `Sleep_health_and_lifestyle_dataset.csv`
This is the dataset used for the analysis and modeling. It contains various lifestyle and health metrics, including:
- Sleep Duration
- Quality of Sleep
- Stress Level
- Physical Activity Level
- Daily Steps
- BMI
- Sleep Disorder Types

This dataset is the foundation of the project.

---
