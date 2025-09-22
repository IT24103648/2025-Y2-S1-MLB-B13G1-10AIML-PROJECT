Overview of the Project
This project, undertaken by Group ID 2025-Y2-S1-MLB-B13G1-10 at the Sri Lanka Institute of Information Technology (SLIIT) for the Artificial Intelligence and Machine Learning course (IT2011, Year 2, Semester 1 - 2025), focuses on the early identification of at-risk students in secondary education to enable timely academic interventions. The real-world problem domain highlights that approximately 30% of students fail to meet minimum grade requirements in secondary education, as reported by the OECD in 2024. Early intervention through predictive modeling is proposed as a solution to improve student outcomes.
The primary goal is to develop a machine learning (ML) model that predicts final grades (G3) based on key inputs, including:

Past academic performance (G1 and G2 grades)
Attendance (absences)
Study habits (study time and parental education)

The model takes inputs such as study time and absences, processes them through an ML algorithm, and outputs a grade prediction. This approach aims to support educators in identifying students who may need additional support, drawing from a combination of academic, demographic, social, and lifestyle factors.
Dataset Details
The chosen dataset is the "Student Performance" dataset sourced from the UCI Machine Learning Repository. It consists of tabular data with the following specifications:

Overview: Data on 649 students, combined from two subsets (Mathematics: 396 records; Portuguese: 650 records), resulting in a total of 1,046 records.
Features: 33 attributes, categorized into:

Academic: Study time, absences.
Demographic: Age, gender.
Social: Family size, family support.
Lifestyle: Internet access, health status.


Target Variable: Final grade (G3).
Additional Attributes: Includes grades (G1, G2, G3), age, study time, and absences as key predictors.
