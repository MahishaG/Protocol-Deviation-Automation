# Protocol-Deviation-Automation

## 📌 Project Overview
Developed a Python-based web application using Streamlit to automate protocol deviation checks in clinical research records. The system validates study data against predefined rules and displays deviations through an interactive interface, significantly reducing manual effort.
Technologies used: Python Libraries like Streamlit, NumPy, etc
Execution: Python module is run via Visual Studio terminal, which automatically launches a web application for file uploads and processing.
Input: Clinical trial data files (CSV / Excel) containing patient visit information, lab measurements, etc.
The output is an Interactive dashboard displaying deviated records per check.

## 🔗 Technical Approach:
1️⃣ Upload Input Files:
User uploads trial data via Streamlit web interface after the application is launched once the python code runs.
Application reads files and its validated against the protocol checks.

2️⃣ Validation Rules
Each record is checked against predefined rules (example):

Visit within allowed date window
Lab measurement within protocol-defined ranges
Required procedures completed

3️⃣ Python iterates over all uploaded files and all rows, detecting deviations.

## 💻 Output
For each check:
1. Displays all deviated records in tables.
2. Provides sorting/filtering per PatientID or Visit.
3. Optional export for further review.

## Conclusion
Developed a Python-based web application to automate protocol deviation checks by validating clinical trial data against predefined rules, and displaying deviation records through an interactive interface which reduced manual deviation identification by 60%.

## Thank you!!!
