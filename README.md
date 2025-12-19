# Taxi Company Analysis — Impact of Weather on Trip Duration
Estudo de aplicação de uma nova companhia de Taxi

## 1) Objective
Analyze taxi trip data to understand operational patterns and test whether **weather conditions affect the average trip duration** between **Loop** and **O’Hare International Airport** on Saturdays.

The main goal is to validate a business hypothesis using **statistical analysis** and support conclusions with data.

---

## 2) Dataset
The analysis is based on two datasets:
- **Taxi trips per company (Nov 15–16, 2017):** number of trips by taxi company.
- **Drop-off locations (November 2017):** average number of trips by destination neighborhood.

---

## 3) Analysis Overview
The project includes:
- Data loading and inspection using **Pandas**
- Exploratory analysis of taxi companies and drop-off locations
- Hypothesis formulation and statistical testing
- Visualization to support analytical conclusions

---

## 4) Hypothesis Testing

### Hypothesis
**Does the average trip duration from Loop to O’Hare change on rainy Saturdays?**

- **Null Hypothesis (H₀):**  
  There is no difference in the average trip duration between rainy Saturdays and non-rainy Saturdays.

- **Alternative Hypothesis (H₁):**  
  There is a difference in the average trip duration between rainy Saturdays and non-rainy Saturdays.

### Significance Level
- **α = 0.05** (5%)

### Statistical Test
- **Student’s t-test for independent samples**
- Comparison between two groups:
  - Trips with **Good** weather
  - Trips with **Bad** (rainy) weather

### Result
The **p-value obtained was lower than 0.05**, leading to the rejection of the null hypothesis.

✔️ **Conclusion:**  
There is statistical evidence that **weather conditions significantly impact the average duration of taxi trips** from Loop to O’Hare on Saturdays.

---

## 5) Visualization
A **boxplot** was used to compare trip duration distributions under different weather conditions.

The visualization shows noticeable differences between the **Good** and **Bad** weather groups, reinforcing the statistical findings and highlighting variability in trip duration during rainy conditions.

---

## 6) Tools Used
- **Python**
- **Pandas**
- **Statistical Analysis (t-test)**
- **Data Visualization (boxplot)**

---

## 7) Key Learnings
- Data loading, cleaning, and exploratory analysis using Pandas
- Formulation and validation of hypotheses using statistical tests
- Application of the **Student’s t-test** to real-world data
- Interpretation of p-values and statistical significance
- Use of visualizations to support analytical conclusions

---

## 8) Possible Improvements
- Include additional weather variables (intensity of rain, temperature, wind)
- Extend the analysis to other routes and days of the week
- Build an interactive dashboard to monitor trip duration trends
- Add confidence intervals to complement hypothesis testing
