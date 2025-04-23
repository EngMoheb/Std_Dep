# Student Depression Analysis with Excel 📊💡

**A data-driven project deep dive into the academic, lifestyle, and socioeconomic factors driving depression among students**, leveraging Excel’s features to uncover high-impact stressors and inform targeted interventions.

---

## Table of Contents 📑

1. [About the Project](#about-the-project)  
2. [Introduction & Objectives 🎯](#introduction--objectives-)  
3. [Data Source & Context 🗂️](#data-source--context-️)  
4. [Data Cleaning & Transformation 🔄](#data-cleaning--transformation-)  
5. [Exploratory Data Analysis 🔍](#exploratory-data-analysis-)  
   - [Part 1: Demographic Analysis](#part-1-demographic-analysis)  
   - [Part 2: Single-Feature Analysis](#part-2-single-feature-analysis)  
   - [Part 3: Hotspots Analysis](#part-3-hotspots-analysis)  
6. [Insights from Analysis 💡](#insights-from-analysis-)  
7. [Recommendations & Implementation 🎯](#recommendations--implementation-)  
8. [Tools Used 🛠️](#tools-used-)  
9. [Next Steps ⏭️](#next-steps-)  
10. [Demo GIFs 📽️](#demo-gifs-)  
11. [Contributing 🤝](#contributing-)  
12. [License 📄](#license-)  
13. [Contact 📬](#contact-)

---

## About the Project

Student mental health is a **critical global issue**—this project analyzes a Kaggle survey of **27,901** respondents to **identify** the top predictors of depression and **recommend** data-backed solutions. We have used Excel’s Power Query, PivotTables and pivot charts to process raw data, perform three phases of analysis, and surface actionable insights.

---

## Introduction & Objectives 🎯

**Why this matters:**  
Depression undermines student well-being and academic success. By uncovering the main stressors—academic pressure, financial hardship, suicidal thoughts, and lifestyle factors—we aim to inform strategies that reduce depression rates.

**Objectives:**  
- 🔍 **Identify** leading single and compound predictors of student depression.  
- 💡 **Recommend** targeted, evidence-based interventions for educators, support services, and policymakers.

---

## Data Source & Context 🗂️

- **Dataset:** [Student Depression Dataset on Kaggle](https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset) (27,901 rows × 18 columns).  
- **Workbook Structure:**  
  - **Raw Data**  
  - **Cleaned Data**  
  - **Part 1: Demographics Analysis**  
  - **Part 2: Single-Feature Analysis**  
  - **Part 3: Hotspots Analysis**  
- **Security:** Workbook is marked as final and protected to prevent unintentional structure edits.

---

## Data Cleaning & Transformation 🔄

1. **Deduplication**: Removed duplicate survey entries.  
2. **Parsing & Bucketing**: Converted “Sleep Duration” text to numeric hours and grouped into Short/Normal/Long.  
3. **Ordinal Buckets**: Created Low/Medium/High groups for pressure, stress, and satisfaction scales.  
4. **Boolean Flags**: Mapped depression and suicidal-thought indicators to TRUE/FALSE.  
5. **Enrichment**: Added `Country` and `IsStudent` flags for segmentation.

---

## Exploratory Data Analysis 🔍

### Part 1: Demographic Analysis  
- **Top Cities**: Kalyan (1,570), Srinagar (1,370), Hyderabad (1,338).  
- **Student Status**: 99% of depressed respondents are students.  
- **Gender × Age Bands**:  
  - *Females* (44% of cases): Young 23%, Mid 17%, Senior 4%.  
  - *Males* (56%): Young 28%, Mid 21%, Senior 7%.  

### Part 2: Single-Feature Analysis  
- **High Academic Pressure**: 81.6% depressed  
- **Suicidal Thoughts = TRUE**: 79.1% depressed  
- **High Financial Stress**: 75.6% depressed  
- **Low Study Satisfaction**: 70.7% depressed  
- **Unhealthy Diet**: 70.7% depressed  
- **High Study Hours**: 66.7% depressed  
- **Excellent GPA**: 61.0% depressed  
- **Short Sleep Duration**: 61.3% depressed  
- **Family Illness History = TRUE**: 61.3% depressed  

### Part 3: Hotspots Analysis  
- **High Academic Pressure + Suicidal Thoughts**: 91.9% depressed  
- **High Academic Pressure + High Financial Stress**: 90.7% depressed  
- **Suicidal Thoughts + High Financial Stress**: 89.1% depressed  
- **High Pressure + Low Satisfaction**: 89.0% depressed  
- **Suicidal Thoughts + Low Satisfaction**: 86.8% depressed  
- **High Stress + Low Satisfaction**: 83.0% depressed  
- **Suicidal Thoughts + Family Illness**: 81.0% depressed  
- **Unhealthy Diet + Short Sleep**: 73.0% depressed  
- **High Study Hours + Short Sleep**: 69.0% depressed  

---

## Insights from Analysis 💡

- **Peak Compound Risk**: *High Academic Pressure + Suicidal Thoughts* → **91.9%**.  
- **Top Single Predictors**: Academic Pressure (81.6%), Suicidal Ideation (79.1%), Financial Stress (75.6%).  
- **Protective Extremes**: Low Pressure (19
