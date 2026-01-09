# healthcare-market-intelligence-notebooks
This repo contains a set of Jupyter notebooks used to build a healthcare market view combining BEA, BLS, and US Census data. The workflows import, clean, and join public data sources so you can analyze growth, concentration, and bank penetration by healthcare segment.

The notebooks are designed to be transparent and easy to adapt for your own market analysis.

---

## Repository structure

```text
.
├─ notebooks/
│  ├─ BEA-Import-Scripts.ipynb
│  ├─ 2024_BEA-Concordance-Updates.ipynb
│  ├─ BEA-File-Import-Growth-Analysis.ipynb
│  ├─ BLS-Establishments-Data-Prep.ipynb
│  └─ Census-SUBS-Data-Preparation.ipynb
├─ data/
│  └─ .gitkeep          # put downloaded source files here (not tracked)
├─ env/
│  └─ requirements.txt
└─ README.md
