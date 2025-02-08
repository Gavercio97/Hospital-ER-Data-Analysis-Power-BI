## **Hospital Emergency Room Data Analysis – Power BI**

### **Overview**  
Emergency room overcrowding and long wait times can impact patient care. This Power BI dashboard analyzes hospital emergency room data to provide insights into patient flow, wait times, and referral patterns, helping stakeholders make data-driven decisions.

### **Problem Statement**  
Hospitals need a way to monitor emergency room efficiency, track patient demographics, and identify areas for improvement. The objective was to analyze ER performance and identify bottlenecks affecting patient experience.

### **Data Source & Preparation**  
- **Dataset:** Kaggle  
- **Data Cleaning:** Used Power Query to remove duplicates, handle missing values, and standardize column formats.  
- **Transformations:** Created DAX measures for key metrics such as *Average Wait Time* and *Percentage of Patients Seen Within 30 Minutes*.

### **Key Metrics & Visualizations**  
- **Total Number of Patients** (KPI card)  
- **Average Wait Time** (KPI card)  
- **Patient Satisfaction Score** (KPI card)  
- **Number of Patients Referred** (KPI card)  
- **Visuals:**  
  - **Patient Admission Status:** Horizontal bar chart  
  - **Percentage of Patients Seen Within 30 Minutes:** Donut chart  
  - **Patients by Age Group:** Vertical bar chart  
  - **Patients by Gender:** Donut chart  
  - **Patients Referred by Different Departments:** Horizontal bar chart  
  - **Patients by Race:** Horizontal bar chart  
  - **Patients by Day and Hour:** Vertical bar chart and tree map  
  - **Filters:** Month and year  
---
###**Dashboard**
![Hospital Emergency Room Dashboard](https://github.com/Gavercio97/Hospital-ER-Data-Analysis-Power-BI/blob/main/assets/images/Hospital%20ER%20Dashboard.png)
---

### **Insights & Recommendations**  
- **Peak ER Days and Hours:** The highest patient volume mostly occurs in the afternoon in the mid days of the week; hospitals can adjust staffing accordingly to meet these demands.  
- **Wait Time Issues:** In most cases, a large percentage of patients waited longer than 30 minutes, indicating a need for process optimization to cut down on the wait time.  
- **Referral Trends:** Most patients came in without being referred by any department.  
- **Age Group & Gender Trends:** Understanding patient demographics helps in targeted healthcare planning.  

### **Challenges & Learnings**  
- Data required cleaning due to missing values and inconsistencies.  
- Creating efficient DAX measures for time-based calculations.  
- Optimizing dashboard layout for clarity and usability.  

### **Conclusion & Next Steps**  
This dashboard provides actionable insights to improve emergency room efficiency. Future improvements could include integrating real-time data and predictive analytics to anticipate peak hours and improve resource allocation.

