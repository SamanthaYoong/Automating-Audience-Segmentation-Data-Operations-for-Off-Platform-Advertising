#  Case Study: Automating Audience Segmentation & Data Operations for Off-Platform Advertising

## 🎯 Context
While supporting a digital retail media team, I saw the **audience-building workflow** for off-platform campaigns relied heavily on **manual SQL queries and CSV handoffs**.  
This slowed down campaign turnaround and created opportunities for error.  

I focused on:
- **Streamlining segmentation with SQL**, and  
- Using **basic Python/Pandas** for **mock data generation** and **light data prep** — without full automation or scripting.

---

## 📌 Objectives
- ✅ **Cut down manual effort** by creating reusable **SQL templates**.  
- ✅ **Improve consistency** by standardizing query logic for marketing audience requests.  
- ✅ Experiment with **basic Python/Pandas** for dataset prep and future automation readiness.

---

## 📌 Approach

### 1️⃣ SQL for Audience Segmentation (Snowflake/BigQuery)
- Wrote **parameterized SQL templates** for common segments (e.g., *frequent shoppers who purchased a category in the last 30 days*).  
- Optimized queries with **CTEs and partitions** to handle **20M+ rows**, reducing runtime by ~35%.  
- Added simple **QA queries** (e.g., audience counts check) to prevent delivery errors.

### 2️⃣ Python/Pandas for Data Prep
- Used **Pandas** for **mock data generation** (to test segmentation logic before real campaigns).  
- Performed **basic file cleanup**: reshaping tables, merging test datasets, and formatting CSV outputs.  
- No full automation — just **concept testing** for where automation could help in the future.

### 3️⃣ Cross-Functional Collaboration
- Worked with **ads ops & product** to define reusable **audience “building blocks.”**  
- Shared SQL templates with teammates to speed up future campaign requests.  
- Flagged tasks that **engineers could automate later** based on observed bottlenecks.

---

## 📌 Key Results
✅ **40% fewer manual SQL query requests** for audience-building.  
✅ **Turnaround time** for custom segments dropped from ~3 days to **same-day delivery** for 70% of requests.  
✅ Established **clear structure** for **future automation** without overengineering.

---

## 📌 Tools & Skills Used
- **SQL (BigQuery)** – Primary tool for segmentation, query optimization, QA checks  
- **Python (Pandas)** – Used for **mock data generation & simple cleanup**, not automation  
- **Collaboration & process thinking** – Identified where automation could fit, even if I didn’t build it yet

---

## 📌 Why This Matters for Instacart
This case study shows:
- ✅ **SQL is my operational backbone** for audience building.  
- ✅ I can **use Python at a basic level** for testing/cleaning datasets.  
- ✅ I understand **where automation is needed** — and can work with engineers when the time comes.

I can **run daily SQL-driven workflows immediately** at Instacart and **grow my Python skillset on the job** to support future automation.
