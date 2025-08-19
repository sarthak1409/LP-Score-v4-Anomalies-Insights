# LP Score v4 Analysis – Internship Assignment

## 📌 Project Overview
This project was completed as part of an **internship selection assignment**.  
The task was to **validate, explain, and stress-test** the **LP Score v4 system** using a wallet-level dataset (~45K rows, 396 columns).  

We analyzed:  
- **Aggregated LP Scores** vs per-pool scores  
- Category breakdown fields (`stable-stable`, `stable-volatile`, `volatile-volatile`)  
- Anomalies in retention, deposits, volatility, and timestamps  
- Outliers where behavior and scores do not align  

The project deliverables included:  
1. **Short Report (2–3 pages)** with key findings, anomalies, and formula explanation.  
2. **Reproducible Jupyter Notebook** (`lp_score_analysis.ipynb`) with code, plots, and anomaly detection.  
3. **Anomalies CSV** listing wallet-level inconsistencies.  
4. **Supporting documentation** (this README and requirements).  

---

## 📂 Folder Structure
```
├── dataset/                       # Raw dataset (wallet-level LP scoring data)
├── anomalies_csv/                 # Exported anomalies (wallet_id, pool_id, reason)
├── lp_score_analysis.ipynb        # Main Jupyter Notebook (analysis + plots)
├── zeru_pdf.pdf                   # Problem statement (assignment spec)
├── README.md                      # Project description and usage guide
└── requirements.txt               # Python dependencies
```

---

## ⚙️ Requirements
To run the notebook, install the dependencies using:  

```bash
pip install -r requirements.txt
```

---

## 🛠️ Technologies Used
- Python 3.9+  
- Pandas, NumPy for data analysis  
- Matplotlib, Seaborn for plots  
- Jupyter Notebook for reproducibility  

---

## 👨‍💻 Author
**Sarthak Maddi**  
*AI Engineer Intern (Applicant)*  
Date: August 2025  

---

## 🎯 Assignment Context
This project was part of an **internship selection process**. The objective was to:  
- Reverse-engineer how the **aggregated LP score** is derived  
- Validate alignment between scores and wallet behavior  
- Identify **anomalies, inconsistencies, and edge cases**  
- Provide a structured report with findings and recommendations  

