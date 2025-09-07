# 📊 Mathematics After COVID-19

## 🧠 Project Overview

This project aims to analyze and understand the global gap in mathematics
 proficiency among primary school students before and after the COVID-19 pandemic.
  The work focuses on comparing learning outcomes between 2019 and 2023 and
   exploring the possible role of factors such as:

- School closures  
- Education spending  
- Digital connectivity  
- Access to trained teachers

---

## 👥 EduCatalysts Team

Our team brings diverse perspectives from teaching, data analysis, and lived experience:

- [__Heba Abudahrouj__](https://github.com/heba3)
- [__MD Jubayer Khan__](https://github.com/MD-Jubayer-Khan)
- [__Nada Saed__](https://github.com/Nada-saad635)
- [__MayMon__](https://github.com/MayMon-T3807)
- [__Alexander Andom__](https://github.com/aandom)
- [__Momtaz Yaqubic__](https://github.com/Momtaz-yaqubi)

---

## 💡Milestone 0 :Domain Stud- Key Questions

- How much did math proficiency change during the pandemic?  
- Which countries or regions were most affected?  
- What factors are most strongly associated with greater learning loss?
  
for more information about background research and problem framing question you can find it in this
  ([folder](./0_domain_study/README.md)) in this ([file](./0_domain_study/research_question))

---

## Team understanding of the learning problem after the COVID-19 pandemic

 📌 Problem Statement  

During our group discussion, we shared personal experiences of how __COVID-19__ disrupted math learning in different but connected ways:  

- 👩‍🏫 __Teachers__ (e.g., Heba) struggled with remote classes — unstable internet, shared devices, and large classrooms later made it impossible to support every student.  
- 👩‍🎓 __Students__ (e.g., Nada) faced poor connections, unclear recorded lessons, and lack of support, leaving them behind in math and other subjects.  
- 🌍 __Context__ (e.g., May from Myanmar) showed how the pandemic, combined with political crises, forced students to delay or stop their education.  
- 🤝 __Peers__ (e.g., Jubayer & Alexander) highlighted similar struggles in access and quality across different regions.  

💡 Together, these stories show __serious and unequal math learning gaps__, especially in low and middle-income settings. Teachers were overwhelmed, and students lacked even the most basic learning tools.  

you can find more information in this ([file](./0_domain_study/problem_statment))
![Understanding](notes/visuals/understanding.png)

---

## 🎯 Goals

- Quantify the change in math proficiency across countries.  
- Identify patterns and factors that may have contributed to the learning gap.  
- Provide insights through visualizations and models to better understand
the educational impact of the pandemic.

---

## 📌 Project Flow Diagram

![Project Overview](notes/visuals/workflow.png)

_Diagram showing the data flow and analysis process to explore the
 math learning gap post-COVID._

---

## 📂Milestone 1: data Collection- 🔍 What We Did

Our data was mainly collected from __UNESCO’s UIS (Institute for Statistics)__ open data platform.  
To add important context, we included supplementary datasets from __UNICEF__ (digital connectivity)  
and the __World Bank__ (income classifications and education indicators).  

- 🎯 Focus: % of students achieving minimum math proficiency  
- 🌍 Grouping: Countries by __World Bank income levels__  

- 📉 Case study: Bangladesh school data (2019–2021) confirmed visible learning loss  

👉 For full details on data sources, variables, and limitations ([folder](./1_datasets/raw_data/))

---

## 🧼Milestone 2 : data Cleaning  

We cleaned and standardized the raw datasets to make them ready for analysis.  

- 🗂️ Converted raw data into a consistent format  
- 🚫 Removed non-country entries  
- 🌍 Aligned all records using __ISO country codes__  
- 🔗 Merged variables into a single dataset  

👉 The cleaned output is available as:([file](./1_datasets/final_dataset.csv)) `1_datasets/final_dataset.csv`  

---

## 🔍 Milestone 3 Data Exploration

We explored both the global dataset and a case study dataset to understand learning patterns.  

- 🌐 __Global dataset__ (`data_exploration.ipynb`):  
  Checked structure, missing values, descriptive stats, and visualized math proficiency changes (2019–2023).  
  Also identified countries with the largest learning losses.  

- 🇧🇩 __Bangladesh case study__ (`class7_math_exploration.ipynb`):  
  Explored grade 7 math scores (2019–2021) with boxplots and histograms to observe the pandemic’s disruption.  

👉 Full details and visuals are in the exploration notebooks.
 [_here class 7_](3_data_exploration/class7_math_exploration.ipynb) and [(here global)](3_data_exploration/data_exploration.ipynb)

---

## 📊Milestone 4 : Data Analysis  

We analyzed the dataset (2019–2023) to understand how __math proficiency__ changed during the COVID-19 period  and which factors explain this variation.  

- 🔍 Explored correlations between key education indicators  
- 📈 Built __linear & multiple regression models__  
- 🖼️ Visualized results using heatmaps, regression plots, and residual checks  

👉 For full details, methods, and code, see [__Analysis Notebooks__](4_data_analysis/dataset_analysis.ipynb).  

---

## 📈 Key Results

- Over 1.6 billion learners worldwide experienced educational disruption, with 463 million children unable to access remote learning.
- Field studies documented sharp declines in mathematics proficiency, including a >27% drop for Brazilian second graders and regression to pre‑primary skill levels in Kenya and Uganda.
- The affected cohort may face up to $17 trillion in lost lifetime earnings, and learning poverty in low- and middle-income countries could reach 70%.
- Structural issues like weak digital infrastructure, teacher burnout, and inflexible curricula deepened the gap.
- Country data show divergent paths between 2019 and 2023: Albania and Armenia improved, while Australia, Azerbaijan, and Belgium declined.

![results](notes/visuals/results.png)

---

### 📝 Milestone 5: Communication Strategy  

A policy-focused plan targeting __education ministers, advisors, and international organizations__.  
Core message: __Targeted math recovery programs can close 78% of COVID-19 gaps at 1/3 the cost of grade repetition__ (Bangladesh + UNESCO data).  

__Deliverables:__  

- 📄 [Policy Brief](./policy_brief.md)  
- 📊 [Interactive Dashboard](https://drive.google.com/drive/folders/1tpDZ0wg6AT8JyFbr3WtrYFN7_c2tpz0n?usp=sharing)  

---

## 🤝 Acknowledgments

This work is part of an academic data science initiative focused on
 understanding global development challenges using real-world data.

---
