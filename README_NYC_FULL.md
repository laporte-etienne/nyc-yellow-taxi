
# 🚖 NYC Yellow Taxi Trips – Data Engineering Project

This repository contains a complete data engineering pipeline for collecting, transforming, and analyzing NYC Yellow Taxi trip data. This project was built while following a course on Udemy by Josué Afouda, and serves as a hands-on implementation of a real-world big data use case.

---

## 🧾 Project Description

The **NYC Yellow Taxi Trips** project is a full-stack data engineering workflow designed to work with large-scale Parquet datasets provided by New York City's Taxi & Limousine Commission (TLC). The project involves collecting trip data, transforming and cleaning it, running exploratory analysis, and optionally preparing it for BigQuery or machine learning pipelines.

---

## 🎯 Objectives

- 🔽 Download raw `.parquet` data files directly from TLC cloud storage
- 🔧 Clean and transform columns (convert timestamps, calculate trip duration, etc.)
- 📊 Perform EDA (Exploratory Data Analysis) using Jupyter Notebooks
- 📦 Store data in a structured format for further processing
- (Optional) Load into BigQuery or orchestrate with Airflow/Prefect

---

## 🧰 Tools and Technologies

- **Python**
- **Pandas / PyArrow**
- **Parquet**
- **Jupyter Notebooks**
- **BigQuery** (optional)
- **Airflow / Prefect** (optional)

---

## 📂 Project Structure

```
nyc-yellow-taxi-trips/
├── data/                      # Raw and processed data (excluded from repo)
├── notebooks/                # Jupyter Notebooks (EDA, transformations)
├── scripts/                  # Python scripts for ingestion/transformation
├── queries/                  # SQL queries for BigQuery (optional)
├── requirements.txt          # Required Python libraries
└── README.md
```

---

## 📌 Key Features

- Dynamic download of monthly `.parquet` taxi trip files
- Efficient storage and processing with PyArrow
- Clear modular structure to support workflow automation
- Notebooks include trip duration statistics, filtering, grouping, and basic visualizations

---

## 📚 Based On

This project was developed by following this Udemy course:

- **Course**: [Become a Data Engineer – NYC Yellow Taxi Pipeline](https://www.udemy.com/course/data-engineering-zoomcamp-nyc-taxi/)
- **Instructor**: [Josué Afouda](https://github.com/JosueAfouda)

---

## 📦 Installation

```bash
git clone https://github.com/etiennelaporte/nyc-yellow-taxi-trips.git
cd nyc-yellow-taxi-trips
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Etienne Laporte**  
Engineer & Data Automation Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/etiennelaporte)

---

## 📜 License

MIT License – free to use and adapt with attribution.
