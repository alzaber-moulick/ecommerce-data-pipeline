<p align="center">
  <img src="./banner.webp" alt="E-Commerce Data Pipeline" width="100%">
</p>

# 🚀 E-Commerce Data Pipeline & Excel Automation

A robust Python-based automated data extraction and processing pipeline designed to fetch product catalogs from APIs/web sources, clean and structure the data, and export multi-tab executive Excel reports.

---

## 🛠️ Key Features
* **Automated Data Extraction:** Fetches live product catalogs securely using Python (`requests`, `pandas`).
* **Data Cleansing & Transformation:** Parses JSON/HTML data, handles missing values, and normalizes formats.
* **Multi-Tab Excel Reporting (`openpyxl`):** Automatically categorizes and exports datasets into distinct sheets:
  1. *All Products* (Complete catalog)
  2. *High Rated (4+ Stars)* (Filtered top-tier items)
  3. *Budget Friendly (<=$50)* (Affordable product segments)
* **Production-Ready Structure:** Clean code architecture ready for proxy integration and task scheduling.

---

## ⚙️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** `pandas`, `requests`, `openpyxl`

---

## 🚀 How to Run Locally

### 1. **Clone the Repository**
```bash
git clone [https://github.com/your-username/ecommerce-data-pipeline.git](https://github.com/your-username/ecommerce-data-pipeline.git)
cd ecommerce-data-pipeline
