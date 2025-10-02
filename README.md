# NSMQ-Dashboard-Analysis
![nsmq](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/nsmq.jpg)

Power BI analysis of Ghana’s National Science &amp; Maths Quiz (2016–2024). Explores school dominance, regional strength, gender representation, and competitiveness with interactive visuals and KPIs.


## 🔍 Project Objective

To analyze NSMQ data from the 1/8 stage upwards and uncover insights on:
- Which schools and regions dominate the competition
- How gender representation looks across Mixed, Boys, and Girls schools
- The scoring power and competitiveness at different stages
- Regional distribution of advancement and wins


## 🧮 Main KPIs

- **Total Schools Represented (2016–2024)**: Unique schools that participated.
- **Championship Titles**: Total wins by schools at the Final stage.
- **Average Winning Score**: Average points scored by champions in the Finals.
- **Average Scores by Year & Gender**: Trend comparison across 8 years.
- **Stage Advancement by Region**: Number of schools per region reaching Quarter, Semi, Final.


## 🛠️ Project Process

1. **Data Cleaning & Prep**  
   - Handled nulls with replacement (for example, “No”, “None”, “Others”).
   - Created Stage_Label mapping (1/8 Final, Quarter, Semi, Final) for better visuals.
   - Built measures for advancement, wins, and average scores

2. **Data Modeling**  
   - Applied DAX measures (such as Total Wins, Avg_Winning_Points).
   - Structured calculations for school dominance, gender breakdowns, and competitiveness.

3. **Visualization Design**  
   - Clustered bar charts for Stage Advancement by Region.
   - Line charts for Gender-based scoring trends.
   - KPI Cards for Total Schools, Average Winning Score.
   - Ghana-focused filled map for Regional Wins.
   - Rounded bar hack (error bars) for polished visuals.


## 📸 Dashboard Visualization

![Dashboard Screenshot](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/NSMQ%20analysis.png)
