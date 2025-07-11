# ✈️ FlightOps360: End-to-End Data Engineering Pipeline

**FlightOps360** is a full-scale data engineering project that simulates a real-world **airline booking and operations analytics platform**, built on the **Databricks Lakehouse** architecture using **Delta Live Tables**, **PySpark**, and **DBT**.

<img width="1280" height="640" alt="Architecture" src="https://github.com/user-attachments/assets/998c813b-f9b4-4378-ba4c-7dd4cd1c1144" />

---

## 📌 Key Components

- 🔄 **Incremental & real-time ingestion** of passenger, airport, flight, and booking datasets using **Databricks Autoloader**
- 📐 Built a **Dimensional Model (Star Schema)** with `Fact_Bookings` and related dimension tables (`Airports`, `Flights`, `Passengers`)
- 🔁 Managed **Slowly Changing Dimensions (Type 2)** to track historical changes in flight and passenger data
- ⚙️ Designed **declarative pipelines** with **Delta Live Tables** for scalable and maintainable transformations
- 🔍 Implemented data governance using **Unity Catalog**
- 📦 Integrated **DBT** for modular SQL transformations, testing, and documentation

---

## 🗂️ Datasets Processed

- `dim_airports.csv`, `dim_flights.csv`, `dim_passengers.csv`
- `fact_bookings.csv` (including `increment` and `scd` variations)

---

## 💡 Outcome

A **production-ready data pipeline** to support:
- Airline operations reporting  
- Historical change tracking  
- Real-time and batch booking analytics

All built using **modern data engineering best practices** and tools on the Databricks platform.

---

## 🛠️ Technologies Used

- **Databricks**
- **Delta Live Tables (DLT)**
- **PySpark**
- **DBT**
- **Unity Catalog**
- **Databricks Autoloader**
- **Medallion Architecture**

---

> 🔗 Feel free to reach out if you're interested in the code or walkthrough!
