# 🧠 Human Resources Analytics Dashboard (Tableau + Python)

![Dashboard Preview]<img width="1390" height="797" alt="Screenshot 2025-07-29 at 7 20 57 PM" src="https://github.com/user-attachments/assets/a4cf938c-f974-4da8-873c-4605aae3ee75" />


This project combines **data science + business intelligence** to simulate, clean, and visualize a realistic HR dataset of **8,950 employees**. The goal was to equip HR stakeholders with a decision-making dashboard, built entirely using **Python for data generation** and **Tableau for visual analytics**.

---

## 🔍 Project Overview

As an HR manager, it's essential to monitor workforce trends, performance, hiring gaps, and salary equity. This dashboard answers key questions like:
- How many employees are active, hired, or terminated each year?
- What are the salary patterns across departments and genders?
- Are performance ratings influenced by education or location?
- What’s the demographic breakdown of the workforce?

---

## ⚙️ Data Generation with Python (Faker)

Instead of using prebuilt datasets, I **generated a realistic synthetic dataset** using Python, `Faker`, and custom logic.  
**Key features of the dataset**:

| Feature | Logic Applied |
|--------|---------------|
| `Employee_ID` | Unique 10-digit identifier |
| `Location` | Assigned based on 8 U.S. states and 24 cities with real-world probability distribution |
| `Department & Job Title` | Randomly assigned with realistic ratios |
| `Education Level` | Mapped based on role seniority and title |
| `Hire & Termination Dates` | Assigned with controlled gaps and probabilities |
| `Salary` | Calculated dynamically based on age, education, gender multipliers, and job title |
| `Performance Rating` | Probability-distributed among 4 categories |
| `Birthdate & Age` | Derived from realistic age ranges depending on job level |

➡️ View the full code in [`generate_hr_dataset.py`](./generate_hr_dataset.py)

---

## 📊 Dashboard Features (Tableau)

Built using **Tableau**, the dashboard contains 3 sections:

### 1. Overview
- Total hires, active employees, terminations
- Year-wise hiring/termination trends
- Department-wise employee distribution
- City-wise and HQ vs. branch comparison

### 2. Demographics
- Gender ratio across departments
- Age group segmentation
- Education level analysis
- Education vs. performance correlation

### 3. Income Analysis
- Salary trends by gender and education
- Age vs. salary patterns across departments

---

## 📁 Files in the Repo

| File | Description |
|------|-------------|
| `generate_hr_dataset.py` | Python script to generate HR data with 8,950 records |
| `HR Dashboard.twbx` | Packaged Tableau dashboard file |
| `dashboard.png` | Static screenshot for preview |
| `README.md` | You’re reading it 👀 |

---

## 💡 Skills Demonstrated

- Python (Faker, NumPy, Pandas, custom logic)
- Data cleaning, formatting, feature engineering
- Tableau (KPIs, filters, dashboards, bar/pie/line/box plots)
- Analytical thinking from both HR and data perspectives

---

## 🔥 Why This Matters

Instead of relying on prebuilt datasets, this project shows that I can:
- Build realistic business data with custom constraints
- Clean and transform data programmatically
- Create meaningful visualizations tailored to stakeholders
- Bridge the gap between **data engineering**, **analytics**, and **storytelling**

---

## 📬 Contact

**Vansh V**  
💼 [LinkedIn](https://www.linkedin.com/in/your-link-here)  
📧 your.email@example.com  
