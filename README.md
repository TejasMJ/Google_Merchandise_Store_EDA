# Google Merchandise Store EDA 📊

A comprehensive **Exploratory Data Analysis (EDA)** of the Google Merchandise Store e-commerce dataset, focusing on user behavior, purchase funnels, product performance, pricing patterns, and customer lifetime value using Python and popular data analysis libraries.

---

## 🌟 Features

### Core Features
- **Data Cleaning & Preprocessing:** Handling missing values, data type standardization, and consistency checks.
- **User Behavior Analysis:** Exploration of users, sessions, devices, and geographic distribution.
- **Purchase Funnel Analysis:** Event-level analysis of add-to-cart, checkout, and purchase behavior.
- **Product & Category Insights:** Performance analysis across product categories, brands, and top-selling items.
- **Pricing & Revenue Analysis:** Price distribution, revenue concentration, and lifetime value (LTV) patterns.
- **Visualization:** Clear and interpretable plots to surface behavioral and business insights.

---

## 🗂 Project Structure

The project folder is organized as follows:

```text
Google_Merchandise_Store_EDA/
├── google_merchandise_store.csv      # Google Merchandise Store dataset
├── Google_Merchandise_Store_EDA.ipynb # Jupyter Notebook with full EDA
├── requirements.txt                  # Python dependencies
└── venv/                             # Virtual environment
```

---

## 🏗️ EDA Architecture

```text
+-----------------------------+  
|        DATA LAYER           |  
|  User & event-level data    |  
|  (Sessions, Products)      |  
+-------------+---------------+  
              ↓  
+-----------------------------+  
|      ANALYSIS LAYER         |  
|  - Data Cleaning            |  
|  - User Behavior Analysis   |  
|  - Funnel Drop-off Analysis |  
|  - Product & Price Analysis |  
|  - LTV Distribution         |  
+-------------+---------------+  
              ↓  
+----------------------------------+  
|     VISUALIZATION LAYER          |  
|  - Bar, Line & Distribution Plots|  
|  - Funnel & Category Charts      |  
|  - Revenue & LTV Visuals         |  
+----------------------------------+  

```

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Data Source:** [Kaggle – Google Merchandise Store](https://www.kaggle.com/datasets/mexwell/google-merchandise-sales-data?select=events1.csv)

---

## 📊 Dataset Overview

- **Rows:**  750000+ apps  
- **Columns include:** user_id, ga_session_id, country, device, event type, product details, price, timestamps, lifetime value (LTV) etc.  

**Context:**  
The dataset represents real e-commerce interactions from the Google Merchandise Store, capturing how users browse products, progress through the purchase funnel, and generate revenue over time.

**Acknowledgements:**  
- Data sourced from Google Merchandise Store via Kaggle.  
- Thanks to Kaggle contributors for making this dataset accessible.

**Inspiration:**  
Understanding how users browse products, progress through the purchase funnel, and generate revenue in the Google Merchandise Store can help business and product teams make data-driven decisions around merchandising, pricing, and conversion optimization.

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/TejasMJ/Google-Play-Store-App-EDA-.git
cd Google-Play-Store-App-EDA-
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```
### 3. Activate Virtual Environment
#### Windows:
```bash
.\venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```
### 5. Run Notebook

```bash
jupyter notebook
```

# 📊 Google MerchandiseStore Analysis Project

## Detailed Analysis Scope

### Data Cleaning & Preprocessing
- Remove duplicate records and ensure data consistency  
- Handle missing values across product and user attributes  
- Convert column types (e.g., categorical fields, event timestamps to datetime)

### Statistical Insights
- Summary statistics for key numerical fields (price, LTV, session counts)  
- Distribution analysis for product prices, user sessions, and lifetime value  
- Identification of skewness and revenue concentration patterns

### Product & Category Analysis
- Engagement and revenue distribution across product categories  
- Identification of top-performing and underperforming categories  
- Category-wise price and purchase behavior analysis

### User Behavior Analysis
- Analysis of user sessions and repeat visit patterns  
- Device-wise behavior and conversion differences  
- Country-level user and revenue distribution

### Pricing & Revenue Insights
- Price distribution and demand concentration  
- Revenue contribution by products and users  
- Customer lifetime value (LTV) analysis

### Visualization
- Insight-driven charts using **Matplotlib**, **Seaborn**, and **Plotly**  
- Funnel, distribution, and category-level visualizations

## 👨‍💻 Author
**Tejas Jadhav**  

- GitHub: [@tejas-jadhav](https://github.com/TejasMJ)  
- LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-m-jadhav/)
