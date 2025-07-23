
# 📡 telecom-site-ml
### Machine Learning on Telecommunication Site Data (Cell Towers – Iran)

---

### 📌 Overview
This project explores the application of **machine learning** on anonymized telecom cell site data.  
We use clustering and classification to understand, group, and predict behavior of telecom towers based on geographical and technical attributes.

---

### 🎯 Goals
- 🔍 Cluster similar telecom sites based on signal and location
- 🤖 Build ML models to classify site types or configurations
- 🗺️ Visualize site distributions and clusters on the map
- 🧪 Use the project as a portfolio for AI + Telecom integration

---

### 🗂 Dataset
The dataset contains real-world telecom site data (anonymized).  
**Columns include:**
- `site_code` – anonymized unique code
- `site_name` – randomized name
- `latitude`, `longitude` – GPS coordinates (with slight noise)
- `calculated_amp` – signal amplitude estimation
- `site_type`, `RRU_model` – technical parameters

> All sensitive data is randomized to be suitable for public repositories.

---

### 🛠️ Technologies
- Python (pandas, scikit-learn, seaborn, folium, plotly)
- Clustering: KMeans, DBSCAN, Agglomerative
- Classification: RandomForest, XGBoost
- Visualization: Plotly, Folium, Matplotlib

---

### 📁 Folder Structure
```
📂 data/              → anonymized datasets (Excel / CSV)  
📂 notebooks/         → EDA, clustering, classification notebooks  
📂 scripts/           → preprocessing and modeling code  
📄 README.md  
📄 requirements.txt   → dependencies  
```

---

### 🔮 Next Steps
- [ ] Add clustering visualizations  
- [ ] Build classification model  
- [ ] Streamlit dashboard for real-time interaction  
- [ ] Kaggle + LinkedIn publication

---

### 👤 Author  
**Mehdi Sahraei**  
Network & Computer Engineer | AI/ML Enthusiast  
📍 Ilam, Iran  
📧 [Your Email] | 💼 [LinkedIn Profile] | 🌐 [Your Blog]
