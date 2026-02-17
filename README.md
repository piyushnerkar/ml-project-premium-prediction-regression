# Age-Optimized Predictive Modeling with Segmented Analysis

## 📌 Project Overview
This project focuses on building a highly reliable regression model by identifying and resolving systematic errors within specific demographic segments. Through rigorous error analysis, I reduced prediction errors for the younger demographic from **73% to 2.14%**.

## 🚀 Key Features & Workflow

### 1. Data Prep & Exploratory Data Analysis (EDA)
* **Cleaning & Preprocessing:** Handled missing values, outliers, and categorical encoding using `pandas` and `numpy`.
* **Visualization:** Leveraged `matplotlib` and `seaborn` to identify feature correlations and data distributions before modeling.

### 2. Error Analysis & Diagnostics 🔍
* **Residual Analysis:** Calculated residuals and percentage errors to evaluate baseline model performance.
* **Problem Identification:** Discovered that the model consistently failed for the **age <25 segment**, with extreme prediction errors exceeding 10%.
* **Investigation:** Conducted deep-dive feature analysis to understand why the global model lacked predictive power for younger populations.

### 3. Segmented Modeling Strategy
* **Data Splitting:** Implemented a segment-based approach by splitting the dataset at age 25.
* **Feature Engineering:** Collaborated on adding a **"Genetic Risk"** feature specifically relevant to the younger segment.
* **Impact:** This targeted strategy reduced the error rate from a baseline of **73% down to 2.14%**, significantly enhancing overall model reliability.

## 🛠️ Tech Stack
* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Deployment:** Streamlit 

## 📊 Results & Insights
* **Global Error Reduction:** By moving from a "one-size-fits-all" model to a segmented approach, the model reliability increased across all age groups.
* **Performance Metric:** Achieved a final prediction error threshold of **<3%** for the primary target segment.
