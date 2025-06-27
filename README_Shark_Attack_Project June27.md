# 🦈 Shark Attack Data Analysis

## 📌 Summary

This project explores patterns and trends in shark attack incidents using real-world data. It investigates whether younger individuals are more frequently targeted and whether fatal attacks have decreased over time. The ultimate goal is to extract actionable insights and identify potential business applications derived from the data.

Link for presentation: https://prezi.com/view/3cwvgd5TMGh6kLop9UWl/

## 📂 Data Source

The dataset used in this project originates from the [Global Shark Attack File (GSAF)](https://www.sharkattackfile.net/incidentlog.htm), a comprehensive, publicly available database that records global shark-human interactions dating back to the early 1900s. The dataset was obtained in CSV format and includes information such as:

- Date of attack  
- Location  
- Age of the individual  
- Activity at the time of the attack  
- Whether the attack was fatal  

---

## ❗ Key Issues with the Data

- 🧩 **Inconsistent Formats**  
  - Date fields appeared in mixed or non-standard formats  
  - Activity and age were free-text and required cleaning

- 🕳️ **Null or Missing Values**  
  - Several columns contained missing data, particularly "Age", "Activity", and "Fatal" status

- 🔤 **Incorrect Data Types**  
  - Some numeric columns were read as text due to formatting issues

- ✂️ **Outliers and Noise**  
  - Inconsistent entries in "Activity" like “swimming”, “Swmming”, and “swimmming” required normalization

---

## 🧪 Hypotheses and Key Findings

### 🧠 Hypothesis 1: Younger people (under 30) are attacked more often, particularly during activities like swimming or surfing.

**Findings**:
- The **under-40 age group** accounts for a significant portion of shark attacks, especially during recreational water activities (from 2000 to 2019).  
- **Top activities** for this group: Surfing, Swimming, and Spearfishing  
- Visualizations confirm that youth and high-activity engagement correlate with higher attack counts.

### 📉 Hypothesis 2: Fatal shark attacks have decreased over time.

**Findings**:
- Although **overall shark attacks have increased**, **fatal attacks have steadily declined** since 2000.  
- This may be due to **improved medical response**, **greater public awareness**, and **technological advancements** (e.g., drones, alert systems).  
- Temporal trend graphs support this conclusion.

---

## 🏢 Business Ideas Derived from the Data

1. **Shark Activity Awareness App**  
   → Offers real-time safety scores for beach visitors based on age, location, and activity.

2. **Insurance Risk Models**  
   → Insurers can use this data to create specialized coastal activity risk profiles.

3. **Smart Lifeguard Deployment**  
   → Local authorities can allocate lifeguard resources based on high-risk months and activities.

4. **Educational Content for Tourism Companies**  
   → Promote safer water practices targeting younger, high-risk tourists.
