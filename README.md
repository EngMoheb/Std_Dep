# Students_Depression_Analysis_with_Excel 📊

Welcome to our project, Student mental health is a growing global concern. This project leverages a comprehensive survey dataset to pinpoint the academic, lifestyle, and socioeconomic factors most strongly linked to depression among students. so we have made a data‑driven project using excel that explores the key factors contributing to depression among students.   We processed  the raw  data in Excel, performed step‑by‑step demographell‑Being Insights analyzeic and statistical analyses, and uncovered high‑impact stressors to inform targeted interventions.This repository contains an Excel workbook (STD_DEP_fnl.xlsx)     Includes sheets for Raw Data, Cleaned Data, Demographics Analysis, Single‑Feature Analysis, and Hotspots Analysis.  as well as short GIF demos illustrating each analysis phase. 

# # Table of Contents 📑
Data Source & Context
 
 Objectives
 
Data Cleaning & Transformation

Exploratory Data Analysis

Insights from Analysis

Recommendations

Tools Used

Next Steps

Contributing

License

Contact

 

 

  

Data Source & Context 🗂️

A Kaggle dataset  " dataset link https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset" consist  of 27,901 row & 18 Column  covering demographics, stressors, behaviors, and depression indicators. & it is  compiles a wide range of information and providing the factors that contribute to student mental health challenges and it is designed  for data science, and education,   to identify the most significant predictors of depression. 


 

  Objectives 🎯

🔍 Identify the leading single and compound predictors of student depression.

💡 Recommend actionable, evidence‑based strategies for educators, institutions, and stakeholders.


Data Cleaning & Transformation "Power Query" 🔄

Deduplication: Removed duplicate records in the Raw Data sheet.

Text Parsing & Bucketing: Converted text fields (e.g., "Sleep Duration") to numeric ranges and grouped into categories.

Bucket Creation: Defined Low/Medium/High thresholds for Academic Pressure, Financial Stress, and other Likert‑scale variables.

Boolean Flags: Mapped depression (0/1) and suicidal thoughts (Yes/No) to TRUE/FALSE in Cleaned Data.

Enrichment: Added Country and IsStudent flags for geographic and cohort segmentation.



Exploratory Data Analysis 🔍

Part 1: Demographics Analysis

Data location--> India

Top Cities by Depression Count: Kalyan (1,570), Srinagar (1,370), Hyderabad (1,338).

Students vs. Others: 99% of depressed respondents are students.

Gender × Age Bands: Females (44%): Young 23%, Mid 17%, Senior 4%; Males (56%): Young 28%, Mid 21%, Senior 7%.

Part 2: Single‑Feature Analysis

"we have calculated the depression rate for each factor alone to locate the highest depression value, & that is what we have found"

High Academic Pressure: 81.6% depressed

Suicidal Thoughts = TRUE: 79.1% depressed

High Financial Stress: 75.6% depressed

Low Study Satisfaction: 70.7% depressed

Unhealthy Diet: 70.7% depressed

high study hours: 67%

GPA Excellent :61%

Short Sleep Duration: 61.3% depressed

Family illness history = True:61% 

Insights from Analysis 💡

Top Single Predictors: Academic Pressure (81.6%), Suicidal Thoughts (79.1%), Financial Stress (75.6%).

Protective Extremes: Low Academic Pressure (19.5%) and Healthy Diet (45.4%).

" so  we have taken the highest key factors that indicate high depression value and make a solid analysis that puts them together to hotsopt  the highest two factors together that represent the highest risk"

Part 3: Hotspots Analysis

High Academic Pressure + Suicidal Thoughts =True : 91.9% depressed

High Academic Pressure + High Financial Stress: 90.7% depressed

Suicidal Thoughts + High Financial Stress: 89.1% depressed

High Academic Pressure + Low Study Satisfication :89% Depressed

Suicidal Thoughts + Low Study Satisfaction: 86.8% depressed

High Financial Stress +  Low Study Satisfaction : 83% depressed

Suicidal Thoughts + Family illness history= true : 81% depressed

Unhealthy diet + Short Sleep :73%

High study hours + Short Sleep :69%


Insights from Analysis 💡

Peak Compound Risk: High Academic Pressure + Suicidal Thoughts (91.9%).


Recommendations 🎯

Mitigate Academic Pressure via Mindfulness‑Based Stress Reduction and growth‑mindset workshops.

Screen & Support Suicidal Ideation with routine ideation screening and gatekeeper training.

Alleviate Financial Stress through financial literacy workshops and rapid‑response emergency aid.



Tools Used 🛠️

Excel 365 (Power Query & PivotTables & pivot Charts)

Chat Gpt

DeepSeek

Grammarly

Perplexity

Git and git hub

Git & GitHub (version control)


Next Steps ⏭️

Transition advaneced analysis to  SQL   to handle larger datasets beyond Excel’s row limits & BI tools such as Power BI and Tableaue for more advaned visualization rather than the basic excel charts.

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

