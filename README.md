<div align="center">
🏥 Healthcare Analytics & Patient Intelligence
Multi-Platform Business Intelligence & Data Pipeline Suite

MCA AI & ML Invertis University Status Patients Revenue

</div>
🛑 Problem Statement

In most healthcare organizations, patient information is recorded manually or stored across isolated files and basic spreadsheets. Major issues identified include:

Scattered Data: Records are fragmented across multiple files, making centralized tracking difficult.
Lack of Analytical Capabilities: Traditional systems focus solely on record-keeping and registration rather than extracting trends or evaluating hospital performance.
Slow & Manual Reporting: Compiling reports manually is time-consuming, prone to human error, and delays administrative decision-making.
Limited Visibility: Management lacks automated insights into disease distribution, ward utilization, doctor performance, financial metrics, and critical patient ratios.

Solution: This project addresses these gaps by building a multi-platform analytical pipeline using Python, SQL, Microsoft Excel, and Power BI to convert static records into dynamic, interactive visual insights.

🔄 Project Workflow / Flow of Execution
text
[ 1. Raw Data Collection ] 
       │  (5 Domain Excel Files spanning 1,000 synthetic patient records)
       ▼
[ 2. Data Extraction & SQL Integration ] 
       │  (Jupyter Notebook establishes connection with SQL database 'hospital_analytics')
       ▼
[ 3. Data Cleaning & Preprocessing ] 
       │  (Validation checks: 0 missing values, data type formatting, primary key mapping)
       ▼
[ 4. Multi-Platform Modeling & Dashboard Visualization ]
       ├──► Standalone Excel Workbooks & Cost/Revenue Dashboard (Pivot Tables & Slicers)
       ├──► Power BI Interactive Major Dashboard (Custom measure metrics & live filters)
       └──► Python / Jupyter Notebook Automated Visual Suite (Pandas & Matplotlib)
📁 Repository Structure
text
MCA-AI-ML-DATA_ANALYTICS--GROUP-PROJECT-/
│
├── Excel/                                   # 5 domain workbooks (Raw Data + pivots + dashboard) and combined dashboards
│   ├── 1_Hospital_Operation (3).xlsx
│   ├── 2_Patient_Analytics (2).xlsx
│   ├── Disease_Analytics for project (1).xlsx
│   ├── 4_Doctor_Performance (1) (1).xlsx
│   ├── 5_Cost_and_Revenue Project (1).xlsx
│   ├── major dashboard of hospital analytics.xlsx     # all 5 datasets merged on Patient ID
│   └── Cost And Revenue Analysis (1) (1) (1) (1).xlsx # (independently created by me)
│
├── jupyter notebooks/
│   ├── mysql (1) (1).ipynb                  # MySQL connection, database + 5 tables, data load (independently created by me)
│   ├── Hospital_Operations Dashboard.ipynb
│   ├── Patient_Analytics.ipynb
│   ├── Disease_Analytics Dashboard (1).ipynb
│   ├── Doctor Performance Analytics.ipynb
│   ├── Cost And Revenue Dashboards.ipynb
│   └── MAJOR DASHBOARD OF HOSPITAL ANALYTICS.ipynb    # all 5 files merged, one page
│
├── powerbi/
│   └── Major Project Powerbi.pbix           # 6 pages: Operations, Patients, Disease, Doctors, Cost & Revenue, Major Dashboard
│
├── report and ppt/
│   ├── report file iiot.pdf                 # full project report
│   └── Hospital_Analytics_Presentation.pdf  # presentation deck
│
└── README.md
🗄️ MySQL Database (hospital_analytics)
Table	Columns
hospital_operations	patient_id, admission_date, discharge_date, length_of_stay, ward_type, admission_status
patient_analytics	patient_id, age, age_group, gender, city
disease_analytics	patient_id, disease, admission_status, age_group, gender
doctor_performance	patient_id, doctor_name, disease, ward_type, treatment_cost
cost_and_revenue	patient_id, disease, ward_type, treatment_cost, payment_mode
📈 Key Findings
Total revenue ₹39.42 Cr, average ₹3.94 lakh per patient (1,000 patients, 0 missing values).
ICU treats 12.9% of patients but brings in 63.9% of revenue (₹25.20 Cr).
Insurance is the largest payment mode – ₹15.20 Cr (38.6%).
Viral Fever is the most common disease (182 patients) and the top revenue source (₹7.93 Cr).
Dengue has the highest critical share (19.3%).
Dr. Singh (Pulmo) earns the most revenue (₹8.08 Cr); Dr. Verma (Physician) treats the most patients (189).
60+ is the largest age group (32%).
▶️ How to Run
Clone the repo and open the Excel/, powerbi/ and jupyter notebooks/ folders.
Install the Python packages: pip install pandas plotly openpyxl mysql-connector-python matplotlib.
For the MySQL notebook, start a local MySQL server and enter your own credentials when asked. Never commit your password – use getpass.getpass() or an environment variable.
In the dashboard notebooks, set file_path to the matching workbook in Excel/ (for example ../Excel/5_Cost_and_Revenue Project (1).xlsx).
Open Major Project Powerbi.pbix in Power BI Desktop and use the slicers on each page.

Note: the dataset is synthetic (generated for learning); it contains no real patient records.

👥 Team – 03 MCA AI & ML, Invertis University, Bareilly (2026-27)

Devang Bhardwaj (Team Leader), Divyansh Pandey, Ayush Saxena, Nuris Hussain, Mayank Pandey, Shivam Gangwar, Kamalpreet Kaur, Semon Aftab, Gajendra Kumar, Aman Yadav

Guide: Mr. Divyank Chauhan, Assistant Professor, Faculty of CSED
