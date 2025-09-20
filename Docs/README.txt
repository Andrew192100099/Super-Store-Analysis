╔════════════════════════════════════════════════════════════════════╗
║                FINAL PROJECT — Superstore Analysis						║
╚════════════════════════════════════════════════════════════════════╝

Tagline: Turning messy retail data into clear, actionable store insights.

────────────────────────────────────────────────────────────────────────
OVERVIEW
────────────────────────────────────────────────────────────────────────
This project demonstrates an end-to-end analysis of the "Superstore" dataset:
data cleaning and modeling in Excel, followed by deeper analytics and
visualizations in Jupyter (Python). The aim is to extract business insights,
improve data quality, and segment customers using RFM.

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final
(also uploaded to Google Drive for backup)
https://drive.google.com/drive/folders/1zsC4dCqCo6gQla2tl1y9ouF6wk0f7MTV?usp=sharing

────────────────────────────────────────────────────────────────────────
HIGHLIGHTS
────────────────────────────────────────────────────────────────────────
• Excel-first cleaning: full metadata, normalization, and product-model fixes.
• Jupyter analysis: profit breakdowns, visualizations, and RFM segmentation.
• Visual tools used: Matplotlib, Seaborn, Plotly Express.
• Outcome: reproducible notebooks + pivot-driven Excel deliverables.

────────────────────────────────────────────────────────────────────────
EXCEL PREPARATION (what's in /excel)
────────────────────────────────────────────────────────────────────────
1. Meta_Data — field definitions & data types.
2. Business_Questions — prioritized analytics questions.
3. Cleaned_Data — all known issues resolved; product inconsistency model.
4. Normalization — normalized tables for reliable joins.
5. Pivot_Tables & Charts (8) — quick BI summaries and dashboards.
6. Documentation — stepwise change log and transformation notes.

────────────────────────────────────────────────────────────────────────
JUPYTER NOTEBOOK (what's in /notebooks)
────────────────────────────────────────────────────────────────────────
1. Data import & final checks.
2. Missing values & duplicate checks (zero found — cleaned in Excel).
3. Profit analysis across categories and segments.
4. Visualizations: Matplotlib, Seaborn, Plotly Express interactive plots.
5. RFM calculation and customer segmentation with summary tables.

────────────────────────────────────────────────────────────────────────
PROJECT STRUCTURE (recommended)
────────────────────────────────────────────────────────────────────────
/superstore-analysis
├─ excel/                     # Excel files & pivot workbooks
│  └─ cleaned_superstore.xlsx
├─ notebooks/
│  └─ Superstore_Analysis.ipynb
├─ docs/                      # documentation, data model diagrams
├─ requirements.txt
├─ README.txt
└─ LICENSE

────────────────────────────────────────────────────────────────────────
QUICK START — Run locally
────────────────────────────────────────────────────────────────────────
1) (Optional) Create virtual env:
   python -m venv venv
   # mac/linux
   source venv/bin/activate
   # windows (PowerShell)
   .\venv\Scripts\Activate.ps1

2) Install requirements:
   pip install -r requirements.txt
   # OR quick install:
   pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter

3) Start Jupyter:
   jupyter notebook
   # open notebooks/Superstore_Analysis.ipynb and run cells in order

────────────────────────────────────────────────────────────────────────
NOTES ON DATA CLEANING
────────────────────────────────────────────────────────────────────────
• Major fixes: product naming inconsistencies, missing dates & prices, and
  inconsistent categorical values resolved in Excel before analysis.
• Detailed cleaning steps and the data model are documented in /excel/docs.

────────────────────────────────────────────────────────────────────────
LICENSE & CREDITS
────────────────────────────────────────────────────────────────────────
Author: <Andrew Wageh Fahmy>
National Telecommunication Institute (NTI), Egypt  
Track: Data Analytics — Internship Task 13 (Excel & Python Project)  
Dataset source: Vivek468 — Superstore Dataset (Kaggle)
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

License: MIT 

────────────────────────────────────────────────────────────────────────
CONTACT
────────────────────────────────────────────────────────────────────────
Questions, suggestions or collaborations — 192100099@ecu.edu.eg || andrewwageh333@gmail.com

════════════════════════════════════════════════════════════════════════

