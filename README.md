# 🏥 Patient Records Management System
### SPARK Academy 2026 | Mini Capstone Project #02

---

## 📖 Project Overview

The **Patient Records Management System** is an interactive Python-based solution designed to help healthcare facilities manage patient data with precision. By leveraging **Object-Oriented Programming (OOP)**, this system transforms static CSV data into a dynamic environment where medical records can be searched, filtered, and analyzed in real-time.

This project was developed as part of the SPARK Academy 2026 curriculum to demonstrate proficiency in:

- **Python Fundamentals** — Logic, loops, and user interaction
- **Object-Oriented Programming** — Class-based software architecture
- **Data Science Libraries** — Pandas for data cleaning; Seaborn and Matplotlib for visualization

---

## ✨ Key Features

- **🔍 Advanced Search:** Instant lookup of patient details by Unique ID or Full Name.
- **🛡️ Data Integrity:** Automated data cleaning using Pandas to handle missing `status` values in the source dataset.
- **📂 Ward Management:** Filter functionality to view all patients assigned to specific hospital sections (e.g., Ward A, ICU).
- **📈 Clinical Analytics:** A built-in dashboard that generates:
  - **Diagnosis Bar Chart:** Visualizes the most common health issues.
  - **Age Demographics:** A histogram showing the age distribution of patients.
  - **Gender Split:** A pie chart illustrating the male-to-female ratio.

---

## 🛠️ Technical Stack

| Component | Details |
| :--- | :--- |
| **Language** | Python 3.x |
| **Data Handling** | Pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Google Colab / GitHub Classroom |

---

## 📂 Project Structure

- **`Patient` Class:** Stores individual patient attributes (ID, Name, Age, Diagnosis, etc.) and handles record formatting.
- **`RecordsManager` Class:** Manages the collection of `Patient` objects and contains the logic for searching and filtering.
- **`load_records()`:** A standalone function that cleans CSV data and prepares the patient database.
- **`show_charts()`:** A visualization module using Seaborn to generate clinical analytics dashboards.

---

## 👥 The Project Team

**Assigned Teams:** Team Nigeria Lagos II | Team Nigeria North West | Team Wakanda

### Coordination & Leadership

| Name | Email | Role |
| :--- | :--- | :--- |
| **Oluwapelumi Solagbade** | solagbadepelumi@gmail.com | Team Coordinator |
| **Bello Abdulbasit Olayemi** | bellobasit790@gmail.com | Teaching Assistant / Support |

### Clinical Research & Analysis

| Name | Email | Role |
| :--- | :--- | :--- |
| **Mkpoikanabasi Obot-Obot** | Emkayobot@gmail.com | Researcher / Clinician |
| **Oloruntoba Joshua Ajayi** | tobajosh1000@gmail.com | Researcher / Clinician |
| **Sarah Ohagu** | ohagusarah@gmail.com | Researcher / Clinician |
| **Happiness Bankole** | bankolehappy@gmail.com | Researcher / Clinician |
| **Abraham Izuchukwu Awamba** | awambaaizu@gmail.com | Researcher / Clinician |
| **Chijioke Kennedy Ibe** | chijiokekennedydominic@gmail.com | Researcher |

### Development & Programming

| Name | Email | Role |
| :--- | :--- | :--- |
| **Glory Onyeche Ejigah** | gloryejigah@gmail.com | Coding & Debugging Programmer |
| **Aisha Olanrewaju** | ishaolan1@gmail.com | Coding & Debugging Programmer |
| **Nimota Opeyemi Yusuf** | nimotaopeyemiyusuf@gmail.com | Coding & Debugging Programmer |
| **Fodilullahi Alao Abdulrasaq** | fodlullah.abdulrasaq@gmail.com | Coding & Debugging Programmer |
| **Toluwalope Ilori** | iloritoluwalope6@gmail.com | Coding & Debugging Programmer |
| **Toyyib Ahmed** | ahmedtoyyib1@gmail.com | Coding & Debugging Programmer |

---

## 🚀 Getting Started

### 1. Prerequisites

Before running the system, install the required Python libraries. Open your terminal or Google Colab and run:
```bash
pip install pandas matplotlib seaborn
```

### 2. Setup & Execution

**Download:** Ensure that `patient_records_management_system.py` and `02_patient_records.csv` are in the same folder.

**Run via Terminal:**
```bash
python patient_records_management_system.py
```

**Run via Google Colab:** Upload both files to the session storage and run this in a code cell:
```python
%run patient_records_management_system.py
```
