# Ensemble Methods for UHC Prediction

**Data Analyst Portfolio Project**  
Prediksjon av Universal Health Coverage (UHC) Service Coverage Index ved hjelp av ensemble-metoder i Python.

---

## 📁 Filstruktur

```text
Jupiter_ensemble/
├── data/                   
│   └── UHC.csv             # Rådata fra WHO
├── notebooks/              
│   └── 01_EDA_UHC.ipynb    # EDA + introduksjon til ensemble-metoder
├── src/                    
│   └── data_utils.py       # Hjelpefunksjoner for lasting og pre-prosessering (valgfritt)
├── reports/                
│   └── figures/            # Eksporterte plots og figurer
├── requirements.txt        # Python-pakker og versjoner
└── README.md               # Denne filen
```

---

## 🔍 Prosjektbeskrivelse

I dette prosjektet:

1. **EDA**  
   - Sjekker datatyper, manglende verdier og fordeling per land/år  
   - Filtrerer til siste års UHC-verdier  

2. **Baseline-modell**  
   - Linear Regression som referanse  

3. **Bagging**  
   - Random Forest Regressor  

4. **Boosting**  
   - XGBoost Regressor  

5. **Evaluering**  
   - Metrisering med Mean Squared Error (MSE) og R² Score  
   - Predicted vs. Actual-plot  

6. **Forklarbarhet (valgfritt)**  
   - SHAP-analyse for å identifisere viktige drivere  

Målet er å demonstrere praktisk bruk av ensemble-teknikker på et samfunnsrelevant datasett – uten å gå for dypt inn i avansert modell-engineering.

---

## ⚙️ Komme i gang

1. **Opprett virtuelt miljø**  
   ```bash
   python3 -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

2. **Installer avhengigheter**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Kjør EDA-notebook**  
   Åpne `notebooks/01_EDA_UHC.ipynb` i VSCode eller Jupyter Lab og kjør cellene i rekkefølge.

---

## 📈 Hovedfunn

- Oversikt over data og manglende verdier  
- Visualisering av UHC-indeks-fordeling per land  
- Modellresultater:
  - Linear Regression: MSE = …, R² = …  
  - Random Forest: MSE = …, R² = …  
  - XGBoost: MSE = …, R² = …  

*Se notebook-seksjonen “Konklusjon og Neste Steg” for detaljert oppsummering.*

---

## 🤝 Bidra eller bruk

Dette er et portfolio-prosjekt for en data analyst.  
Koden kan gjenbrukes som mal for egne analyser og ensemble-eksperimenter.

---

© 2025 • MIT License  
