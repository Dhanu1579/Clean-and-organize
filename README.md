# Clean-and-organize
**Analyze startup investment trends and founder success patterns using Shark Tank India dataset.**

---

## 🎯 Objective
The goal of this project is to analyze **investment trends** from the *Shark Tank India* dataset to uncover:
- 📊 Industry-wise funding distribution  
- 👥 Founder success patterns (team size vs. deal success)  
- 💸 Key investor domains and average funding amounts  

The cleaned data and summary reports are exported for visualization in **Tableau**.

---

## 🧰 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Python (Pandas)** | Data cleaning & aggregation |
| **Excel / CSV** | Data exploration |
| **Tableau Public** | Dashboard visualization |
| **Jupyter Notebook** | Data preparation & export |

---

## ⚙️ Data Preparation Workflow

### **1️⃣ Load & Clean Data**
- Removed ₹ and commas from funding amounts  
- Standardized column names to lowercase with underscores  
- Extracted numeric values for analysis  
- Added a new column `funded_flag` → *True/False* for whether the startup received a deal  

### **2️⃣ Analyze by Domain (Industry)**
Grouped startups by `industry` to calculate:
- Total number of startups  
- Number of funded startups  
- Total and average deal amounts  

### **3️⃣ Analyze Founder Profiles**
Grouped by `number_of_presenters` to compute:
- Total startups per team size  
- Funded startups per team size  
- Success rate = `(funded / total) * 100`

### **4️⃣ Export for Tableau Visualization**
Exported 3 clean CSV files for Tableau:
- **Cleaned_SharkTank_Main.csv** → full dataset  
- **Tableau_Industry_Summary.csv** → industry-level data  
- **Tableau_Founder_Success.csv** → founder success rates  

---

## 📈 Tableau Dashboard Highlights
**Visuals Created:**
- 🧩 Bar chart → *Total Funding by Industry*  
- 📊 Pie chart → *Funded vs. Non-Funded Startups*  
- 👥 Line chart → *Team Size vs. Success Rate*  
- 💡 KPI cards → *Total Startups, Total Funding, Funding Success Rate*  

**Dashboard Features:**
- Interactive filters by Industry and Season  
- Dynamic total investment indicators  
- Exported as **PDF Report**

---

## 📊 Deliverables
| Deliverable | Description |
|--------------|-------------|
| **Visual Dashboard** | Tableau dashboard of trends |
| **Clean Dataset** | Cleaned CSV files for reuse |
| **Founder Success Summary** | Funding rate by team size |
| **PDF Report** | Exported visual dashboard summary |


