# HEALTH-PATIENT-DASHBOARD
Introduction
Hospital management needs a clear, data-backed view of how the hospital is performing. This project uses Microsoft Excel to analyse 1,000 patient records from Secure Life General Hospital (January 2024 to December 2025) and presents the results in an interactive dashboard.
The dashboard tracks patient volumes, billing, length of stay, insurance coverage and payment status, so management can spot trends and make better decisions.


About the Dataset
The dataset (Hospital_Patients_Dataset.xlsx) holds 1,000 patient admission records with 11 columns and no missing values or duplicate Patient IDs:
•	Patient details: Patient ID, Patient Name, Age, Gender
•	Admission details: Admission Date, Discharge Date, Department, Diagnosis
•	Billing details: Total Bill Amount, Insurance Coverage %, Payment Status (Paid, Partially Paid, Pending)
The following fields were calculated during analysis:
•	Length of Stay = Discharge Date minus Admission Date (in days)
•	Paid Amount = total of bills with a Paid status
•	Age Group and Admission Month, used to group patients and show trends
If you built Paid Amount or the age groups differently in your workbook, edit these lines to match.
Problem Statement
Management at Secure Life General Hospital wants answers to questions such as:
•	How many patients were admitted, and how does admission volume change over time?
•	Which departments and age groups handle the most patients?
•	How much was billed, and how much has actually been paid?
•	What share of patients are insured?
•	How long do patients stay on average?
•	What is the split of payment status across patients?
Compare this list with your Data Dictionary & Problem Statement PDF and swap in the exact questions.
Visualization
The dashboard below summarises the hospital's performance.
Insert your Dashboard_Image screenshot here (Insert > Pictures).
Insights
•	Volume: The hospital admitted 1,000 patients over two years, 508 in 2024 and 492 in 2025. Admissions peaked at 57 in November 2025 and dipped to 29 in June and August 2025.
•	Billing: Total billing was $8,053,143, and $4,568,527 (56.7%) has been paid. The other $3,484,616 is still outstanding: $2,082,786 pending and $1,401,830 partially paid.
•	Payment status: 56.4% of patients have paid in full, 25.7% are pending and 17.9% are partially paid.
•	Length of stay: The average stay is 4.8 days. Orthopedics has the longest stay (8.4 days) and Emergency the shortest (2.0 days).
•	Insurance: Average insurance coverage is 75%. 95.6% of patients have some cover, and 44 patients have none.
•	Departments: General treats the most patients (252), followed by Emergency (190), Orthopedics (159), Pediatrics (153), Cardiology (152) and Neurology (94).
•	Revenue: Orthopedics ($2.55M), Cardiology ($2.10M) and Neurology ($1.22M) bring in 72.8% of all billing while treating only 40.5% of patients. Their average bills are $16,062, $13,786 and $12,929, against under $4,000 for General, Emergency and Pediatrics.
•	Age: Patients aged 51 and above make up 46.7% of admissions (51-65: 235, over 65: 232). The 36-50 group has 210, the 19-35 group 166 and those 18 and under 157.
•	Gender: The split is almost even, 512 female (51.2%) and 488 male (48.8%).
•	Diagnosis: Pneumonia is the most common diagnosis (43 patients), followed by Gastritis (39) and Dehydration (38).

