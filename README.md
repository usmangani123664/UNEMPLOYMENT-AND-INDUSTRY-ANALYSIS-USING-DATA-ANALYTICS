# 📈 Unemployment Analysis & Industry Insights in India (2019–2020)

This Data Analytics project provides a complete end-to-end analysis of unemployment trends in India during 2019–2020. It leverages real-world datasets and visualization techniques to uncover regional disparities, analyze industry efficiency, and suggest strategic directions for employment growth.

---

## 📂 Dataset Overview

The project uses **three real-world datasets** sourced from Kaggle:

1. **Unemployment in India.csv**
   - State-wise and area-wise unemployment data (Rural/Urban)
   - 📎 [Dataset Link](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)

2. **Unemployment Rate upto 11_2020.csv**
   - Includes state-level unemployment rates with latitude/longitude
   - 📎 [Dataset Link](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)

3. **Industrywisedatasupto_dipp.csv**
   - Industry-wise investment and employment data
   - 📎 [Dataset Link](https://www.kaggle.com/datasets/ravivarmaodugu/data-on-investment-and-employment-in-india)

> 🔒 **Note**: Raw datasets are not uploaded to this repository due to licensing and size restrictions. Access the above links to download them.

---

## 🔍 Project Workflow

### 🔧 Phase 1: Data Loading & Exploration
- Imported datasets and Python libraries
- Previewed structure, types, and missing values

### 🧹 Phase 2: Data Cleaning & Preprocessing
- Renamed columns for consistency
- Converted date columns to `datetime`
- Dropped nulls and duplicates
- Formatted investment/employment columns numerically

### 📊 Phase 3: Exploratory Data Analysis (EDA)
- Plotted national unemployment trend over time
- Visualized June 2020 unemployment by region
- Created correlation heatmaps and bar charts
- Compared investment vs employment across industries

### 🧠 Phase 4: Deep Insights & Strategic Analysis
- Calculated **Jobs per ₹ Crore** for industry efficiency
- Assessed regional employment strength (e.g., Telangana)
- Mapped **opportunity scores** based on unemployment rate
- Suggested skill development areas per high-efficiency industry

---

## 📊 Key Visualizations & Metrics

| Insight                    | Description                                                      |
|---------------------------|------------------------------------------------------------------|
| 📈 Trend Plot              | National unemployment rate (monthly) from Jan 2019 – Nov 2020   |
| 🗺️ Geo Map                 | June 2020 state-wise unemployment rate using latitude/longitude |
| 🔥 Top Industries         | Ranked by investment, employment, and efficiency (jobs/crore)    |
| 💼 Efficiency Bar Plot     | Jobs per ₹ crore for each industry                              |
| 🧠 Skill Suggestions        | Based on top job-generating industries                          |
| 📌 Regional Score Mapping  | States categorized by high/medium/low job creation potential    |

---

## ⚙️ Technologies Used

- **Python 3**
  - `pandas`, `numpy` – Data processing
  - `matplotlib`, `seaborn` – Static plots
  - `plotly.express` – Interactive visualizations

- **Google Colab** – Jupyter-based execution and visualization
- **CSV files** – Loaded from Kaggle downloads

---

## 🚀 Possible Extensions

- 🔗 Real-time data via **API** from CMIE/NSSO
- 📈 Forecasting future unemployment using **ML models**
- 🖥️ Build dashboards with **Streamlit, Dash, or Tableau**
- 🔍 Automate skill-gap analysis from job board data

---

## 📌 Limitations

- Data limited to **Jan 2019 – Nov 2020**; no post-COVID recovery trends
- Geographic coordinates are approximate
- Industry dataset may have formatting or normalization issues

---

## 🔭 Future Scope

- Integrate new data from **CMIE**, **MOSPI**, or **PLFS**
- Build **predictive models** for regional unemployment risk
- Create a **national employment dashboard** with drill-down options
- Add **NLP-based job post analysis** for skill gap detection

---

## 🙌 Acknowledgements

- [Unemployment in India – Kaggle](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)
- [Industry-wise Employment & Investment Dataset – Kaggle](https://www.kaggle.com/datasets/ravivarmaodugu/data-on-investment-and-employment-in-india)
- Government of India statistical portals

---

## 📁 Project Structure
📦 unemployment-analysis-india
├── 📄 README.md
├── 📄 unemployment_analysis.ipynb
└── 📁 data/
└── (Datasets not uploaded – see links in notebook)
