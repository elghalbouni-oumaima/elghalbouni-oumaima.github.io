# 📊 Data Engineering Portfolio

## 📌 About Me

I am a **Data Engineering student** focused on building **scalable data systems, real-time pipelines, and analytics platforms**.

My work centers around:

* Designing **data pipelines (batch & streaming)**
* Processing large-scale data using **Big Data tools**
* Applying **machine learning for data-driven insights**
* Building **data platforms for real-world use cases**

---

## 🚀 Core Skills

### ⚙️ Data Engineering

* ETL / ELT Pipelines
* Data Modeling
* Data Warehousing
* Stream Processing
* Batch Processing
* Query Optimization

### 🔥 Big Data Stack

* Apache Kafka
* Apache Flink
* Apache Spark (PySpark)
* Cassandra
* MinIO (Data Lake)

### 📊 Data & ML

* Pandas, NumPy
* Machine Learning (Spark MLlib)
* Feature Engineering
* Time Series & Forecasting

### 🛠️ Tools

* SQL (Advanced)
* Power BI, Grafana
* Docker
* Linux

---

## 📂 Featured Projects

---

### 🚖 TaaSim — Urban Mobility Data Platform

**Real-time mobility platform powered by Big Data & Machine Learning**

#### 📌 Problem

Urban transportation systems suffer from:

* Inefficient vehicle allocation
* Demand-supply imbalance
* Lack of predictive insights

#### 💡 Solution

TaaSim is a **real-time data platform** that:

* Streams GPS and trip data
* Matches riders with vehicles
* Predicts future demand using ML

---

#### 🧠 Architecture (Kappa)

* **Single source of truth:** Kafka
* **Processing:** Apache Flink (real-time + replay)
* **Batch & ML:** Apache Spark
* **Storage:** Cassandra + MinIO

> No Lambda complexity — unified streaming architecture

---

#### 🔄 Data Pipeline

* Producers → GPS + Trip events
* Kafka Topics → `raw.gps`, `raw.trips`
* Flink Jobs → normalization, aggregation, matching
* Storage → Cassandra (serving) + MinIO (data lake)

---

#### 🚀 Key Features

* Real-time vehicle tracking
* Low-latency trip matching (< 5s)
* Demand heatmaps per zone
* ML-based demand forecasting
* Live monitoring with Grafana

---

#### 📊 Machine Learning

* Model: Gradient Boosted Trees (Spark MLlib)
* Predicts demand **30 minutes ahead**
* Uses:

  * Time features
  * Historical demand
  * Zone data
  * Weather

---

---

### 🧠 JobIntelligent — Data Platform

**End-to-end data pipeline for job market intelligence**

#### 📌 Objective

Build a system that transforms raw job postings into **structured, analyzable insights**.

#### 🔄 Pipeline

* Data ingestion (job listings)
* Data cleaning & transformation
* NLP processing (semantic matching)
* Visualization in Power BI

#### 🚀 Features

* Semantic job matching using NLP
* Skill extraction & classification
* Market trend analysis
* Interactive dashboards

---
---

### 📈 Query Performance Optimization

**Database performance engineering project**

#### 📌 Focus

* Query optimization techniques
* Use of **Views & Materialized Views**
* Execution plan analysis (EXPLAIN)

#### 🎯 Goal

Improve query performance for analytical workloads.

---

## 📚 Education

🎓 Bachelor's Degree in **Data Engineering**

---

## 📈 Interests

* Real-time Data Systems
* Distributed Architectures
* Data Platforms & Infrastructure
* Machine Learning for Data Systems

---

## 📫 Contact

<p align="left">
<a href="https://github.com/elghalbouni-oumaima" target="blank">
<img src="https://skillicons.dev/icons?i=github" height="40"/>
</a>
<a href="https://linkedin.com/in/el-ghalbouni-oumaima-a73a26331" target="blank">
<img src="https://skillicons.dev/icons?i=linkedin" height="40"/>
</a>
</p>

---

## 🌐 Portfolio 
- 👨‍💻 Portfolio: [Visit my website](https://elghalbouni-oumaima.github.io/)
- 📄 CV: [View Resume](https://drive.google.com/file/d/18_r9ssD6idLFMkZjq8jJq5-j7sI-yGOS/view?usp=sharing)
- 📫 Email: **elghalbouniomaima@gmail.com**
## ⭐ Career Goal

To become a **Data Engineer specialized in real-time and large-scale data systems**, building platforms that transform raw data into actionable insights.
