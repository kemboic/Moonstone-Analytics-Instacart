# Moonstone Analytics – Instacart Data Engineering Project

**Phase 4: Pipeline & Governance**

**Team**  
- Peter Otieno – Database & Schema Lead  
- Nurudeen Showole – Processing & Spark Lead
- **Collins Kemboi** – Pipeline & Governance Lead

## Architecture
Medallion Architecture (Bronze → Silver → Gold) implemented with PySpark.

- **Bronze**: Raw CSV files (aisles, departments, order_items, orders, products)  
- **Silver**: Cleansed & enriched Parquet files  
- **Gold**: Business-ready Parquet tables + **daily_department_kpi** (required KPI table)

## How to Run
1. Clone the repo
2. Place the 5 raw CSV files in `/Moonstone_Instacart/bronze/`
3. Open `Moonstone_Pipeline_Phase4.ipynb` in Google Colab
4. Run all cells (fully automated – one click)

## Deliverables
- `Moonstone_Pipeline_Phase4.ipynb` – Complete automated pipeline
- `Moonstone_Governance.pdf` – Data Dictionary, PII analysis & access control
- `Moonstone_Architecture.png` – Pipeline diagram

## Technologies
PySpark • Medallion Architecture • Parquet • Google Colab

**Pipeline & Governance Lead:** Collins Kemboi  
**Status:** Complete & Production-Ready
