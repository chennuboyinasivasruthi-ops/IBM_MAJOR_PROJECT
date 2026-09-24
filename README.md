# Hospital Performance Intelligence System (MedTrack_DV)
### IBM SkillsBuild Data Analytics with AI Academic Internship Program

## 👥 Student Information
* **Student Name:** CHENNUBOYINA SIVA SRUTHI
* **College:**SESHADRI RAO GUDLAVALLERU ENGINEERING COLLEGE
* **Year of Study:** 3rd Year B.Tech (Batch 2024-2028)
* **Domain:** Data Analytics with AI

---

## 📋 Project Overview
The **Hospital Performance Intelligence System** is an advanced operational and clinical analytics pipeline engineered to optimize hospital performance, bed capacity tracking, financial distributions, and healthcare delivery metrics. Utilizing an engineered dataset of **10,000 patient records across 77 features**, this project processes core raw clinical matrices into high-utility transactional layers explicitly calibrated for rapid visualization inside business intelligence engines like Tableau and Power BI.

---

## 📊 Core Engineered KPIs
The dataset incorporates deep algorithmic calculations across the following target parameters:
1. **Total Admissions:** 10,000 unique records.
2. **Average Length of Stay (LOS):** 20.4 days (clipped within a realistic operational window of 1-30 days).
3. **Readmission Rate:** 50.0% baseline validation metric mapped from clinical diagnosis records.
4. **Bed Occupancy Rate:** 37.0% mean strategic resource loading.
5. **ICU Utilization Rate:** 53.0% localized department load ratio.
6. **Staff Utilization Rate:** 58.0% workforce efficiency profile factor.
7. **Equipment Utilization Rate:** 34.0% functional baseline matrix.
8. **Patient Transfer Rate:** 18.0% inter-departmental routing velocity.
9. **Department Efficiency Score:** 99.66 baseline administrative operational score.

---

## 📁 Repository Structure
```text
MedTrack_DV/
├── 📁 dashboard/
│   ├── 📊 MedTrack_DV_Dashboard.pbix    # Polished Power BI UI Dashboard Asset
│
├── 📁 data/
│   ├── 📄 hospital_raw_data.csv        # Baseline transactional raw feed
│   ├── 📄 hospital_cleaned.csv         # Intermediate clean dataset
│   └── 📁 hospital_final_dataset.xlsx  # Fully calculated data analytics layer
├── 📁 docs/
│   ├── 📝 CHENNUBOYINA SIVA SRUTHI_ProjectReport.docx# Comprehensive clinical report mapping
│    
└── 📁 scripts/
    ├── 编程 data_collection.py         # Baseline data scan framework
    ├── 📓 CHENNUBOYINA SIVA SRUTHI_Hospital Performance Intelligence System (MedTrack_DV).ipynb      # Notebook containing ingestion and cleaning scripts
    └── 编程 generate_hospital_kpis.py     # Pandas metrics calculation engine
```

---

## 🛠️ Technological Stack & Environment
* **Language/Platform:** Python 3.11.5 via Jupyter Notebook environment
* **Libraries Utilized:** Pandas, NumPy, Matplotlib, Seaborn, Pathlib
* **BI Target Integration:** Power BI Desktop / Tableau Public Dashboard

---

## 🚀 Installation & Local Environment Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/chennuboyinasivasruthi-ops/IBM_MAJOR_PROJECT.git
   cd IBM_MAJOR_PROJECT
   ```

2. **Install Target Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute Core Data Pipeline Engine:**
   ```bash
   python scripts/generate_hospital_kpis.py
   ```

4. **Bi Engine Deployment:** Ingest the calculated `hospital_final_dataset.xlsx` from the data folder directly into Power BI to access operational visualization interfaces.