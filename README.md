 # Healthcare‑Stroke‑Analysis‑Using‑PySpark 🚑

## 🧾 Project Overview  
The Healthcare‑Stroke‑Analysis‑Using‑PySpark project explores risk factors and patterns related to stroke occurrence using a real‑world healthcare dataset and leverages Apache Spark (via PySpark) for scalable data processing. The aim is to clean, preprocess, and analyze patient records — applying statistical analysis and classification techniques to uncover insights that could inform healthcare risk assessments or preventive strategies.

## ✅ Why This Project Matters  
- Stroke remains a major global health concern, and data‑driven analysis can help identify high‑risk segments and contributing factors.  
- Demonstrates the use of big data tooling (PySpark) for healthcare analytics — a critical skill in healthcare data roles.  
- Combines data cleaning, validation, exploratory analysis, and predictive modeling — showcasing end-to-end data‑analytics workflow.

## 📂 Dataset & Features  
The dataset includes a variety of patient attributes such as:  
- Demographics: Age, Sex  
- Health indicators: Hypertension, Diabetes, Heart disease, Previous conditions  
- Lifestyle / Risk factors: Smoking status, Serum measures, Medical history  
- Outcome: Stroke occurrence / Death event  

> 📝 *Note:* For full details, refer to dataset column descriptions in `data_analysis.ipynb`.  

## 🛠️ Tech Stack & Tools  
- **PySpark** — for scalable data processing and transformation  
- **Python (Pandas, NumPy)** — for preprocessing and supplementary analysis  
- **Jupyter Notebooks** — for iterative exploratory data analysis (EDA) & modeling  
- **SQL (via Spark SQL)** — for structured data querying and manipulation  
 
## 🔄 Workflow & Pipeline  

| Stage | Description |
|-------|-------------|
| **Data Loading** | Import raw data into Spark DataFrame environment |
| **Data Cleaning & Validation** | Handle missing values, outliers; validate consistency and completeness |
| **Exploratory Data Analysis (EDA)** | Statistical summaries, distribution plots, correlation checks |
| **Feature Engineering** | Encode categorical variables, derive new features if needed |
| **Modeling / Analysis** | Build classification or statistical models to predict stroke risk or analyze associations |
| **Evaluation & Insights** | Assess model performance / analyze results; highlight key risk factors or trends |

## 📈 Key Findings (Summary)  
- Identified significant correlations between age, comorbidities (e.g. hypertension / diabetes), lifestyle factors and stroke risk.  
- Demonstrated ability to process and analyze **large healthcare datasets** efficiently with PySpark, ensuring data quality and scalability.  
- Built a reproducible & documented workflow — from raw data ingestion to cleaned dataset and analysis notebooks, ready for further extension or adaptation.

## 🧑‍💻 How to Run / Reproduce  
1. Clone the repository  
   ```bash
   git clone https://github.com/rishitas18/Healthcare‑Stroke‑Analysis‑Using‑PySpark.git
