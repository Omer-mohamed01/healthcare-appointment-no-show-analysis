# 🩺Healthcare Operations
Power BI healthcare analytics project analyzing appointment no-shows, waiting times, and patient attendance behavior.

## Data Used
<a href="https://www.kaggle.com/datasets/joniarroba/noshowappointments?resource=download">Medical Appointment No Shows</a>
</br>
Used under a public data license for educational purposes.

## Dasboard
<a href="https://app.powerbi.com/groups/0de4da28-3fc8-4014-a6a0-ddb5c2509927/list?experience=power-bi">Healthcare Operations Dasboard</a>
</br>

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
![](https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/041f78fcc5cf34b738049fa04ec2a6719fef599c/Charts/Financial%20Drain%20Analysis%20(Breaking%20Down%20Lost%20Revenue).png)
</br>
![](https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/041f78fcc5cf34b738049fa04ec2a6719fef599c/Charts/Root%20Cause%20Analysis%20(Drivers%20of%20Missed%20Appointments).png)

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


Healthcare Operations
</br>
README.md
</br>
LICENSE
</br>
├── Data |
    └──<a href="https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/95d2bd1cb990c9291a7e83b29c431ac6f4e70b8c/Data%20Source/medical-appointment-2016.csv">Data Source.csv</a>
    </br>
├── Link |
    └──<a href="https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/95d2bd1cb990c9291a7e83b29c431ac6f4e70b8c/Data%20Source/Data%20Source%20Link.txt">Data Source Link.txt</a>
</br>
├── Excel |
  └──<a href="https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/95d2bd1cb990c9291a7e83b29c431ac6f4e70b8c/Data%20Cleaning/Medical%20Appointment%202016.xlsx">Data Cleaning.xlsx</a>
</br>
├── Power bi |
   └── <a href="https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/55474a8925b3a9852ab6d067210dcf94a6c82ba9/Data%20Analysis/Medical%20Appointment%202016%20Analysis.pbix">Medical Appointment 2016.pbix</a>
</br>
├── Presentation |
   └── <a href="https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/06ab7da92ff6fb78ffdcb2544d2fe4765eb89fd2/Document/Healthcare%20Operations%20Presentation.pdf">Medical Appointment 2016.pdf</a>
</br>
└── Images |
    </br>
    └── <a href="https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/e73d8c3d9c590ce794e78d7971186ecdbb2e2c30/Charts/Dasboard.png">Dasboard Overview.png</a>
    </br>
    └── <a href="https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/e73d8c3d9c590ce794e78d7971186ecdbb2e2c30/Charts/Total%20Number%20of%20%20Missed%20by%20Age%20Group.png">Age Group Impact.png</a>
    </br>
    └── <a href="https://github.com/Omer-mohamed01/healthcare-appointment-no-show-analysis/blob/e73d8c3d9c590ce794e78d7971186ecdbb2e2c30/Charts/Total%20Number%20of%20%20Missed%20by%20SMS%20Received.png">SMS Impact.png</a>

---

## 🧠 Explanation
This structure helps others quickly understand:
- What each folder contains  
- How your project is organized  
- Where to find key deliverables (data, presentation, visuals)

---

