# E-Commerce Analytics: Customer Behavior and Business Performance  
*Data Cleaning, EDA, and Visualization project using Python (Pandas, Matplotlib)*  

## 📌 Project Overview
This repository analyzes an **E-Commerce dataset** to understand customer behavior and evaluate business performance.  
It follows a clear workflow: **data cleaning → exploratory data analysis (EDA) → visualization → insights**.

## 📦 Data Access (Kaggle)
Dataset: https://www.kaggle.com/datasets/bytadit/ecommerce-order-dataset

```bash
pip install kaggle
kaggle datasets download -d bytadit/ecommerce-order-dataset -p data/raw --unzip
```

## 🚀 Quickstart
```bash
python -m venv .venv
# Windows PowerShell:
. .venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt jupyter ipykernel
python -m ipykernel install --user --name ecommerce-venv --display-name "Python (ecommerce-venv)"
```

### Objectives
- Clean and prepare raw data for analysis  
- Explore customer purchasing patterns and segmentation  
- Analyze sales and revenue trends over time, category, and geography  
- Visualize findings to support business decisions

## 🧰 Tools & Technologies
- **Python**: Pandas, Matplotlib, Seaborn  
- **Jupyter Notebook**  
- **CSV** data handling  

## 📁 Repository Structure
```
ecommerce-analytics-repo/
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ notebooks/
│  └─ Ecommerce_Data_Analysis.ipynb
├─ docs/
│  └─ E-commerce Business Intelligence Analysis.pdf
├─ data/               # place raw/processed data here (kept empty in repo)
├─ images/             # export charts here to reference in README/docs
└─ src/                # reusable Python scripts/utilities
```


## ▶️ How to Run
1. **Clone** the repository:
   ```bash
   git clone https://github.com/IzharSyauqi/ecommerce-analytics.git
   cd ecommerce-analytics
   ```
2. (Optional) **Create a virtual environment**:
   ```bash
   python -m venv .venv
   # Windows:
   .venv\Scripts\activate
   # macOS/Linux:
   source .venv/bin/activate
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Open the notebook**:
   ```bash
   jupyter notebook notebooks/Ecommerce_Data_Analysis.ipynb
   ```

## 📊 Results & Insights (examples)
- Top-performing product categories and seasonal spikes  
- Delivery performance vs. customer satisfaction signals  
- Geographic clusters with high revenue per customer  
- Actionable recommendations for marketing & logistics

## 🧭 Next Steps
- Add interactive dashboards (Plotly/Power BI)  
- Apply ML for churn/CLV prediction  
- Integrate near real-time data feeds

---

**Author**: Muhammad Izhar Syauqi  
**Focus**: Data Analytics | Python | Visualization | EDA
