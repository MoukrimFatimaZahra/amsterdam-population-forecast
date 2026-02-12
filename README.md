# amsterdam-population-forecast
City-level demographic forecasting and district trend analysis using ML.
# 📊 Amsterdam Demographic & Subsidies Forecasting

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenPyXL](https://img.shields.io/badge/OpenPyXL-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 📋 **Project Overview**

This project performs comprehensive **demographic and subsidy forecasting for Amsterdam (2020-2028)** using machine learning techniques. The analysis combines multiple datasets to generate actionable insights for policymakers, with a focus on:

- 👶 **Youth population (0-15)** trends and forecasts
- 👴 **Elderly population (65+)** trends and forecasts
- 🎓 **Education subsidies** evolution
- 🏥 **Care subsidies** evolution
- 🏠 **Household composition** changes
- 📍 **District-level** comparative analysis

---

## 🛠️ **Technologies Used**

### **Core Data Science Stack**
| Technology | Logo | Purpose |
|-----------|------|---------|
| **Python 3.8+** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | Primary programming language |
| **Pandas** | ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) | Data manipulation & cleaning |
| **NumPy** | ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) | Numerical operations |
| **Scikit-learn** | ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white) | Linear regression modeling |
| **Matplotlib** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?logo=python&logoColor=white) | Data visualization |
| **Seaborn** | ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?logo=python&logoColor=white) | Statistical visualizations |

### **Data Processing & I/O**
| Technology | Logo | Purpose |
|-----------|------|---------|
| **OpenPyXL** | ![OpenPyXL](https://img.shields.io/badge/OpenPyXL-217346?logo=microsoftexcel&logoColor=white) | Excel file processing |
| **CSV** | ![CSV](https://img.shields.io/badge/CSV-FF6C37?logo=python&logoColor=white) | Data export format |

### **Development Environment**
| Technology | Logo | Purpose |
|-----------|------|---------|
| **Google Colab** | ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?logo=googlecolab&logoColor=white) | Cloud-based development |
| **Jupyter** | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) | Interactive notebooks |
| **Google Drive** | ![Google Drive](https://img.shields.io/badge/Google_Drive-4285F4?logo=googledrive&logoColor=white) | Data storage |

### **Business Intelligence**
| Technology | Logo | Purpose |
|-----------|------|---------|
| **Power BI** | ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black) | Dashboard & reporting |

---

## 📊 **Data Sources**

| Dataset | Source | Years | Description |
|---------|--------|-------|-------------|
| **Demographics** | Amsterdam Region Districts | 2020-2024 | Population by age, gender, household type |
| **Subsidies** | Amsterdam Subsidies | 2010-2025 | Education & care funding |
| **Education** | Students per type | 2015-2024 | Student enrollment statistics |

---

## 🧠 **Methodology**

### **1. Data Processing Pipeline**
```
Raw Excel/CSV → Pandas Cleaning → Feature Engineering → Aggregation
```

### **2. Forecasting Approach**
- **Model**: Linear Regression (Scikit-learn)
- **Features**: Historical year-on-year trends
- **Target**: 2026-2028 projections
- **Validation**: R² score, trend analysis

### **3. Key Metrics Tracked**
```
├── 👶 Youth Population (0-15)
├── 👴 Elderly Population (65+)
├── 🎓 Education Subsidies (€)
├── 🏥 Care Subsidies (€)
├── 🏠 Households with children
├── 🏠 Single-person households
└── 📍 District-level variations
```

---

## 📈 **Key Findings**

### **🔴 Education Mismatch**
- **Youth population**: ⬇️ Declining (-316/year)
- **Education subsidies**: ⬆️ Growing (+€2.95M/year)
- **Insight**: Funding increases despite population decline

### **🟢 Care Alignment**
- **Elderly population**: ⬆️ Growing (+4,099/year)
- **Care subsidies**: ⬆️ Growing (+€4.57M/year)
- **Insight**: €1,115 per new elderly person

### **🟡 Care Dominance**
- **Care growth**: 4.6x faster than Education
- **2028 projection**: €48.8M (Care) vs €34.7M (Education)

---

## 🚀 **Output Files**

| File | Description |
|------|-------------|
| `demographics_all_years.csv` | Cleaned demographic data (2020-2024) |
| `amsterdam_citywide.csv` | Aggregated Amsterdam metrics |
| `subsidies_clean.csv` | Processed subsidy data |
| `students_clean.csv` | Student enrollment data |
| `forecast_education_subsidies.csv` | 2026-2028 education subsidy forecasts |
| `forecast_care_subsidies.csv` | 2026-2028 care subsidy forecasts |
| `forecast_youth_population.csv` | 2026-2028 youth population forecasts |
| `forecast_elderly_population.csv` | 2026-2028 elderly population forecasts |
| `district_forecasts.csv` | District-level trend comparisons |

---

## 💻 **Installation & Usage**

```bash
# Clone repository
git clone https://github.com/yourusername/amsterdam-forecasting.git

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl

# Run in Google Colab or Jupyter
# Mount Google Drive with data files
# Execute run_pipeline.py
```

---

## 📁 **Project Structure**

```
├── 📓 run_pipeline.py              # Main execution script
├── 📊 demographics_all_years.csv   # Output: cleaned demographics
├── 📊 amsterdam_citywide.csv       # Output: city aggregates
├── 📊 subsidies_clean.csv         # Output: processed subsidies
├── 📊 forecast_*.csv             # Output: 2026-2028 forecasts
├── 📘 README.md                   # Project documentation
└── 📈 PowerBI_Dashboard.pbix     # Visualization dashboard
```

---

## 👥 **Target Audience**

- 🏛️ **Amsterdam Municipality** - Policy planning
- 🎓 **Education Department** - Resource allocation
- 🏥 **Care & Welfare Department** - Elderly services
- 📊 **Data Analysts** - Urban trend analysis
- 🧪 **Researchers** - Demographic studies

---

## 📝 **License**

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🤝 **Contributing**

Contributions, issues, and feature requests are welcome!

---

## 📬 **Contact**

For questions or collaboration:  
📧 f.z.moukrim@gmail.com 
🌐 ](https://www.linkedin.com/in/f-z-moukrim21/)

---

<div align="center">
  
### ⭐ **Star this repository if you find it useful!** ⭐

**Built with Python ❤️ for Amsterdam's data-driven future**

</div>
