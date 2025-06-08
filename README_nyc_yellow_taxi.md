
# 🚖 NYC Yellow Taxi Trips – Data Engineering Project

This project is a complete data engineering pipeline for processing, transforming, and exploring NYC Yellow Taxi trip data. It was built as part of a hands-on course on Udemy taught by Josué Afouda.

---

## 📦 Project Overview

The dataset comes from the official NYC Taxi & Limousine Commission (TLC) and includes millions of trips taken by Yellow Taxis in New York City.

### 🧰 Tech Stack

- **Python**
- **Pandas / PyArrow**
- **Parquet** for columnar storage
- **Jupyter Notebooks** for EDA
- **BigQuery (optional)** for scalable SQL-based processing
- **Airflow or Prefect (optional)** for workflow orchestration

---

## 🗂️ Project Structure

```
nyc-yellow-taxi-trips/
├── data/                      # Raw and processed data (excluded from repo)
├── notebooks/                # Jupyter Notebooks (EDA, feature engineering)
├── scripts/                  # Python scripts for ingestion/transformation
├── queries/                  # BigQuery SQL files (optional)
├── requirements.txt          # Python package requirements
└── README.md
```

---

## 📌 Key Features

- 🔄 **Download** Parquet files directly from NYC TLC cloud
- 🧪 **Explore** trips by date, distance, fare amount, and trip duration
- 🔧 **Transform** raw data: clean columns, convert datatypes, create new features
- 🧠 **Prepare** datasets for ML use (trip duration prediction, clustering, etc.)

---

## 🚀 Example Workflow

1. Run `scripts/download_taxi_data.py` to fetch the Parquet files
2. Use `notebooks/eda.ipynb` to explore the dataset
3. Use `scripts/transform_trips_data.py` to clean and enrich data
4. Load to BigQuery or use locally in a data science model

---

## 🎓 Based On

This project was built while following the Udemy course:

**🧠 Course**: [Become a Data Engineer: Mastering NYC Yellow Taxi Pipeline](https://www.udemy.com/course/data-engineering-zoomcamp-nyc-taxi/)  
**👨‍🏫 Instructor**: [Josué Afouda](https://github.com/JosueAfouda)

---

## ⚙️ Installation

```bash
git clone https://github.com/etiennelaporte/nyc-yellow-taxi-trips.git
cd nyc-yellow-taxi-trips
pip install -r requirements.txt
```

---

## 👤 Author

**Etienne Laporte**  
Engineer & Data Automation Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/etiennelaporte)

---

## 📜 License

MIT License – feel free to use, adapt, and share with credit.
