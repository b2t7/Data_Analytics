# Data Analytics Portfolio

Hi, I'm **Bini**, a data analytics postgraduate student based in Perth, Western Australia. This repository brings together my data analytics projects, from data collection and cleaning through to modelling, visualisation and reporting.

---

## About Me

- Studying a **Master of Predictive Analytics (Data Science)**
- **Bachelor of Science** in Physics and Statistics
- Hands-on experience in data entry, inventory and purchasing data, and junior data analysis
- Looking for data analyst internships and graduate roles in Western Australia

---

## Skills and Tools

| Area | Tools |

| Programming | Python (pandas, NumPy, statsmodels, scikit-learn), R, SQL |
| Visualisation and BI | Power BI, Streamlit, Matplotlib, Excel |
| Analytics and Modelling | Regression (OLS, 2SLS/IV), time-series (ECM, VAR), data mining, business analytics |
| Workflow | Git/GitHub, VS Code, Google Workspace |
| Data Sources | ABS, RBA, CoreLogic and other public datasets |

---

## Projects

### 1. A Model of the West Australian Housing Market
Adapts the RBA national housing model (Saunders & Tulip, 2019) to Western Australia using public data.

- **Goal:** Understand how supply, population, migration, incomes and interest rates drive WA dwelling prices and rents
- **Data:** ABS (building approvals, completions, dwelling stock, population, migration, labour force, income), RBA (CPI, cash and mortgage rates)
- **Methods:** Quarterly panel build, error correction model (ECM), 2SLS/IV, scenario analysis, out-of-sample validation
- **Output:** Python codebase, interactive Streamlit dashboard with scenario sliders, final report
- **Folder:** [`/wa-housing-model`](./wa-housing-model)

---

## Repository Structure

```
.
├── wa-housing-model/
│   ├── config/            # Data source configuration (series IDs)
│   ├── data/
│   │   ├── raw/           # Original ABS/RBA workbooks
│   │   └── processed/     # Cleaned quarterly panel
│   ├── src/
│   │   ├── data/          # Loaders and panel builder
│   │   └── features/      # Transformations and feature engineering
│   ├── app/               # Streamlit dashboard
│   └── README.md
└── README.md
```

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

# Create a virtual environment
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # macOS/Linux

# Install dependencies
pip install -r requirements.txt
```

Each project folder has its own README with specific run instructions.

---

## Typical Workflow

1. **Collect** data from public sources and APIs
2. **Clean** and validate (missing values, types, deflating to real terms)
3. **Explore** with summary statistics and visualisations
4. **Model** using statistical and machine learning methods
5. **Communicate** findings through dashboards and reports

---

## Data Sources and Licensing

Data comes from public sources including the Australian Bureau of Statistics (ABS) and the Reserve Bank of Australia (RBA). Please refer to each provider's terms of use. Code in this repository is released under the [MIT License](./LICENSE).

---

## Contact

Open to internships and graduate opportunities in data analytics.

- Location: Perth, WA
