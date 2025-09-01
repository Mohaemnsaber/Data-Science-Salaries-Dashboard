# Data Science Salaries Dashboard

## 📌 Project Overview
This project visualizes global salary trends in the Data Science field using the **`ds_salaries` dataset**.  
The dataset contains **3,755 job records** with information on salaries, job titles, experience levels, company size, remote work, and locations.  
The dashboard was built in **Power BI** to provide insights into salary distributions, trends, and workforce characteristics.

---

## 📊 Dataset Information
**Source:** ds_salaries.xlsx  
**Rows:** 3,755  
**Columns:** 11  

| Column              | Description |
|---------------------|-------------|
| `work_year`         | The year of the data record |
| `experience_level`  | Employee experience level (EN, MI, SE, EX) |
| `employment_type`   | Full-time, Part-time, Contract, etc. |
| `job_title`         | Role of the employee (e.g., Data Scientist, ML Engineer) |
| `salary`            | Salary in local currency |
| `salary_currency`   | Currency code (e.g., USD, EUR) |
| `salary_in_usd`     | Standardized salary in USD |
| `employee_residence`| Country of residence of the employee |
| `remote_ratio`      | % of remote work (0 = On-site, 50 = Hybrid, 100 = Remote) |
| `company_location`  | Country where the company is located |
| `company_size`      | Size of the company (S = Small, M = Medium, L = Large) |

---

## 📈 Dashboard Features
The Power BI dashboard includes:

1. **KPI Cards**
   - Average Salary (USD)
   - Maximum Salary (USD)
   - Total Number of Records

2. **Charts**
   - **Line Chart:** Average salary trend over time (`work_year` vs Avg `salary_in_usd`)
   - **Bar Chart:** Average salary by job title (Top roles)
   - **Bar Chart:** Average salary by experience level (`experience_level`)
   - **Map:** Geographic salary analysis by company location
   - **Donut Chart:** Distribution of remote work (`remote_ratio`)
   - **Bar Chart:** Average salary by company size
   - **Bar Chart:** Number of employees by company location

---

## 🚀 How to Use
1. Open the Power BI `.pbix` file or recreate the dashboard using the dataset.
2. Use slicers/filters (e.g., year, job title, location) to interact with the visuals.
3. Gain insights into:
   - Salary differences across roles
   - Impact of experience on salary
   - Remote work adoption trends
   - Salary variations by geography and company size

---

## 📂 Project Structure
📁 Data Science Salaries Dashboard
├── ds_salaries.xlsx # Dataset
├── dashboard.pbix # Power BI dashboard file
└── README.md # Project documentation


---

## 🛠 Tools & Technologies
- **Power BI** → Data visualization & dashboard building  
- **Excel / Python (optional)** → Data cleaning and exploration  

---

## 📌 Insights from the Dashboard
- Senior-level employees (SE/EX) earn significantly higher salaries than entry-level.  
- Remote work (100%) is the most common arrangement.  
- The United States dominates in number of employees and highest salaries.  
- Larger companies tend to offer higher salaries compared to small and medium-sized firms.  

---

## 📧 Contact
**Author:** Mohaemn Saber  
**Email:** mohaemn.saber@gmail.com  
**Location:** Cairo, Egypt  


