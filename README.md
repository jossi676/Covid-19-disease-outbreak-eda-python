# Covid-19-disease-outbreak-eda-python
Exploratory data analysis of global COVID-19 outbreak data using Python to analyze trends, peak periods, growth phases, and outbreak severity.

# COVID-19 Disease Outbreak Trend Analysis using Python (EDA)

## 📌 Problem Statement
Understanding how a disease outbreak evolves over time is critical for public health planning and resource allocation.  
This project applies Exploratory Data Analysis (EDA) techniques to global COVID-19 outbreak data to analyze spread trends, identify high-impact regions, detect peak periods, and assess outbreak severity.

---

## 📊 Dataset
**Source:** Kaggle – COVID-19 Clean Complete Dataset  
**Granularity:** Daily, Country-level  

**Key Columns Used:**
- Date
- Country/Region
- Confirmed cases
- Deaths
- Recovered cases

The dataset captures the temporal progression of COVID-19 across countries and is suitable for time-series outbreak analysis.

---

## ❓ Key EDA Questions Addressed
1. How did the global COVID-19 outbreak evolve over time?
2. Which countries were most affected by confirmed cases?
3. How did outbreak growth rates change across different phases?
4.When did peak outbreak periods occur globally?
5. How severe was the outbreak in terms of deaths relative to confirmed cases?

---

## 🔍 Analysis Approach
- Cleaned and prepared time-series data using **Pandas**
- Aggregated global and country-level outbreak metrics
- Identified peak outbreak periods using time-series analysis
- Analyzed growth rates and moving averages using **NumPy**
- Assessed outbreak severity through death-to-confirmed case ratios
- Visualized key trends and comparisons using **Matplotlib**



## 📈 Key Visualizations & Insights

### 1️⃣ Global Outbreak Trend Over Time
![Global Trend](global_trend.jpg)

**Insight:**  
The global outbreak exhibited a rapid acceleration phase followed by stabilization periods, indicating distinct outbreak waves.

---

### 2️⃣ Top 10 Most Affected Countries by Confirmed Cases
![Top Countries](top_countries_cases.jpg)

**Insight:**  
A small number of countries accounted for a disproportionately large share of global confirmed cases, highlighting regional concentration of the outbreak.

---

### 3️⃣ Growth Rate & Moving Average Analysis
![Growth Rate Trend](visuals/growth_rate_trend.jpg)

**Insight:**  
Outbreak growth rates declined significantly after peak phases, suggesting the impact of public health interventions and control measures.

**Peak Outbreak Periods:**  
  The analysis identified specific time windows during which global confirmed cases reached their maximum, indicating periods of highest strain on healthcare systems.

**Outbreak Severity:**  
  Death-to-confirmed case ratio analysis revealed variation in outbreak severity across countries, reflecting differences in healthcare capacity, demographics, and response strategies.

(These analyses are documented in detail within the Jupyter notebook.)



## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📁 Repository Structure
covid-19-disease-outbreak-eda-python/
│
├── data/
│ └── covid_19_Data.csv
│
├── notebooks/
│ └── covid19_outbreak_eda.ipynb
│
├── visuals/
│ ├── global_trend.jpg
│ ├── top_countries_cases.jpg
│ └── growth_rate_trend.jpg
│
├── README.md


## 📌 Conclusion
This project demonstrates how Python-based exploratory data analysis can be applied to real-world healthcare data to understand disease outbreak dynamics, identify critical trends, and support data-driven public health decision-making.
