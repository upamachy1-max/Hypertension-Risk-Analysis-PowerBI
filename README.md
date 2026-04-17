# 📊 Hypertension Clinical Risk Factor Analysis
> **An end-to-end Power BI project analyzing the physiological and lifestyle drivers of hypertension in a population of ~2,000 patients.**

## 🔍 Project Overview
This project moves beyond descriptive statistics to identify the **predictive drivers** of hypertension. By combining clinical data with statistical modeling, I developed an interactive diagnostic dashboard to help healthcare providers identify high-risk patient segments and modifiable lifestyle risks.

## 🧠 Statistical Methodology & Tools
*   **Logistic Regression Modeling:** Utilized the Power BI 'Key Influencers' engine to run a regression-based model, identifying **Family History (1.74x likelihood)** and **Stress Scores (>7)** as the primary independent predictors of hypertension.
*   **Interaction Analysis:** Developed a Heat Map Matrix to analyze the interaction between **Age** and **Smoking Status**, revealing a cumulative risk of **88.7%** in the 60+ smoking cohort.
*   **Correlation Analysis:** Used Scatter Plots with Trend Lines to confirm that **BMI** and **Stress Levels** act as independent drivers with low multi-collinearity ($r \approx 0$).
*   **Data Transformation:** Performed data cleaning and standardized clinical age cohorts using **Power Query**.
*   **DAX:** Developed custom measures for **Group-Specific Prevalence Rates**.

## 📈 Key Insights
*   **The 100% Risk Segment:** Identified a critical cluster of patients (Age >50, Smoker, Positive Family History) with a **100.0% prevalence rate**.
*   **Modifiable Factors:** Excluding genetic predisposition revealed **Sleep Duration** and **Sodium Intake** as the leading lifestyle-only influencers.
*   **Age Trend:** Visualized a clear "staircase" trend where prevalence jumps significantly after the age of 50.

## 🛠️ Files in this Repository
*   **`Hypertension Diagnostic Overview.pbix`**: The full Power BI file (includes the data model, DAX measures, and interactive visuals).
*   **`/Data/hypertension_dataset.csv`**: The raw Kaggle clinical dataset used for the analysis.

---
**Note:** *This project was developed for a professional portfolio to demonstrate clinical data modeling and statistical storytelling. Data used is a public dataset from Kaggle.*
