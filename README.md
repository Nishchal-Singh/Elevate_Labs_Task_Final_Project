# Elevate_Labs_Task_Final_Project

# 🧠 HR Analytics – Predicting Employee Attrition

**Author:** Nishchal Singh  
**Role:** Data Analyst Intern @ Elevate Labs  

---

## 📘 Overview
This project focuses on **understanding and predicting employee attrition** using the **IBM HR Analytics dataset**.  
The goal is to identify the **key drivers of employee turnover** and provide **data-driven strategies** to enhance retention, improve workforce satisfaction, and reduce human capital risks.

---

## 🎯 Objectives
- Analyze employee data to uncover attrition trends and patterns  
- Build a **predictive machine learning model** to identify high-risk employees  
- Visualize insights through an interactive **Power BI dashboard**  
- Provide actionable recommendations for HR strategy and decision-making  

---

## 📊 Key Highlights

| Metric | Value |
|---------|--------|
| **Total Employees** | 1,470 |
| **Employees Who Left** | 237 |
| **Overall Attrition Rate** | 16% |
| **Average Monthly Income** | $6,500 |
| **Average Tenure** | 6.8 years |
| **Model Accuracy (Random Forest)** | 91% |

---

## 🧩 Data & Tools Used

**Dataset:** IBM HR Analytics Employee Attrition Dataset  

**Tech Stack:**
- 🐍 **Python:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, SHAP  
- 📊 **Power BI:** Interactive dashboard for visualization  
- 🤖 **Machine Learning Models:** Random Forest, Logistic Regression  
- 💬 **Explainability:** SHAP for feature importance and interpretability  

---

## 🔍 Data Storytelling Flow

### 1️⃣ How Big Is the Problem?
- Attrition rate: **16%**, exceeding the industry benchmark (10–12%)  
- Highest attrition observed in **Sales** and **Human Resources** departments  

### 2️⃣ Where Is It Happening?
- **High-turnover roles:** Sales Executives, Lab Technicians, HR Associates  
- **Tenure group:** Employees with **2–4 years** experience most likely to leave  

### 3️⃣ Why Is It Happening?
**Top predictors (from SHAP analysis):**
- OverTime  
- Monthly Income  
- Years Since Last Promotion  
- Job Level  
- Age  
- Environment Satisfaction  
- Job Role  

**Key Findings:**
- Employees earning **< $5,000/month** are 2.5× more likely to leave  
- Lack of promotion within **3–5 years** increases attrition risk  
- Regular overtime significantly impacts retention  

### 4️⃣ What Can We Do? – *Actionable Recommendations*
- 🚀 **Career Mobility Program:** Promotion cycles every 3 years  
- ⚖️ **Work–Life Balance:** Limit overtime & introduce stress monitoring tools  
- 💰 **Compensation Benchmarking:** Align lower salary bands with market rates  
- 👥 **Early Engagement:** Mentorship for employees with <2 years tenure  
- 🤖 **Predictive Retention Dashboard:** Integrate ML model into HR systems  

---

## 📈 Dashboard Preview

An interactive **Power BI Dashboard** visualizes:
- Attrition by department, job role, age, and gender  
- Correlations between income, tenure, and attrition  
- Key workforce metrics and KPIs  

📄 *See file:* `Dashboard IBM Hr Analytics.pdf`

---

## 🧠 Model Performance

| Metric | Value |
|---------|--------|
| **Algorithm** | Random Forest |
| **Accuracy** | 91% |
| **Evaluation Metrics** | Precision, Recall, F1-Score |
| **Explainability** | SHAP values (feature-level interpretation) |

---

## 💼 Business Impact

By acting on these insights, the organization can:
- Reduce **turnover costs by 20–25% annually**  
- Improve **employee engagement and retention**  
- Transition HR operations from **reactive** to **predictive** management  

---

## 📂 Repository Structure

├── python_code.ipynb # Data analysis & model building
├── HR_Analytics_Attrition_Report.pdf # Detailed analytical report
├── Dashboard IBM Hr Analytics.pdf # Power BI dashboard snapshot
├── README.md # Project documentation (this file)

## 🏆 Acknowledgments
Special thanks to **Elevate Labs** for guidance and providing the dataset for this project.  

## 📫 Contact
📧 **Email:** [nishchalsingh@example.com](mailto:nishchalsingh@example.com)  
🌐 **LinkedIn:** [linkedin.com/in/nishchal-singh](https://linkedin.com/in/nishchal-singh)  

---

⭐ *If you found this project helpful, consider giving it a star on GitHub!*
