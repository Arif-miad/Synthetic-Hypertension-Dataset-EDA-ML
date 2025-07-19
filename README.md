# Hypertension Risk Prediction Dataset & Classification Models

## Overview  
This repository contains a **synthetic yet realistic hypertension dataset** along with a comprehensive Jupyter Notebook demonstrating Exploratory Data Analysis (EDA) and building multiple classification models to predict hypertension risk.

The dataset simulates important clinical and lifestyle factors influencing blood pressure, enabling researchers, students, and healthcare data enthusiasts to explore and model hypertension prediction effectively.

---

## Dataset Description

- **Number of records:** 1,985  
- **Number of columns:** 11  
- **Data Type:** Mixed (Numerical and Categorical)  
- **Target variable:** `Has_Hypertension` (Yes/No)

---

## Dataset Columns & Explanation

| Column Name         | Description                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------|
| **Age**             | Patient's age in years (range: 18 to 85).                                                       |
| **Salt_Intake**     | Average daily salt consumption in grams. High salt intake is a known risk factor for hypertension. |
| **Stress_Score**    | Subjective stress level on a scale from 0 (no stress) to 10 (extreme stress).                   |
| **BP_History**      | Past blood pressure condition, categorized as `Normal`, `Prehypertension`, or `Hypertension`.   |
| **Sleep_Duration**  | Average number of hours slept daily. Short sleep can contribute to high blood pressure.         |
| **BMI**             | Body Mass Index, a measure of body fat based on height and weight.                              |
| **Medication**      | Type of blood pressure medication currently used, if any. Categories include `None`, `Beta Blocker`, `Diuretic`, `ACE Inhibitor`, and `Other`. |
| **Family_History**  | Indicates if any family member has hypertension (`Yes` or `No`).                                |
| **Exercise_Level**  | Patient's physical activity level classified as `Low`, `Moderate`, or `High`.                   |
| **Smoking_Status**  | Indicates if the patient is a `Smoker` or `Non-Smoker`.                                        |
| **Has_Hypertension** | Target column indicating presence (`Yes`) or absence (`No`) of hypertension diagnosis.          |

---

## How to Use This Repository

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/hypertension-risk-prediction.git
    cd hypertension-risk-prediction
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Explore the Dataset:**
   The dataset is located in the `data/` folder as `hypertension_dataset.csv`.

4. **Run the Notebook:**
   Open the notebook `notebooks/Hypertension_EDA_Classification.ipynb` to perform:
   - Data exploration and visualization
   - Preprocessing and feature engineering
   - Training and evaluation of 10 different classification models
   - Model comparison and feature importance analysis

---


