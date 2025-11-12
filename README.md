# Early-Sepsis-Detection-through-Clinical-Data-Analysis
In the United States, sepsis affects at least 1.7 million adults annually and is the leading cause of death in hospitals, contributing to about 350,000 deaths each year. It is an extreme, life-threatening response to an infection that can cause organ damage and death, with the risk of death increasing the longer it goes untreated. Common signs include fever or low temperature, confusion, difficulty breathing, clammy skin, and a high heart rate. Prompt detection and treatment are therefore essential to improving outcomes and minimizing the devastating impact of sepsis.

<img width="661" height="465" alt="Screenshot 2025-11-12 at 10 26 25 AM" src="https://github.com/user-attachments/assets/1b1f013d-1193-49eb-9b5a-8aef400aea33" />

## Objective
To promtly detect a patient’s risk of developing sepsis and generate hourly sepsis predictions based on their clinical records.

## About Clinical Data 
This dataset comprises over 1.5 million clinical data points from more than 40,000 ICU patients, aimed at detecting early sepsis.

Using SQL, Excel, and Tableau, I performed:

## Demographic Analysis: 
Patient profiling to identify high-risk groups and trends in sepsis incidence. I leveraged Level of Detail (LOD) expressions and calculated fields in Tableau to classify patients into sepsis, non-sepsis, and onset groups.

<img width="1390" height="715" alt="Screenshot 2025-11-12 at 10 47 39 AM" src="https://github.com/user-attachments/assets/1c90ef7e-82d8-4d93-b816-22f49da60ba7" />

## Biomarker & Vital Sign Analysis: 
Monitored 34 key biomarkers and vital signs to detect early warning signals of sepsis.


## Sepsis Stage Analysis: 
Evaluated SIRS criteria and septic shock progression to monitor disease severity and support timely interventions. Identified critical trigger hours using Fixed LOD expressions and visual alerts for abnormal biomarker readings. To enhance real-time response, implemented email alert actions in Tableau dashboards to notify medical teams immediately when patients reached high-risk conditions.
These analyses generated actionable insights, improving ICU efficiency, enabling prompt intervention, and supporting better patient outcomes.

<img width="1401" height="554" alt="Screenshot 2025-11-12 at 10 54 52 AM" src="https://github.com/user-attachments/assets/57141eac-64be-47a5-9f86-1bf56d18d6b9" />

## Conclusion
This project demonstrates how data-driven analysis of clinical records can enable early detection of sepsis, allowing medical teams to intervene before the condition becomes critical. By combining demographic profiling, biomarker monitoring, and sepsis stage evaluation, actionable insights were generated to improve patient outcomes, enhance ICU efficiency, and reduce the risk of sepsis-related mortality. The integration of real-time alerts in Tableau dashboards showcases the potential of analytics to support proactive, life-saving clinical decisions.
