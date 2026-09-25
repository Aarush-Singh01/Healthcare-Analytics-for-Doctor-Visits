# Healthcare Analytics for Doctor Visits

## 📊 Project Overview

**Healthcare Analytics for Doctor Visits** is a Data Analytics project that explores patterns in doctor visits using demographic, health, socioeconomic, healthcare-access, and chronic-condition-related variables.

The project applies data cleaning, descriptive statistics, exploratory data analysis, visualization, correlation analysis, multivariate analysis, outlier analysis, and statistical hypothesis testing to transform healthcare data into meaningful and interpretable insights.

---

## 🎯 Problem Statement

Healthcare utilization varies across individuals depending on their demographic characteristics, health conditions, socioeconomic factors, and healthcare access.

This project analyzes healthcare data to identify patterns and associations related to the frequency of doctor visits and understand how different characteristics relate to healthcare utilization.

---

## 🎯 Project Objectives

- Analyze the distribution of doctor visits.
- Understand demographic patterns in healthcare utilization.
- Examine relationships between illness, health, reduced activity, and doctor visits.
- Analyze associations between socioeconomic characteristics and doctor visits.
- Investigate doctor visits in relation to chronic-condition indicators.
- Perform statistical analysis to identify significant group differences.
- Present analytical findings through meaningful visualizations.
- Translate data patterns into healthcare-related insights.

---

## ❓ Research Questions

1. How are doctor visits distributed across the dataset?
2. How do doctor visits differ across gender groups?
3. How are illness levels associated with doctor visits?
4. What relationship exists between reduced activity and doctor visits?
5. How are health-related variables associated with healthcare utilization?
6. Do chronic-condition indicators correspond to differences in doctor visits?
7. What relationship exists between income and doctor visits?
8. Are selected differences between groups statistically significant?

---

## 📁 Dataset

The dataset contains **5,190 observations and 13 original variables** related to doctor visits and individual characteristics.

### Main Variables

| Variable | Description |
|---|---|
| `visits` | Number of recorded doctor visits |
| `gender` | Gender category |
| `age` | Encoded/scaled age variable |
| `income` | Encoded/scaled income variable |
| `illness` | Illness-related measure |
| `reduced` | Reduced-activity measure |
| `health` | Health-related measure |
| `private` | Private healthcare/insurance indicator |
| `freepoor` | Free/reduced healthcare indicator |
| `freerepat` | Healthcare/repatriation-related indicator |
| `nchronic` | Chronic-condition indicator |
| `lchronic` | Long-term chronic-condition indicator |
| `Unnamed: 0` | Original index/identifier column |

> **Note:** Some variables are represented using encoded or scaled values. Their exact interpretation depends on the original dataset documentation.

---

## 🔬 Methodology

The project follows a structured Data Analytics workflow:

```text
Raw Dataset
     ↓
Data Cleaning & Preprocessing
     ↓
Descriptive Statistics
     ↓
Univariate Analysis
     ↓
Bivariate Analysis
     ↓
Feature Engineering
     ↓
Multivariate Analysis
     ↓
Correlation Analysis
     ↓
Outlier Analysis
     ↓
Hypothesis Testing
     ↓
Key Findings & Healthcare Insights
     ↓
Conclusion
