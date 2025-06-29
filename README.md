# 📈 Unemployment Analysis & Industry Insights in India (2019–2020)

This Data Analytics project provides an end-to-end analysis of unemployment trends in India during 2019–2020, leveraging multiple datasets and visualization techniques. It also maps industrial efficiency and regional employment opportunities using real-world data.

---

## 📂 Dataset Overview

The project uses **three real-world datasets** sourced from Kaggle and other government data repositories:

1. **Unemployment in India.csv** – State-wise, area-wise unemployment data
2. **Unemployment Rate upto 11\_2020.csv** – Includes geographical data (latitude/longitude)
3. **Industrywisedatasupto\_dipp.csv** – Investment, employment, and industry-wise stats

> 📌 **Note**: Raw datasets are not uploaded to GitHub due to license and file size. Instead, use the original dataset links provided inside the notebook.

---

## 🔍 Project Workflow

### **Phase 1: Data Loading & Exploration**

* Imported datasets and libraries
* Displayed dataset structure and health (nulls, datatypes, preview)

### **Phase 2: Data Cleaning & Preprocessing**

* Column renaming for consistency
* Datetime parsing and formatting
* Null removal and duplicate handling
* Data type conversions for numeric fields (investment, employment)

### **Phase 3: Exploratory Data Analysis (EDA)**

* National unemployment rate over time
* Region-wise unemployment distribution (June 2020 focus)
* Correlation heatmaps and top 10 lists
* Geo-plots for state-wise unemployment
* Industry-wise investment vs employment comparison

### **Phase 4: Deep Insights & Strategic Analysis**

* Jobs per ₹ crore investment (industry efficiency)
* Regional employment strength (e.g., Telangana vs national avg)
* Skill recommendations based on top job-generating sectors
* Opportunity score mapping for different states
* Summary of strategic observations and recommendations

---

## 📊 Key Visualizations & Metrics

| Insight                          | Description                                          |
| -------------------------------- | ---------------------------------------------------- |
| 📈 Trend Plot                    | National unemployment trends over time               |
| 🗺️ Geo Map                      | State-wise unemployment in June 2020                 |
| 🔥 Top Industries                | Ranked by investment, employment, and jobs per crore |
| 💼 Efficiency Bar Plot           | Job output per crore across industries               |
| 🧠 Skill Development Suggestions | Based on industry-wise employment trends             |
| 📌 Regional Score Mapping        | High-opportunity states based on unemployment rate   |

---

## ⚙️ Technologies Used

* **Python** (Pandas, NumPy, Seaborn, Matplotlib, Plotly)
* **Google Colab** (interactive notebook)
* **CSV datasets** (publicly available sources)

---

## 🚀 Manual Testing (for Extension)

If you want to extend this project, consider:

* Adding real-time data integration via API
* Creating a web dashboard using Streamlit or Dash
* Applying predictive modeling for forecasting future unemployment

---

## 📌 Limitations

* The datasets end in late 2020; post-COVID recovery patterns are not included.
* Geo-coordinates are approximate and static.
* Some industry data is not standardized or may contain currency formatting issues.

---

## 🔭 Future Scope

* Integrate data from **CMIE**, **NSSO**, or **MOSPI** for higher granularity
* Build ML models to **predict regional unemployment rates**
* Automate **skill recommendation system** based on employment gaps
* Develop a **dashboard or heatmap visualization** using Tableau or PowerBI

---

## 🙌 Acknowledgements

* [CMIE Unemployment Data (via Kaggle)](https://www.kaggle.com/datasets)
* \[DIPP Industry Employment Dataset]
* \[Government of India Statistical Repositories]

---

## 📁 Project Structure

```
📦 Unemployment-Analysis-India
├── 📄 README.md
├── 📄 unemployment_analysis.ipynb
└── 📁 data/
    └── (Datasets not uploaded – links provided in notebook)
```

---

## 🪪 License

This project is for academic use only. Dataset rights remain with original authors/sources.

---

> 💡 **Pro Tip**: View the notebook on Colab for best interactive visual experience.
