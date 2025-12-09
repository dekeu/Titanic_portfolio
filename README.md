# Titanic_portfolio
This project explores the Titanic dataset to see what factors influenced passenger survival.  
It’s a mix of data cleaning, exploration, and modeling — framed as a **risk analysis case study**.

---

## What I Did
- Cleaned the data (fixed missing ages, fares, and embarkation ports).
- Engineered features like **FamilySize**, **IsAlone**, and **HasCabin**.
- Ran statistical tests:
  - **Chi-square** → Sex, Class, Cabin info strongly linked to survival.
  - **T-test** → Survivors were a bit younger, but not significantly.
  - **Logistic regression odds ratios** → Being male or 3rd class reduced survival odds; having a cabin increased them.
- Built models (Logistic Regression, Random Forest) to predict survival.
- Created a simple **Streamlit app** where you can test passenger profiles and see survival probabilities.

---

## Key Insights
- **Gender and class were the strongest predictors of survival.**
- **Family presence and cabin info mattered too.**
- **Age alone wasn’t a strong factor.*
