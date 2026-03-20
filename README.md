# 🏥 Patient Records Management System
### SPARK Academy 2026 | Mini Capstone Project #02

---

## 📖 Project Overview
The **Patient Records Management System** is an interactive Python-based solution designed to help healthcare facilities manage patient data with precision. By leveraging **Object-Oriented Programming (OOP)**, this system transforms static CSV data into a dynamic environment where medical records can be searched, filtered, and analyzed in real-time.

This project was developed by our team as part of the SPARK Academy 2026 curriculum to demonstrate proficiency in:
* **Python Fundamentals** (Logic, loops, and user interaction)
* **Object-Oriented Programming** (Class-based architecture)
* **Data Science Libraries** (Pandas for cleaning, Seaborn/Matplotlib for visualization)

---

## ✨ Key Features
* **🔍 Advanced Search:** Instant lookup of patient details by searching their Unique ID or Full Name.
* **🛡️ Data Integrity:** Automated data cleaning using Pandas to handle missing `status` values in the source dataset.
* **📂 Ward Management:** Filter functionality to view all patients assigned to specific hospital sections (e.g., Ward A, ICU).
* **📈 Clinical Analytics:** A built-in dashboard that generates:
    * **Diagnosis Bar Chart:** Visualizes the most common health issues.
    * **Age Demographics:** A histogram showing the age distribution of patients.
    * **Gender Split:** A pie chart illustrating the male-to-female ratio.

---

## 🛠️ Technical Stack
* **Language:** Python 3.x
* **Data Handling:** Pandas
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / GitHub Classroom

---

## 📂 Project Structure
* **`Patient` Class:** Stores individual patient attributes (ID, Name, Age, Diagnosis, etc.) and handles record formatting.

* **`RecordsManager` Class:** Manages the collection of `Patient` objects and contains the logic for searching and filtering.
* **`load_records()`:** A standalone function that cleans data and prepares the database.
* **`show_charts()`:** A visualization module using Seaborn to generate clinical insights.

---

## 👥 The Project Team
**Assigned Teams:** Team Nigeria Lagos II | Team Nigeria North West | Team Wakanda

### Coordination & Leadership
| Name | Email | Role |
| :--- | :--- | :--- |
| **Oluwapelumi Solagbade** | solagbadepelumi@gmail.com | Team Coordinator |
| **Bello Abdulbasit Olayemi** | bellobasit790@gmail.com | TA / Support |

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
| **Toluwalope Ilori Ilori** | iloritoluwalope6@gmail.com | Coding & Debugging Programmer |
| **Toyyib Ahmed** | ahmedtoyyib1@gmail.com | Coding & Debugging Programmer |

---

## 🚀 Getting Started

### 1. Prerequisites
To install the required libraries, run:
```bash
pip install pandas matplotlib seaborn
