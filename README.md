# Customer Churn Analytics Platform

An end-to-end data and machine learning project focused on customer churn analysis for a **synthetic online sports betting platform**.

The project simulates a betting platform where customer behavior, betting activity, and sporting events can be analyzed to identify patterns associated with customer churn.

> **Project status:** Synthetic dataset generation completed. Exploratory Data Analysis is the next stage.

---

## Project Overview

Customer churn is an important problem for digital platforms because losing existing customers can affect revenue and long-term customer retention.

In this project, I am building a synthetic sports betting platform and analyzing customer behavior to understand:

* How customers interact with the platform.
* How betting behavior differs between customer segments.
* How sporting events and seasonality affect activity.
* Which behavioral patterns may be associated with customer churn.

The final goal is to develop a machine learning pipeline capable of identifying customers who may be at risk of churning.

The project will also include data engineering, database management, API development, and deployment components.

---

## Dataset

The dataset is **synthetically generated** for this project and covers the period from **2024 to 2025**.

The main entities are:

### Users

User information includes:

* `usuario_id`
* `fecha_registro`
* `edad`
* `pais_residencia`
* `metodo_pago_preferido`
* `segmento_riesgo`
* `limite_deposito_mensual`

### Bets

Each betting transaction contains information such as:

* `apuesta_id`
* `usuario_id`
* `evento_id`
* `fecha_colocacion`
* `tipo_apuesta`

The simulated betting types include:

* Single
* Parlay
* System

### Events

The event dataset contains approximately **10,000 sporting events** between 2024 and 2025.

Sports included:

* Football
* Basketball
* Tennis
* Baseball

Competitions include:

* Liga MX
* Premier League
* LaLiga
* UEFA Champions League
* NBA
* EuroLeague
* ATP
* WTA
* American League
* National League

Each event contains information such as:

* Event ID
* Date
* Sport
* Competition
* Participants
* Result

---

## Synthetic Customer Behavior

Different customer segments are used to simulate different betting patterns.

The current segments include:

* **Recreational**
* **Occasional**
* **High Value**
* **Seasonal**

The data generation process also incorporates seasonal changes in activity around major sporting periods.

These assumptions are used only to create a realistic synthetic environment for the project.

---

## Event Characteristics

The project also incorporates simulated characteristics of sporting events and teams.

These include factors such as:

* Team popularity
* Team strength
* Home advantage
* Stadium capacity
* Average attendance

The purpose is to create more realistic event data and provide additional variables that can later be used during analysis and feature engineering.

---

## Churn

One of the main objectives of the project is to develop a meaningful definition of customer churn.

Rather than relying only on an arbitrary inactivity period, the project will investigate changes in customer behavior over time.

Potential signals include:

* Decreasing betting frequency
* Changes in betting volume
* Increasing inactivity
* Changes in preferred betting behavior
* Changes relative to the customer's historical activity

The final churn definition will be established during the exploratory analysis and feature engineering stages.

---

## Project Roadmap

### 1. Problem Definition

* [x] Define business problem
* [x] Define project scope
* [x] Design synthetic data structure

### 2. Synthetic Dataset

* [x] Generate users
* [x] Generate sporting events
* [x] Generate betting activity
* [x] Add customer segments
* [x] Add event characteristics
* [x] Generate initial dataset

### 3. Exploratory Data Analysis

* [ ] Data quality analysis
* [ ] Customer behavior analysis
* [ ] Betting activity analysis
* [ ] Seasonality analysis
* [ ] Segment analysis
* [ ] Churn analysis

### 4. Feature Engineering

* [ ] Define observation and prediction windows
* [ ] Create customer-level features
* [ ] Create recency and frequency features
* [ ] Define churn target
* [ ] Prepare modeling dataset

### 5. Machine Learning

* [ ] Establish baseline
* [ ] Train classification models
* [ ] Compare models
* [ ] Evaluate performance
* [ ] Analyze feature importance

### 6. Data Engineering

* [ ] PostgreSQL database
* [ ] ETL pipeline
* [ ] SQL analysis
* [ ] PySpark processing

### 7. API & Deployment

* [ ] FastAPI
* [ ] Docker
* [ ] MLflow
* [ ] Automated testing
* [ ] CI/CD
* [ ] Streamlit dashboard
* [ ] Deployment

---

## Tech Stack

**Languages & Data Analysis**

* Python
* Pandas
* NumPy
* Scikit-learn

**Database**

* PostgreSQL
* SQL

**Data Engineering**

* ETL
* PySpark

**Machine Learning**

* Scikit-learn
* MLflow

**API & Deployment**

* FastAPI
* Docker

**Visualization**

* Matplotlib
* Seaborn
* Streamlit

**Version Control**

* Git
* GitHub

---

## Disclaimer

This project uses **synthetic data** created for educational and portfolio purposes.

The customer segments, betting behavior, event characteristics, and churn patterns are simulated assumptions and should not be interpreted as real-world statistics.

No real customer information is used.

---

## Project Status

**Current stage:** Synthetic dataset generation completed.

**Next stage:** Exploratory Data Analysis and data validation.
