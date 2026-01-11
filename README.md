# Healthcare Operations
Power BI healthcare analytics project analyzing appointment no-shows, waiting times, and patient attendance behavior.

## Data Used
<a href="https://divvy-tripdata.s3.amazonaws.com/index.html">Divvy Bike Share System Data (2019 Q1–Q4)</a>
</br>
Used under a public data license for educational purposes.

## 📊 Project Overview
This project analyzes medical appointment data to understand the key factors driving appointment no-shows, long waiting times, and patient attendance behavior. The goal is to provide actionable insights to improve clinic scheduling efficiency and patient experience.

## 🧩 Business Task
Healthcare providers face high no-show rates and long waiting times, leading to wasted resources and reduced care availability. This analysis identifies operational and patient-related drivers behind missed appointments.

## 🧰 Tools Used
Excel – Data cleaning and preprocessing.
</br>
Power BI – Data modeling, DAX measures, dashboards.
</br>
PowerPoint → Final presentation of insights and recommendations.

## 🧹 Data Cleaning
Removed null and invalid records.
</br>
Converted date-time fields into proper date formats and standardized them for analysis.
</br>
Calculated waiting days between scheduled and appointment dates and removed invalid negative values.
</br>
Handled unrealistic values (e.g., out-of-range ages) to improve data quality.
</br>
Created derived time attributes such as month name, month number, and day of week.
</br>
Standardized attendance status by transforming the no-show indicator into a clear Show / No-Show field.
</br>
Verified data integrity using distinct appointment identifiers to avoid double counting.

## 📈 Key Insights
Longer waiting times significantly increase no-show rates.
</br>
SMS reminders reduce missed appointments.
</br>
Younger age groups show higher no-show behavior.
</br>
Patients waiting more than 7 days are more likely to miss their appointment.
![](https://github.com/Omer-mohamed01/Cyclistic-Bike-Share-Analysis/blob/16dab1253fc05c436aba562428730ee514ceeb40/Charts/Sum%20of%20Trips%20Casual%20vs%20Annual.png)
</br>
![](https://github.com/Omer-mohamed01/Cyclistic-Bike-Share-Analysis/blob/16dab1253fc05c436aba562428730ee514ceeb40/Charts/Average%20Ride%20Length%20Day%20of%20Week.png)

## 💡 Recommendations
Reduce scheduling lead times where possible.
</br>
Expand SMS reminder programs.
</br>
Prioritize high-risk no-show segments.
</br>
Use data-driven scheduling strategies.

## 🧠 Outcome
This analysis provided clear, actionable insights into the factors influencing medical appointment attendance. Key outcomes.
</br>
The project translates raw healthcare data into practical insights that support improved operational efficiency and patient experience.
---

## 🗂️ Project Structure


healthcare-appointment-no-show-analysis/
</br>
README.md
</br>
LICENSE
</br>
├── Data |
    └──Data medical_appointment_noshow.csv
</br>
├── Excel |
  └──data_cleaning.xlsx
</br>
├── Power bi |
   └── Medical_Appointment_Analysis.pbix
</br>
├── Presentation |
   └── Medical_Appointment_Insights.pdf
</br>
└── Images |
    </br>
    └── dashboard_overview.png
    </br>
    └── no_show_by_waiting_days.png
    </br>
    └── sms_impact.png

---

## 🧠 Explanation
This structure helps others quickly understand:
- What each folder contains  
- How your project is organized  
- Where to find key deliverables (data, presentation, visuals)

---

