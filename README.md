# Student Depression Analysis with Excel 📊💡

**A data-driven project deep dive into the academic, lifestyle, and socity factors driving depression among students**, using Excel's features to uncover high-impact stressors and inform targeted interventions.

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
8. [Tools I Used 🛠️](#tools-i-used-️)
9. [Next Steps ⏭️](#next-steps-️)
10. [Contact 📬](#contact-)


---

## About the Project

Student mental health is a **critical global issue**—this project analyzes a Kaggle survey of **27,901** respondents to **identify** the top predictors of depression and **recommend** data-backed solutions. We have used Excel’s Power Query, PivotTables and pivot charts to process raw data, perform three phases of analysis, and surface actionable insights.

---

## Introduction & Objectives 🎯

**Why this matters:**  
Depression undermines student well-being and academic success. By uncovering the main stressors—academic pressure, financial hardship, suicidal thoughts, and lifestyle factors—we aim to inform strategies that reduce depression rates.

**Objectives:**  
- 🔍 **Identify** leading single and compound predictors of student depression.  
- 💡 **Recommend** targeted, evidence-based interventions for educators & support services.

---

## Data Source & Context 🗂️
![Raw Data](assets/raw-data.png)

- **Dataset:** [Student Depression Dataset on Kaggle](https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset) (27,901 rows × 18 columns).  
- **[STD_DEP_fnl.xlsx]( https://github.com/EngMoheb/Std_Dep/blob/main/STD_DEP_fnl.xlsx) Workbook Structure:**  
  - **Raw Data**  
  - **Cleaned Data**  
  - **Part 1: Demographics Analysis**  
  - **Part 2: Single-Feature Analysis**  
  - **Part 3: Hotspots Analysis**  
- **Security:** Workbook is marked as final and protected to prevent unintentional structure edits.

---

## Data Cleaning & Transformation 🔄
![Cleaned Data](assets/cleaned-data.png)

1. **Deduplication**: Removed duplicate values.  
2. **Parsing & Bucketing**: Converted “Sleep Duration” text to numeric hours and grouped into Short/Normal/Long.  
3. **Ordinal Buckets**: Created Low/Medium/High groups for pressure, stress, and satisfaction scales.  
4. **Boolean Flags**: Mapped depression and suicidal-thought indicators to TRUE/FALSE.  
5. **Enrichment**: Added `Country` and `IsStudent` flags for segmentation.

---

## Exploratory Data Analysis 🔍

### Part 1: Demographic Analysis  
![Demographics](assets/phase1-demographics.png)
- **Indian Cities with Highest Depression Rates**: Kalyan (1,570), Srinagar (1,370), Hyderabad (1,338).  
- **Student Status**: 99% of depressed respondents are students.  
- **Gender × Age Bands**:  
  - *Females* (44%): Young 23%, Mid 17%, Senior 4%.  
  - *Males* (56%): Young 28%, Mid 21%, Senior 7%.  

#### Detailed Observations
- **Regional Clusters**: Urban centers like Kalyan show elevated depression counts.

- **Student Dominance**: Non-students report minimal depression, validating focus on student cohorts.

- **Age Pattern**: Younger students disproportionately affected, pointing to transitional stress in early academic years.

### Part 2: Single-Feature Analysis  
![Single Feature](assets/phase2-single-feature.png)
- **High Academic Pressure**: 81.6% depressed  
- **Suicidal Thoughts = TRUE**: 79.1% depressed  
- **High Financial Stress**: 75.6% depressed  
- **Low Study Satisfaction**: 70.7% depressed  
- **Unhealthy Diet**: 70.7% depressed  
- **High Study Hours**: 66.7% depressed  
- **Excellent GPA**: 61.0% depressed  
- **Short Sleep Duration**: 61.3% depressed  
- **Family Illness History = TRUE**: 61.3% depressed  

### In-Depth Insights
- _**_Academic and emotional stressors (pressure, ideation) are top predictors, overshadowing lifestyle variables._**
- **_Diet and sleep emerge as modifiable behaviors—opportunities for wellness programs._**

### Part 3: Hotspots Analysis  
![Hotspots](assets/phase3-hotspots.png)
- **High Academic Pressure + Suicidal Thoughts**: 91.9% depressed  
- **High Academic Pressure + High Financial Stress**: 90.7% depressed  
- **Suicidal Thoughts + High Financial Stress**: 89.1% depressed  
- **High Pressure + Low Satisfaction**: 89.0% depressed  
- **Suicidal Thoughts + Low Satisfaction**: 86.8% depressed  
- **High financial Stress + Low study Satisfaction**: 83.0% depressed  
- **Suicidal Thoughts + Family Illness**: 81.0% depressed  
- **Unhealthy Diet + Short Sleep**: 73.0% depressed  
- **High Study Hours + Short Sleep**: 69.0% depressed  

## Insights from Analysis 💡

- **Peak Compound Risk**: *High Academic Pressure + Suicidal Thoughts* → **91.9%**.  
- **Top Single Predictors**: Academic Pressure (81.6%), Suicidal Ideation (79.1%), Financial Stress (75.6%).  

---

## Recommendations & Implementation 🎯

1. **Reduce Academic Pressure**  
   - 📚 *Mindfulness & CBT Workshops*: Semester-long programs proven to lower stress by 30–40%.  
   - 👩‍🏫 *Growth-Mindset Training*: Integrate resilience and study-skill modules into curricula.

2. **Address Suicidal Ideation**  
   - 🛡️ *Routine Screening (PHQ-9)*: Flag at-risk students during health-center visits.  
   - 🤝 *Gatekeeper Training*: Equip faculty and peers to recognize warning signs and refer for support.

3. **Alleviate Financial Stress**  
   - 💳 *Financial Literacy Bootcamps*: Budgeting and scholarship navigation,  These bootcamps are effective enough to lower stress levels by approximately 25%.  
   - 🆘 *Emergency Aid Grants*: Rapid-response funding (within 48 hours) for urgent needs.

4. **Improve Well-Being**  
   - 🍎 *Nutrition Counseling*: On-campus dietitian sessions and meal planning.  
   - 😴 *Sleep Hygiene Programs*: Workshops, trackers, and campus sleep spaces.

*Implementation*: Partner with campus counseling, secure grant funding, and track outcomes via follow-up surveys.

---

## Tools I Used 🛠️

- **Excel 365**: Power Query for ETL, PivotTables for analysis and pivot charts for Visualization.   
- **Git & GitHub**: Version control and project hosting.  
- **ChatGPT**: Drafted and refined narrative content and advanced analysis.  
- **DeepSeek AI**: Defining questions and selecting key depression factors.
- **Perplexity**: Rapid research and fact-checking.  
- **Grammarly**: Ensured clear, polished writing.
- **Sider.ai**: Chating with all the AI Models.

---

## Next Steps ⏭️

- **Scale to SQL**: Migrate cleaned data to a relational database for large-scale & to overcome Excel’s row limits and enable advanced querying. .  
- **Advanced BI Tools**: Create interactive dashboards in Power BI or Tableau to visualize real-time depression risk across cohorts..  

---

## Contact 📬

**Lead Analyst**: Eng_Ahmed_Moheb 

[LinkedIn](https://www.linkedin.com/in/ahmed-moheb-09b37135a/)  

---

*Thank you for exploring Student Depression Analysis—let’s collaborate to foster healthier campus communities!*  


