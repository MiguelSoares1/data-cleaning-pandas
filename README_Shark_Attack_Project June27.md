
# 🦈 Shark Attack Data Analysis

## 📌 Summary

This project explores patterns and trends in hark attack incidents using real-world data. It investigates whether younger individuals are more frequently targeted and whether fatal attacks have decreased over time. The ultimate goal is to extract actionable insights and identify potential business applications derived from the data.



## 📂 Data Source

The dataset used in this project originates from the [Global Shark Attack File (GSAF)](https://www.sharkattackfile.net/), a comprehensive, publicly available database that records global shark-human interaction events since the early 1900s. The dataset was obtained in CSV format and includes information such as:

- Date of attack  
- Location  
- Age of the individual  
- Activity during the time of the attack  
- Whether the attack was fatal or not  

---

## ❗ Key Issues with the Data

- 🧩 **Inconsistent Formats**:  
  - Date fields in mixed or non-standard formats  
  - Activity and location often free-text, requiring cleaning

- 🕳️ **Null or Missing Values**:  
  - Several columns contain missing values, especially in "Age", "Activity", and "Fatal" status

- 🔁 **Redundant or Irrelevant Columns**:  
  - Multiple unnamed or duplicate columns that needed to be dropped

- 🔤 **Incorrect Data Types**:  
  - Some numeric columns were read as text due to formatting issues

- ✂️ **Outliers and Noise**:  
  - Inconsistent descriptions in "Activity" such as “swimming”, “Swmming”, “swimmming” required normalization





## 🧪 Hypotheses and Key Findings

### Hypothesis 1: Younger people (under 30) are attacked more often, particularly during activities like swimming or surfing.

**Findings**:
- The age group **under 30** accounts for a significant proportion of attacks, especially during recreational water activities.
- **Top activities** linked with this age group: Surfing, Swimming, and Spearfishing.
- Visualizations confirmed that youth and high-activity engagement correlate with higher attack counts.

### Hypothesis 2: Fatal shark attacks have decreased over time.

**Findings**:
- While **overall shark attacks have increased**, **fatal attacks have declined** steadily since the 1980s.
- This could be due to **better medical response**, **public awareness**, and **technology (e.g., drones, alert systems)**.
- Temporal trends and fatality ratio graphs clearly support this conclusion.

---

## 🏢 Business Ideas Derived from Data

1. **Shark Activity Awareness App**  
   → Based on age, location, and activity, give real-time safety scores for beachgoers.

2. **Insurance Risk Models**  
   → Insurance companies could use this data to build specialized coastal activity risk plans.

3. **Smart Lifeguard Deployment**  
   → City councils can allocate resources during high-risk months/activities.

4. **Educational Content for Tourism Companies**  
   → Promote safer water practices targeting young tourists.



