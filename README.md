# UHC Ensemble – Healthcare Data Analysis

## Project Overview
This project explores and analyzes a **United Healthcare dataset** using **Python** to extract insights, identify trends, and prepare data for further modeling.  
The analysis includes **data cleaning**, **exploratory data analysis (EDA)**, and **visualization** to support data-driven decision-making in healthcare analytics.

---

## Tools & Technologies
- **Python 3**
- **Pandas** – data manipulation
- **NumPy** – numerical computations
- **Matplotlib & Seaborn** – data visualization
- **Jupyter Notebook** – interactive development

---

## Project Structure
```
uhc-ensemble/
│
├── README.md                <- Project documentation (this file)
├── notebooks/
│   └── 01_EDA_UHC.ipynb     <- Main EDA notebook
├── data/
│   └── UHC.csv              <- Dataset (if tracked)
├── .gitignore               <- Ignored files/folders
└── requirements.txt         <- Python dependencies
```

---

## Key Steps in the Analysis
1. **Data Loading** – Importing CSV dataset into Pandas DataFrame.
2. **Data Cleaning** – Handling missing values, renaming columns, correcting data types.
3. **Exploratory Data Analysis (EDA)** –  
   - Summary statistics  
   - Univariate & bivariate visualizations  
   - Distribution analysis
4. **Insights Generation** – Identifying trends & correlations.

---

## How to Run Locally
1. **Clone the repository**  
   ```bash
   git clone https://github.com/LordBalouch/uhc-ensemble.git
   cd uhc-ensemble
   ```
2. **(Optional) Create and activate a virtual environment**  
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Mac/Linux
   .venv\Scripts\activate     # Windows
   ```
3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
4. **Open the notebook**  
   ```bash
   jupyter notebook notebooks/01_EDA_UHC.ipynb
   ```

---

## Future Work
- Apply feature engineering and preprocessing for ML models.
- Build predictive models for healthcare cost estimation.
- Add interactive dashboards (Power BI / Tableau).

---

## Contact
**Babak Balouch**  
[LinkedIn](https://www.linkedin.com/in/your-link)  
lord.balouch@gmail.com
