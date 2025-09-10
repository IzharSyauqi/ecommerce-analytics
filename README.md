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
<img width="1189" height="589" alt="image" src="https://github.com/user-attachments/assets/4f0d4092-2158-4c8d-84f4-7a26999516ea" />

<img width="1190" height="590" alt="image" src="https://github.com/user-attachments/assets/d3a02393-bd5f-4e2c-809f-cc1265393242" />

- Order fulfillment and delivery performance 
<img width="1431" height="590" alt="image" src="https://github.com/user-attachments/assets/11e2ab97-3dda-4b9e-ae90-dc385413cb6c" />
ORDER FULFILLMENT INSIGHTS:
| Order completion rate: 97.9%
| Total orders processed: 89,316

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/aa57f6c6-62d9-4bbd-a913-c590e1e80940" />
| Average delivery time: 11.3 days
| Fast (<7 days): 30.5% of orders
| Delayed (>15 days): 21.8% of orders

- Geographic clusters with high revenue per customer  
<img width="1489" height="590" alt="image" src="https://github.com/user-attachments/assets/6a58de56-eb2c-4f39-b89b-a8e5564615d2" />
GEOGRAPHIC INSIGHTS:
 Top customer state: sp (37,879 customers)
| Top revenue state: sp ($14,586,002.19)
| Geographic concentration: Top 5 states = 69,235 customers (80.6% of total)

## 🧭 Next Steps
- Add interactive dashboards (Plotly/Power BI)  
- Apply ML for churn/CLV prediction  
- Integrate near real-time data feeds

---

**Author**: Muhammad Izhar Syauqi  
**Focus**: Data Analytics | Python | Visualization | EDA
