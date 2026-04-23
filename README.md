# 🚔 Melbourne Crime Analysis: Motor Vehicle Theft (2016-2025)

Comprehensive analysis of motor vehicle theft patterns in Melbourne using 10 years of crime statistics from Victoria Police.

---

## 📊 Key Findings

- **52% spike** in motor vehicle thefts (2023-2024): from 16,748 → 25,549 incidents
- **70%+ unsolved rate** across all years
- **Street parking = 34%** of all thefts (45,654 incidents)
- **Top hotspots:** Hume (11,366), Casey (10,095), Melbourne CBD (9,566)
- **Males: 75%** of alleged offenders; peak age 25-29 years

---

## 🗂️ Datasets

Three Victoria Police Crime Statistics datasets (500K+ records):

1. **LGA Dataset** (367,203 records) - Geographic & temporal trends
2. **Criminal Incidents** (134,000+ B41 incidents) - Location types & charge status
3. **Alleged Offenders** - Demographics (gender, age)

### Data Access

⚠️ **Data files NOT included** (100MB+ total)

**Download from:** [Victoria Police Crime Statistics](https://www.crimestatistics.vic.gov.au)

Files needed:
- `Data_Tables_LGA2025.xlsx`
- `Data_Tables_Criminal_Incidents2025.xlsx`
- `Data_Tables_Alleged_Offender2025.xlsx`

Place in `data/raw/` folder

---

## 🛠️ Technologies

- Python 3.9+
- Pandas, NumPy
- Matplotlib, Seaborn
- Folium (interactive maps)
- Jupyter Notebook

---

## 🚀 Setup

```bash
# Clone repository
git clone https://github.com/matthewphilip-quantlab/melbourne-crime-analysis.git
cd melbourne-crime-analysis

# Install dependencies
pip install -r requirements.txt

# Download data (see above)
# Place in data/raw/

# Run notebook
jupyter notebook
```

---

## 📈 Analysis Overview

### Temporal Analysis
- COVID-19 impact: 24% drop (2020-2021)
- Post-pandemic surge: 52% increase (2024)
- Consistent 70% unsolved rate

### Geographic Patterns
- Melbourne Metro accounts for majority
- Outer suburbs (Hume, Casey, Dandenong) highest
- Custom region mapping: 79 LGA → 12 regions

### Location Analysis
- Street/footpath: 34% (most vulnerable)
- Residential driveways: 13%
- Single-level carparks: 7%

### Demographics
- Gender: 75% male, 25% female
- Age peak: 25-29 years (16.3%)
- Youth crime: 17.2% under 18

---

## 🗺️ Visualizations

15+ charts including:
- Temporal trends (line charts)
- Geographic hotspots (bar charts, maps)
- Demographic breakdowns (stacked area charts)
- Interactive Folium map

---

## ⚠️ Ethical Considerations

### Limitations
- Alleged offenders ≠ convicted criminals
- Reporting bias exists
- No socioeconomic context
- Aggregated data only

### Intended Use
✅ Understanding crime patterns  
✅ Public awareness  
✅ Academic research  

❌ NOT for individual profiling  
❌ NOT for discriminatory practices  

---

## 📂 Project Structure

melbourne-crime-analysis/
├── README.md
├── requirements.txt
├── .gitignore
├── [your-notebook].ipynb
├── data/
│   └── raw/          # Download datasets here
└── outputs/
├── figures/
└── maps/

---

## 📝 License

MIT License

Data: Victoria Police Crime Statistics (subject to their terms of use)

---

## 👤 Author

**Philip Setiawan**

- GitHub: [@matthewphilip-quantlab](https://github.com/matthewphilip-quantlab)
- LinkedIn: [Philip Matthew](https://linkedin.com/in/philip-matthew)
- Email: matthewphilip788@gmail.com

---

## 🙏 Acknowledgments

- Victoria Police for providing open crime statistics
- Melbourne metropolitan community for the context
- Python data science community for excellent tools

---

⭐ **If you found this useful, please star the repo!**

*Last updated: January 22, 2026*
