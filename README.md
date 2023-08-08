# Tracking-Breast-Cancer-Severity

This project is the development of end-to-end data pipeline that follows CRISP-DM strategy

CRISP-DM stands for "Cross-Industry Standard Process for Data Mining." It's a widely-recognized methodology providing a structured approach for planning, organizing, and executing data mining projects. The CRISP-DM methodology consists of six major phases:

#### Business Understanding:
This initial phase focuses on understanding the project objectives and requirements from a business perspective. It involves defining the problem, understanding the business's objectives, and formulating a preliminary plan to achieve those objectives.

#### Data Understanding: 
Here, the focus is on collecting the data and familiarizing oneself with it. This includes tasks such as data loading, data exploration, and data quality assessment.

#### Data Preparation: 
This phase is often considered the most time-consuming in the data mining process. It involves cleaning the data (handling missing values, removing outliers), transforming variables (e.g., normalization, encoding categorical variables), and creating derived variables.

#### Modeling: 
In this phase, various algorithms and techniques are applied to the prepared dataset to develop models. It often involves selecting the right modeling technique, building the model, and assessing the model.

#### Evaluation: 
Once models have been built, this phase ensures they meet the business objectives set in the first phase. It involves assessing the model's results against the business goals, considering possible deployment strategies, and determining if more work needs to be done.

#### Deployment: 
The final phase is about deploying the model into a real-world environment. Depending on the business needs, this could be making the model available for business analysts, integrating the model into business processes, or developing interactive visualizations and reports.

![image](https://github.com/Alagesan-Sushmitha/Tracking-Breast-Cancer-Severity/assets/137837229/fe593b1c-7cde-4fcf-98cd-5513cc54a93a)

# Business Understanding 
Objective of the Clinical Trial:
The primary objective is to evaluate recovery stability and patient comfort post-surgery using various physiological measurements.

Phases of Clinical Trials:
This seems to be a Phase III trial where the efficacy of a new post-surgical recovery protocol is being tested on a broad group of patients to compare it to existing standards.

Regulatory & Ethical Compliance:
The data collected respects patient confidentiality, ensuring that all personally identifiable information is removed. All participants have provided informed consent to monitor their recovery metrics post-surgery.

Data Complexity:

patients_internal_temperature and patients_surface_temperature: Measure the patient's core and external temperature, respectively.
oxygen_saturation: Indicates how much oxygen the blood is carrying.
last_measurement_of_blood_pressure: Captures the most recent blood pressure reading.
Stability indicators (patients_surface_temperature_stability, patients_core_temperature_stability, patients_blood_pressure_stability): Provide insights on fluctuations or stability in these metrics.
patients_perceived_comfort_discharge: A qualitative measure capturing patient feedback on comfort levels upon discharge.
decision: Perhaps a binary or categorical output indicating if the patient is ready for discharge or needs more monitoring.
Stakeholders:

Surgeons and Medical Teams: Interested in monitoring recovery and improving post-op protocols.
Hospital Administration: Keen on ensuring quick, safe recoveries to free up beds without compromising patient health.
Patients: Want to ensure they are stable post-surgery and understand the metrics for their health.
Data Quality and Integrity:
All data points are collected using calibrated medical equipment. The patient feedback on comfort is collected through standardized questionnaires to ensure consistency.

Data Analysis & Reporting:
Statistical analyses will compare the stability metrics with patient comfort feedback and final discharge decisions. The goal is to determine if stability in physiological metrics aligns with patient-reported comfort and appropriate discharge decisions.

Operational Challenges:
The trial spans three different hospitals in two countries, so ensuring consistent data collection protocols and equipment calibration is a challenge.

Economic Impact:
Improving recovery protocols and ensuring patients are stable can reduce post-op complications, readmissions, and costs. Hospitals can also optimize bed rotations, impacting the bottom line positively.

End Goal:
Determine if the new post-surgical recovery protocol improves patient physiological stability and comfort, influencing discharge decisions more accurately.



