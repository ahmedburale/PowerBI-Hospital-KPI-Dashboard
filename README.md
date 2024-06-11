# Clinical Business Intelligence Portfolio

## Introduction to the KPIs

### Overview
This project focuses on building a Clinical Business Intelligence dashboard using Power BI. The key performance indicators (KPIs) included are crucial for healthcare organizations to monitor and improve patient outcomes. 

### Key Performance Indicators

1. **Average Time to See Healthcare Provider**: 
   - Definition: The average elapsed time between patient admission and seeing a healthcare provider.
   
2. **Patient Satisfaction**:
   - Definition: A score provided by patients rating their care on a scale from 1 (very unsatisfied) to 5 (very satisfied).

3. **Patient Readmission Rate**:
   - Definition: The number of patients readmitted within 30 days divided by the total number of patients admitted within the same period.

4. **Average Hospital Length of Stay**:
   - Definition: The average elapsed time between patient admission and discharge.

Each healthcare organization can set its target values for these KPIs based on its specific context, location, and size.

### Importance of KPIs
These KPIs provide a holistic view of organizational performance, helping to drive improvements in patient care and outcomes.

### Dataset
The dataset used in this project consists of synthetic dummy data. You can follow along using the provided dataset or use other open-source datasets.

### Data Cleaning
1. **Loading Data**:
   - Open Power BI Desktop and go to "Get Data" to load the Excel workbook.
   - Instead of selecting "Load," choose "Transform" to launch the Power Query editor.

2. **Transforming Data**:
   - Use the built-in Age function in Power Query to calculate age from the Patient Date of Birth and today's date.

### How to Run
1. Clone the repository:
   ```sh
   git clone (https://github.com/ahmedburale/PowerBI-Hospital-KPI-Dashboard.git)
