# GISAT_Plus Readme
Overview
GISAT_Plus (Gap Identification System Analysis Tool) is a modern GUI Python application designed for mining health data from the Electronic Medical Record (EMR) system known as the Nigeria Medical Record System (NMRS). Developed as a version of OpenMRS tailored for Nigeria, NMRS is a crucial tool for healthcare data management in the country. GISAT_Plus seamlessly connects to the MySQL engine of NMRS, allowing healthcare professionals to automatically generate patient line lists for detailed reports. With a sleek and intuitive interface, GISAT_Plus empowers users to leverage over 650 patient-level data components for in-depth analysis and reporting.
![image](https://github.com/OluwasolaIdowu645/DataScience-GISAT_Plus/assets/162600317/50966b4c-e404-4585-b36a-7111b82fdb13)

Features
1.	Data Mining: Automatically generates patient line lists for various reports, including:
      •	HIV Treatment Line List: Provides comprehensive data on patients undergoing HIV treatment, including medication regimens, treatment outcomes, and follow-up visits.
      •	HIV Testing Services Line List: Offers insights into HIV testing services, including testing frequency and results, facilitating targeted interventions for HIV prevention and treatment.
      •	Full Pharmacy Complement: Delivers patient-level pharmacy details, including information on the Decentralized Service Delivery Model (DSD) and Multi Month Dispensing (MMD), enhancing medication management and adherence monitoring.
      •	PMTCT Line List (Prevention of Mother to Child Transmission): Focuses on tracking interventions aimed at preventing the transmission of HIV from mother to child, supporting maternal and child health initiatives.
      •	EID Line List (Early Infant Diagnosis): Provides data on early HIV diagnosis in infants, enabling timely intervention and treatment to improve health outcomes.
      •	AHD Line List (Advanced HIV Disease): Offers insights into patients with advanced HIV disease, facilitating targeted healthcare interventions and support services.
      •	LIMS_EMR Daily Report: Compares data from the Laboratory Information Management System with EMR data, enabling comprehensive analysis and quality assurance.
      •	HIV-COVID_19 Line List: Tracks patients affected by both HIV and COVID-19, supporting coordinated healthcare efforts during public health emergencies.
      •	Last 5 Pharmacy: Provides details of the last five drug refills for each patient, aiding in medication management and adherence monitoring.
      •	OTZ Line List (Operation Triple Zero): Focuses on initiatives aimed at achieving zero new HIV infections, zero AIDS-related deaths, and zero discrimination, supporting HIV prevention and treatment programs.
      •	Mobile HTS Tracker: Monitors the usage of Mobile NMRS for HIV testing services, optimizing resource allocation and improving access to healthcare.
      •	NCD Line List (Non-Communicable Diseases): Provides insights into the prevalence and management of non-communicable diseases among patients, supporting comprehensive healthcare delivery.
      •	PBS Line List (Patient Biometrics System): Delivers patient-level biometric details for identification and tracking purposes, enhancing patient care and security.
      •	Client Tracking and Discontinuation: Helps track interruptions in treatment and identify patients at risk of discontinuing healthcare services, supporting continuity of care initiatives.
      •	Regency Standalone List: Offers standalone reports tailored to specific requirements, providing flexibility in data analysis and reporting.
      •	Nutritional Status List: Provides data on the nutritional status of patients, facilitating targeted interventions and support services.
  	![image](https://github.com/OluwasolaIdowu645/DataScience-GISAT_Plus/assets/162600317/f0d6f3e7-ca94-487e-a570-8755735f9887) ![image](https://github.com/OluwasolaIdowu645/DataScience-GISAT_Plus/assets/162600317/57932e5c-8e75-4def-a67d-d4795bc974be)

3.	Database Connectivity: Utilizes SQL Stored procedures created using Python libraries such as sqlalchemy, mysql.connector, and pymysql to interact with the MySQL engine of NMRS, ensuring efficient data retrieval and processing.
4.	Data Security: Ensures health data security and confidentiality by fetching extracted data into an encrypted Excel workbook using Python libraries like pandas, openpyxl, and win32com.client, safeguarding sensitive patient information.
5.	Error Detection: Detects data errors and inconsistencies, such as incomplete data and missing fields, enhancing data quality and reliability for informed decision-making in healthcare delivery.![image](https://github.com/OluwasolaIdowu645/DataScience-GISAT_Plus/assets/162600317/2eb98f75-ea7b-461e-8c60-de7c7db9462c)
6.	Data Integration: Capable of merging patient-level data across different health facilities, local governments, and states, facilitating comprehensive data analysis and reporting for improved healthcare outcomes.

![image](https://github.com/OluwasolaIdowu645/DataScience-GISAT_Plus/assets/162600317/5f78a49e-feb0-426b-94e3-892c65d01a5f)

Data Components of Each Line List
Each line list generated by GISAT_Plus comprises detailed patient-level data components tailored to specific healthcare needs, including:
  •	Demographic information (e.g., age, gender, location)
  •	Clinical indicators (e.g., diagnosis date, treatment regimen)
  •	Laboratory results (e.g., viral load measurements, CD4 cell count)
  •	Medication details (e.g., drug refills, adherence indicators)
  •	Service utilization (e.g., follow-up visits, testing frequency)
These data components provide valuable insights into patient demographics, disease progression, treatment outcomes, and healthcare service utilization, enabling healthcare professionals to make informed decisions and improve patient care effectively.
Getting Started
To get started with GISAT_Plus:
1.	Clone or download the project repository from GitHub: GISAT_Plus Repository.
2.	Install the required Python libraries using pip:
Copy code
pip install sqlalchemy mysql-connector-python pymysql pandas openpyxl pypiwin32 
3.	Configure database connection settings in the application.
4.	Launch the application using Python:
Copy code
python gisat_plus.py 
5.	Select the desired patient line list from the available options and explore the generated reports.
Getting Help
For assistance or support with GISAT_Plus, please visit the project repository on GitHub and open an issue: GISAT_Plus Issues.
Maintenance and Contributions
GISAT_Plus is maintained and contributed to by Oluwasola Idowu, affiliated with the Centre for Integrated Health Program (CIHP), PHIS3, and the Centers for Disease Control and Prevention (CDC). Contributions from the community are welcome, and interested individuals can fork the repository, make changes, and submit pull requests for review and integration into the project.
