[README.md](https://github.com/user-attachments/files/35359297/README.md)
# ApexPlanet Data Analytics Internship — Task 1

## Foundational Setup & Exploratory Data Analysis (EDA)

This repository completes Task 1 from the ApexPlanet 30-Day Data Analytics Internship PDF.

### Dataset
Sample Superstore Sales. The notebook downloads the CSV from the public source below on first run:
- https://github.com/Analytics6/Streamlit-Dashboards/blob/main/superstore_dashboard/data/sample_superstore.csv

If automatic download does not work, download the CSV manually and save it as:
`data/raw/sample_superstore.csv`

### Project structure
```text
apexplanet-data-analytics/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── task1_superstore_eda.ipynb
├── scripts/
├── reports/
├── dashboards/
├── requirements.txt
└── README.md
```

### Setup (Windows PowerShell)
```powershell
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
jupyter notebook
```

Open `notebooks/task1_superstore_eda.ipynb` and run all cells from top to bottom.

### Work completed
- Dataset loading and initial inspection
- Missing-value handling and duplicate removal
- Date and numeric type conversion
- IQR-based outlier detection and capping
- Statistical summary
- Histograms, boxplots, bar charts, correlation heatmap, and monthly trend line chart
- Five data-driven insights
- Cleaned CSV export

### Output
After running the notebook:
- `data/processed/superstore_cleaned.csv`
- `reports/eda_key_insights.txt`

### Tools
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, Plotly, SQLAlchemy.
