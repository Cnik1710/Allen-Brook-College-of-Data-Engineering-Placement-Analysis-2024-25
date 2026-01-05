# Allen Brook College of Data Engineering Placement Analysis (2024-25)
 
 ---
## 🎯 Objective
To develop an interactive Placement Analytics Dashboard to analyze placement performance and key salary drivers for Allen Brook College of Data & Engineering (ABCDE).
### **Project Purpose:**
Evaluate placement outcomes to uncover **factors—CGPA, degree background, specialization, gender, work experience—that influence placement success and salary levels.**
   * Build an interactive **Excel dashboard** for college administrators, career services, and students.
   * Provide actionable recommendations to improve **placement support** and **student readiness**.
### **Key KPIs:**
   * Overall Placement Rate
   * Total Students by Gender/Background
   * Average Salary by Gender/Background
   * Placement Rate by Gender/Background
   * Average Salary by CGPA Band, Top-paying Specializations.**
### **Deliverables:**
   * Excel dashboard, presentation slides, and a concise insights report.
---

## 📘 Project Overview 
### **Context Highlights:**
   * Analyzed placement records of **215 students** from Allen Brook College of Data & Engineering (ABCDE).
   * Dataset covers **academic metrics** (degree type, specialization, CGPA), **demographics** (gender, work experience), and **placement outcomes** (status, salary).
   * Demonstrates how **data analytics empowers institutional decisions** to optimize placement strategies and student performance evaluation.
   * Built an **interactive Placement Analytics Dashboard** using Excel (Pivot Tables, Charts, and KPI visuals).
     * Key insights derived on:
       * Overall placement rate and salary distribution
       * CGPA-to-salary correlation patterns
       * Gender and background-based placement trends
       * Specialization-wise salary contributions     
 ---
 
## 🗂️ Data Overview & Schema     
### **Data Source:**  
  * Source: Fictionalized college placement dataset (inspired by open educational datasets).
  * Data Type: Structured student records and outcomes (placement status and salary).
  * Time Period: One-time snapshot for the academic year **2024-25**.  
### **Data Structure & Metrics:** 
   * Key Index Types: Student-level records
   * Total Rows: 215 
   * Categories: Approximately **15 features** covering three main buckets: 
      * Demographics: Gender, Work Experience (Yes/No). 
      * Academics: Secondary percentage (ssc_p), Higher Secondary percentage (hsc_p) & background (hsc_b), Degree percentage (degree_p) & degree type (degree_t) and MBA percentage (mba_p) - Backgrounds/Types Specialization – Mkt&Fin / Mkt&HR 
      * Placement: Placement Status and Salary. 
   * Calculated Metrics: Binary Placement Status (placement_flag = 1/0) derived for classification modeling.
 ---
 
## 💻 Tech Stack    
### **Tools:**
   * **Excel**
      * Data cleaning & preprocessing
      * Pivot Tables for aggregation
      * Pivot Charts for visualizations
      * Slicers/filters for interactivity Dashboard creation
   * **PowerPoint**
      * Presentation and final dashboard snapshots
---
        
## 📈 Methodology & Analysis  
### **Prepare, Process & Analytical Approach:** 
A structured analytical workflow was followed to ensure data accuracy, meaningful insights, and interactive visualization.
 * **Data Preparation & Cleaning:**
   * Removed missing, duplicate, and inconsistent values to maintain data reliability.
   * Standardized categorical fields such as Degree Type and Specialization for uniform analysis.
   * Ensured consistent formatting for CGPA, salary, and placement status fields.
 * **Data Modeling & Integration:**
   * Organized data into analysis-ready tables to support aggregation and segmentation.
   * Established relationships between academic background, placement status, and salary metrics.
   * Prepared structured datasets optimized for pivot-based analysis.
* **Feature Engineering:**
   * Created a derived field placement_flag (1 = Placed, 0 = Not Placed) to simplify KPI calculations.
   * Grouped CGPA into defined ranges (e.g., 5.00–5.99, 6.00–6.99, etc.) for trend analysis and comparisons.
* **Visualization Design:**
   * Used Pivot Tables to summarize placement rates, salary metrics, and academic distributions.
   * Built Pivot Charts to visualize trends across CGPA, specialization, gender, and background.
   * Implemented Slicers & Filters to enable dynamic, interactive exploration of the dashboard.
 * **Validation & Formatting:**
   * Cross-verified KPI calculations such as placement rate, average salary, and salary extremes.
   * Ensured visual consistency through standardized labels, scales, and color themes.
   * Optimized dashboard layout for clarity, readability, and executive-level interpretation.
---
 
## ❓ Problem Statements
College often collect detailed placement data, but it remains **scattered and underutilized**, leading to limited visibility into placement performance, salary trends, and academic correlations.
Without consolidated insights, it becomes difficult to identify performance gaps or guide students effectively.  
### Key Questions:
*   What is the overall placement rate of the college?
*   How do CGPA and specialization influence placement and salary outcomes?
*   Are there gender-based or academic background-based differences in placement results?
*   What are the average, highest, and lowest salary patterns across different student segments?
*   How can the college leverage these insights to improve placement strategies and student preparedness?
---

## 💡 Key Insights      
### **Top Findings:** 
*   **Placement Rate**: 69% of students (148 out of 215) were successfully placed.
*   **Gender Gap**: Males earned a higher average salary (₹2.15 LPA) compared to females (₹1.69 LPA).
*   **Academic Background**: Students from **Science & Tech** backgrounds achieved the **highest average salary (~₹2.19 LPA)**.
*   **Specialization**: **Marketing & Finance** students earned **57% higher salaries** and had better placement rates than **Marketing & HR** students.
*   **CGPA Correlation**: Salary increased steadily with CGPA — students with **8–9 CGPA** earned an **average ₹3.45 LPA**.
*   **Work Experience**: Students with prior work experience showed **slightly higher placement success and pay levels**.
### **Supporting Metrics:**
*   Average Salary (Placed Students): ₹4.5 LPA
*   Highest Salary: ₹9.6 LPA
*   Lowest Salary: ₹2.4 LPA
*   Placement by Specialization: Mkt&Fin – 72%, Mkt&HR – 61%
*   Trend: Clear positive correlation between CGPA and Salary
---
 
## 📍 Conclusion
### **Summary:** 
The placement analysis of Allen Brook College of Data & Engineering reveals distinct trends in student performance and employment outcomes.
  * Science & Technology students consistently secure the **highest salary packages**, while **Commerce & Management** has higher student participation.
  * A **strong positive correlation** exists between **CGPA and salary**, confirming that academic excellence directly enhances placement prospects.
  * **Specialization and gender** continue to influence placement outcomes, highlighting areas for institutional focus.
  * The interactive dashboard delivers a **concise, data-driven overview** of college placement performance — enabling administrators to refine **career support strategies**, align **curriculum with industry trends**, and help students understand **key drivers of salary and employability**.
  * Overall, this project demonstrates the power of **data analytics in driving academic and placement excellence**.
---
 
## 🖥️ Dashboard Overview
![image alt](https://github.com/Cnik1710/Allen-Brook-College-of-Data-Engineering-Placement-Analysis-2024-25/blob/4b57070016abfe6a8aa65905293008b044bb703d/Allen%20Brook%20College%20of%20Data%20%26%20Engineering%20(ABCDE)%20Placement%20Analysis%20Dashboard.png)

---
 
## ✅ Business Impact & Use Cases   
* **College Administration & Management:**
  Leverage placement analytics to evaluate program performance, identify academic strengths and gaps, and plan strategic improvements in training and curriculum.
* **Training & Placement Cell:**
  Use data-driven insights to monitor placement trends, target underperforming student groups, and strengthen industry partnerships through transparent reporting.
* **Faculty & Academic Departments:**
  Understand how academic background and specialization influence placement outcomes, guiding curriculum updates and mentorship strategies.  
* **Students & Career Advisors:**
  Gain awareness of how CGPA, specialization, and skill development affect placement chances and salary expectations, helping tailor preparation plans.
* **Recruiters & Industry Partners:**
  Access data-supported insights on student quality, academic diversity, and performance trends to optimize recruitment strategies and hiring pipelines.     
 ---
 
 ## 🙏 Acknowledgements & Contact 
 ### Project Analyst: Anik Chakraborty	
   📧 Email: anikc1710@gmail.com  
 ### Special Thanks To: 
 * Coding Ninjas – for project framework and guidance  
   
