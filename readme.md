# Projek Freedom Open Source – Exploring dbt Core & Trino for DWH Transformation

![Alt text](https://github.com/projekdos/elt_workshop_dbt_trino_batch1/blob/main/image/header.jpeg)

This hands-on technical workshop is prepared by:
- **Theodorus Widhi** https://www.linkedin.com/in/theodorus-widhi-9a54111a3/
- **Wandhana Kurnia** https://www.linkedin.com/in/wandhanakurnia/

---

## Workshop Information

**Title:**  
**Exploring dbt Core and Trino for DWH Transformation**

**Date:** 
28 December 2025  
2:00 PM – Finish

**Session Theme:**  
Technical closing session for **2025** and a solid foundation to start a **2026 analytics roadmap** using modern open-source data stack.

---

## Workshop Objective

![Alt text](https://github.com/projekdos/elt_workshop_dbt_trino_batch1/blob/main/image/conceptual-design-dwh.png)

This workshop focuses on **practical implementation** of a modern **Data Warehouse transformation workflow** using **dbt Core** and **Trino** as the main engine.

Participants learn how to:
- Transform raw operational data into analytics-ready datasets
- Apply dimensional modeling best practices
- Build scalable SQL-based transformations
- Design a reliable data warehouse as a **single source of truth**

All sessions are **free**, hands-on, and fully based on **open-source tech stack**.

---

## Topics Covered

- PostgreSQL as raw operational data source
- Trino as distributed SQL query engine
- dbt Core fundamentals and project structure
- SQL-based data transformation with dbt models
- Project Quiz

---

## Architecture Overview

**High-level architecture used in this workshop:**

- **Source Layer:** PostgreSQL (OLTP)
- **Query Engine:** Trino
- **Transformation Layer:** dbt Core
- **Modeling Approach:** Fact & Dimension, & Datamart

---

## Case Study

### 🚚 Shipment & Logistics Analytics

The case study will guide participants from **raw data ingestion** to **final data mart**.

![Alt text](https://github.com/projekdos/elt_workshop_dbt_trino_batch1/blob/main/image/preview-dbt.png)

![Alt text](https://github.com/projekdos/elt_workshop_dbt_trino_batch1/blob/main/image/preview-schema-trino.png)

---

## 🧠 Hands-on Activities

- Create dbt models (staging, dimension, fact, datamart)
- Run dbt transformations using Trino

---

## 🧪 QUIZ – Data Warehouse Transformation Challenge

### **Overview**
You act as Data Engineering, and will be provided with a **Retail Business - MySQL dataset** and a partially built dbt project.

### **Step**
- Pre-requisites: Install MySQL, dbt, Trino in your local environment
- Download Sample Data (refer to quiz/data_sample_url.txt)
- Import in your MySQL Server
- Create Catalog Trino to MySQL
- Read the mapping by Business Analyst in quiz/DWH-Mapping.xlsx
- build modeling DWH with dbt & trino based on DWH-Mapping.xlsx
- Wrap in Orchestrator tools is a plus+ (mage.ai, apache airflow, prefect, & more)

### **Deliverables**
1. dbt model structure (stg, dim, fact, mart)
2. SQL logic for SCD
3. Successful dbt run result
4. Publish Short explanation of modeling decisions in Github/Slide

There is no single correct answer — the focus is on **clarity, correctness, and best practices**.

---

## Perfect For

This workshop is suitable for:
- Fresh Graduates
- Data Engineers
- Analytics Engineers
- Data Analysts

---

## 🤝 Partnership & Collaboration

**Contact:**
- Email: contact@projekdos.com, projek.freedomopensource@gmail.com
- Website: https:///www.projekdos.com
- LinkedIn: https://www.linkedin.com/company/projek-dos/
- Discord: https://discord.com/invite/zvvBv7pyUh
- Instagram: https://www.instagram.com/projekdos/
- YouTube Series: https://www.youtube.com/watch?v=flq6xhWlbYk&list=PLBhEeg5qlN83MrEJSKNRcpdCt7HhUH7UV

![Alt text](https://github.com/projekdos/elt_workshop_dbt_trino_batch1/blob/main/image/projeckDos2-fullcolor-white.png)