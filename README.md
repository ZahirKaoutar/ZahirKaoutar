<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./light.svg">
    <img src="./dark.svg" alt="Kaoutar Zahir (كوثر زهير) — Full Stack Web &amp; AI Engineer" width="100%">
  </picture>
</div>

<br>

<div align="center">
  <a href="https://github.com/ZahirKaoutar"><img src="https://img.shields.io/badge/GitHub-58%20Public%20Repos-00A8FF?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repos"></a>
  <a href="https://www.linkedin.com/in/kaoutar-zahir-39a024284/"><img src="https://img.shields.io/badge/LinkedIn-Kaoutar%20Zahir-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:zahirkaoutar2003@gmail.com"><img src="https://img.shields.io/badge/Email-zahirkaoutar2003%40gmail.com-D44C4C?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Safi%2C%20Morocco-B4532A?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Pre--Hiring-059669?style=for-the-badge&logo=checkmark&logoColor=white" alt="Status">
</div>

---

### 🏛️ The Intelligence Archive // Kaoutar Zahir

> *"I turn data into intelligence and ideas into systems."*

Hi 👋, I'm **Kaoutar Zahir** (`كوثر زهير`), an **AI / Machine Learning Engineer & Full Stack Developer** based in **Safi, Morocco** (Mobility: Marrakech and Remote). 

Holding an Associate Degree in Digital Development (**ISTA NTIC Bac+2**) and currently engineering full-stack architectures and machine learning systems at **YouCode-UM6P** (2025–2027). I bridge the gap between rigorous statistical modeling and production software: from scikit-learn & deep learning vision architectures to Medallion data pipelines and robust web systems.

---

### 🔬 Curated Engineering Repertoire (4 Major Volumes)

```text
VOLUME 01 ─── [ML / DATA SCIENCE]     Student Mental Health Risk Prediction (~77% CV Acc, Airflow DAG, Streamlit)
VOLUME 02 ─── [FULL STACK / HEALTH]   BloodConnect — Blood Donation Logistics (Laravel 11, Vue.js, FIFO Stock Ledger)
VOLUME 03 ─── [DATA ENGINEERING]      MétéoRisk — Morocco Meteorological Lakehouse (Medallion B/S/G, Airflow, PostgreSQL)
VOLUME 04 ─── [DEEP LEARNING / VISION] BrainScan AI — MRI Neuroimaging Classifier (TensorFlow/Keras CNN, 4 Classes)
```

#### [01. Student Mental Health Risk Prediction](https://github.com/ZahirKaoutar/Sante-mentale-etudiant)
* **Category**: Machine Learning & MLOps
* **Stack**: Python, Scikit-learn, Apache Airflow, Streamlit, Pandas, NumPy, Docker
* **Architecture**: Cohort analysis of 2,000 university students across 17 behavioral dimensions. Preprocessing pipeline using Scikit-Learn `ColumnTransformer` (standard scaling, one-hot encoding). Benchmarked Decision Tree (55.4%), Random Forest (68.8%), and Gradient Boosting (70.3%) against optimized **Logistic Regression (~77.0% CV Accuracy, 0.77 Macro F1)**. Deployed with an interactive Streamlit UI (`app/app.py`) and scheduled via an Apache Airflow MLOps DAG (`dag/mental_health_dag.py`).

#### [02. BloodConnect — Healthcare Logistics](https://github.com/ZahirKaoutar/SangBanque)
* **Category**: Full Stack Development & Distributed Logistics
* **Stack**: Laravel 11, PHP, Vue.js, PostgreSQL/MySQL, Docker, REST APIs
* **Architecture**: Role-based coordination system with 4 distinct portals (Donors, Hospitals, Blood Donation Centers, Administrators). Enforces statutory donation interval checks (56 days), blood stock inventory across 8 blood groups (`A+`, `A-`, `B+`, `B-`, `AB+`, `AB-`, `O+`, `O-`), and automated expiration monitoring using strict FIFO (First In, First Out) dispensation.

#### [03. MétéoRisk — Meteorological Lakehouse](https://github.com/ZahirKaoutar/marocco_weather_pipeline)
* **Category**: Data Engineering & Climate Risk Analytics
* **Stack**: Apache Airflow, Python, PostgreSQL, Streamlit, Plotly Express, ETL
* **Architecture**: Automated data pipeline implementing the industry-standard **Lakehouse Medallion Architecture**:
  * **Bronze Tier**: Date-partitioned raw JSON snapshots (`data/bronze/`)
  * **Silver Tier**: Schema validation, deduplication, and missing value treatment (`data/silver/`)
  * **Gold Tier**: Feature engineering and aggregated regional risk indices (`data/gold/`)
  * **Orchestration**: Daily Airflow DAG (`dags/meteorisk_pipeline.py`) loading cleaned data into PostgreSQL and serving interactive Plotly maps in Streamlit (`dashboard/app.py`).

#### [04. BrainScan AI — Neuroimaging Deep Vision](https://github.com/ZahirKaoutar/cerveaux)
* **Category**: Deep Learning & Computer Vision
* **Stack**: Python, TensorFlow, Keras, CNN, OpenCV/PIL, NumPy, Streamlit
* **Architecture**: Deep Convolutional Neural Network (CNN) trained on brain MRI neuroimaging scans to classify and detect brain tumors across four distinct classes: **Glioma, Meningioma, Pituitary Tumor, and No Tumor (Healthy)**. Resizes and normalizes images to 224×224 tensors with real-time Softmax confidence distribution visualizers in Streamlit (`src/app.py`).

---

### 💼 Verified Professional Experience

* **INVENEO | Full Stack Developer Intern** *(May 2026 – July 2026 • Marrakech)*
  * Built *Job Portal*, a LinkedIn-inspired recruitment web platform (job postings, candidates, company profiles).
  * Developed employer analytics dashboard with real-time statistics, modular admin interface, and containerized REST APIs.
  * *Technologies*: `Node.js`, `Vue.js`, `PostgreSQL`, `Docker`, `Tailwind CSS`, `JavaScript`

* **Province de Safi | Python Developer Intern** *(July 2024 – August 2024 • Safi)*
  * Developed a standalone desktop software application to automate official administrative document generation and printing workflows.
  * *Technologies*: `Python`, `PDF Generation`, `Desktop UI`, `Git`

* **Sabri Joud | Laravel Developer Intern** *(April 2024 – May 2024 • Safi)*
  * Designed and built an e-commerce web platform with catalog management, cart flows, and an intuitive admin backoffice using Filament and Livewire.
  * *Technologies*: `Laravel`, `PHP`, `Livewire`, `Filament`, `JavaScript`, `MySQL`

---

### 🛠️ Verified Technical Repertoire

```text
┌───────────────────────────┬────────────────────────────────────────────────────────┐
│ DOMAIN                    │ PRACTICED TECHNOLOGIES                                 │
├───────────────────────────┼────────────────────────────────────────────────────────┤
│ AI & Machine Learning     │ Python, Scikit-learn, TensorFlow, Keras, CNN, YOLOv8,   │
│                           │ Pandas, NumPy, GridSearchCV, Macro F1, Streamlit       │
├───────────────────────────┼────────────────────────────────────────────────────────┤
│ Back-End & Architecture   │ Laravel, PHP, Livewire, Filament, Node.js, Python,     │
│                           │ Langage C, RESTful APIs, OOP, Design Patterns          │
├───────────────────────────┼────────────────────────────────────────────────────────┤
│ Front-End & Interfaces    │ Vue.js, React, JavaScript (ES6+), TypeScript,          │
│                           │ Tailwind CSS, HTML5, CSS3, Bootstrap                   │
├───────────────────────────┼────────────────────────────────────────────────────────┤
│ Databases & Storage       │ PostgreSQL, MySQL, MongoDB, SQLite, Relational Schemas │
├───────────────────────────┼────────────────────────────────────────────────────────┤
│ Data & DevOps             │ Apache Airflow, Medallion Architecture, Docker,        │
│                           │ Git & GitHub (58 Repos), UML, Jira, Agile (Scrum)      │
└───────────────────────────┴────────────────────────────────────────────────────────┘
```

---

### 🎓 Academic Trajectory

* **YouCode - UM6P Safi** *(2025 – 2027, In progress)* : Full Stack Web Development & Artificial Intelligence
* **ISTA NTIC Safi** *(2022 – 2024)* : Specialized Technician in Digital Development (Bac+2)
* **Lycée El Hidaya Issalmiya Safi** *(2021 – 2022)* : High School Diploma in Physical Sciences

---

### 📬 Connect & Collaborate

* **Email**: [zahirkaoutar2003@gmail.com](mailto:zahirkaoutar2003@gmail.com)
* **Phone**: `+212 7 71 96 29 60`
* **LinkedIn**: [linkedin.com/in/kaoutar-zahir](https://www.linkedin.com/in/kaoutar-zahir-39a024284/)
* **GitHub**: [@ZahirKaoutar](https://github.com/ZahirKaoutar)
* **Portfolio**: [The Intelligence Archive](https://github.com/ZahirKaoutar/portfolio)

---

<div align="center">
  <sub>Generated with engineering rigor for Kaoutar Zahir · The Intelligence Archive</sub>
</div>
