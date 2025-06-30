# ✈️ Aviation Accident Analysis

## 📌 Overview

This project analyzes aviation accident data to identify patterns, uncover safety risks, and generate actionable recommendations for aviation stakeholders. 
Using Python (Google Colab) and Tableau, I cleaned, explored, and visualized aviation incident data to support real-world decision-making.

---

## 🧠 Business Understanding

**Stakeholders**:
- Aviation safety managers and policy teams
- Aircraft manufacturers and insurers

**Key Business Questions**:
- What are the most common causes and conditions for aviation accidents?
- Do weather, aircraft type, or number of engines correlate with injury severity?
- Which areas or seasons have the highest safety risks?
- How can data insights guide safety improvements?

---

## Data Understanding and Analysis

**Data Source**:
- [Aviation Accident Data - NTSB](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)  
- File used: `AviationData.csv` (cleaned and filtered in Colab)

**Data Description**:
- 80,000+ rows across multiple years
- Key features: `event.date`, `weather.condition`, `aircraft.damage`, `total.injuries`, `aircraft.category`, `location`, `number.of.engines`

### Data Cleaning & Feature Engineering:
- Removed outliers from injury totals and number of engines
- Created new variables like Total injuries, I split date to month and weekly encoding
- Handled missing values with statistical imputation and classification-based techniques

---

## Visualizations

The following charts were used to support findings. Full interactive dashboard available on Tableau.


🔗 [Interactive Tableau Dashboard](https://public.tableau.com/views/Avifinal/Dashboard1)

---

## Conclusion

### Key Findings:

1. **Over 40% of fatal crashes occurred in clear weather** — indicating that human error or technical failure, not visibility, is often the root cause.
2. **Smaller aircraft (1–2 engines)** experienced higher injury rates — pointing to structural vulnerabilities or less advanced safety systems.
3. **Accidents spike during summer months**, especially June–August — highlighting seasonal travel and maintenance stress.

### 🔁 Business Impact:

- These findings support scheduling **pre-summer inspections**, enhancing **pilot retraining**, and reviewing **aircraft type-based risk**.
- The dataset also helps prioritize **high-risk regions** for targeted safety campaigns.

---

## THE END

