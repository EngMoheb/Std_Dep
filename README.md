# Students_Depression_Insights

 Student Well‑Being Insights 📊

Welcome to Student Well‑Being Insights, a data‑driven project that explores the key factors contributing to depression among students. This repository contains a secured Excel workbook (STD_DEP_fnl.xlsx) detailing raw, cleaned, and analyzed data, as well as short GIF demos illustrating each analysis phase.

Table of Contents 📑

About the Project

Introduction & Objectives

Data Source & Context

Data Cleaning & Transformation

Exploratory Data Analysis

Insights from Analysis

Tools Used

Recommendations

Next Steps

Demo GIFs

Contributing

License

Contact

About the Project

Student Well‑Being Insights analyzes a Kaggle dataset of 27,901 student responses to identify the most significant predictors of depression. We processed raw survey data in Excel, performed step‑by‑step demographic and statistical analyses, and uncovered high‑impact stressors to inform targeted interventions.

Introduction & Objectives 🎯

Introduction

Student mental health is a growing global concern. This project leverages a comprehensive survey dataset to pinpoint the academic, lifestyle, and socioeconomic factors most strongly linked to depression among students.

Objectives

🔍 Identify the leading single and compound predictors of student depression.

💡 Recommend actionable, evidence‑based strategies for educators, institutions, and stakeholders.

Data Source & Context 🗂️

Raw Dataset: Kaggle export with 18 fields covering demographics, stressors, behaviors, and depression indicators.

Workbook Structure: Includes sheets for Raw Data, Cleaned Data, Demographics Analysis, Single‑Feature Analysis, and Hotspots Analysis.

Security: The Excel file is protected to prevent structural edits, while remaining viewable.

Data Cleaning & Transformation 🔄

Deduplication: Removed duplicate records in the Raw Data sheet.

Text Parsing & Bucketing: Converted text fields (e.g., "Sleep Duration") to numeric ranges and grouped into categories.

Bucket Creation: Defined Low/Medium/High thresholds for Academic Pressure, Financial Stress, and other Likert‑scale variables.

Boolean Flags: Mapped depression (0/1) and suicidal thoughts (Yes/No) to TRUE/FALSE in Cleaned Data.

Enrichment: Added Country and IsStudent flags for geographic and cohort segmentation.

Exploratory Data Analysis 🔍

Part 1: Demographics Analysis

Top Cities by Depression Count: Kalyan (1,570), Srinagar (1,370), Hyderabad (1,338).

Students vs. Others: 99% of depressed respondents are students.

Gender × Age Bands: Females (44%): Young 23%, Mid 17%, Senior 4%; Males (56%): Young 28%, Mid 21%, Senior 7%.

Part 2: Single‑Feature Analysis

High Academic Pressure: 81.6% depressed

Suicidal Thoughts = TRUE: 79.1% depressed

High Financial Stress: 75.6% depressed

Low Study Satisfaction: 70.7% depressed

Unhealthy Diet: 70.7% depressed

Short Sleep Duration: 61.3% depressed

Part 3: Hotspots Analysis

High Academic Pressure + Suicidal Thoughts: 91.9% depressed

High Academic Pressure + High Financial Stress: 90.7% depressed

Suicidal Thoughts + High Financial Stress: 89.1% depressed

Suicidal Thoughts + Low Study Satisfaction: 86.8% depressed

Insights from Analysis 💡

Peak Compound Risk: High Academic Pressure + Suicidal Thoughts (91.9%).

Top Single Predictors: Academic Pressure (81.6%), Suicidal Thoughts (79.1%), Financial Stress (75.6%).

Protective Extremes: Low Academic Pressure (19.5%) and Healthy Diet (45.4%).

Tools Used 🛠️

Excel 365 (Power Query & PivotTables)

FFmpeg (GIF conversion)

Git & GitHub (version control)

Markdown (documentation)

Recommendations 🎯

Mitigate Academic Pressure via Mindfulness‑Based Stress Reduction and growth‑mindset workshops.

Screen & Support Suicidal Ideation with routine ideation screening and gatekeeper training.

Alleviate Financial Stress through financial literacy workshops and rapid‑response emergency aid.

Next Steps ⏭️

Transition analysis to an SQL environment to handle larger datasets beyond Excel’s row limits.

Demo GIFs 📽️

These inline demos illustrate each analysis phase:

Part 1: Raw Data



Part 2: Cleaned Data



Part 3: Demographics



Part 4: Single‑Feature



Part 5: Hotspots



Contributing 🤝

Contributions are welcome! Please open issues or submit pull requests for feedback and improvements.

License 📄

This project is licensed under the MIT License. See the LICENSE file for details.

Contact 📬

Project Lead — you@example.com

Connect with me on LinkedIn: https://www.linkedin.com/in/yourprofile

