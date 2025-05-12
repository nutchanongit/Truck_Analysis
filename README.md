# 📦 Carbon Emission and Speed Pattern Analysis in Freight Transport  
**Using GPS Data and Machine Learning**

## 🧠 Objective
Analyze GPS tracking data from freight trucks operating around **Laem Chabang Port, Thailand**, to:

- Estimate **baseline CO₂ emissions** from road freight activity  
- Identify **spatial patterns** of truck behavior using **unsupervised learning (DBSCAN)**  
- Support planning for **low-carbon and efficient logistics systems**

## 🛠️ Tools & Technologies
- **Python** (Pandas, GeoPandas, Scikit-learn, Matplotlib, Folium)  
- **Machine Learning**: DBSCAN Clustering  
- **Geospatial Analysis**: GPS data, road network mapping  
- **Emissions Modeling**: Using national standard emission coefficients (TGO)

## 🔧 Methodology

### 1. Data Preprocessing
- Cleaned and validated large-scale GPS datasets from freight trucks  
- Filtered out missing, duplicate, and noisy records (e.g., abnormal speeds or out-of-bound coordinates)  
- Segmented trip paths by vehicle ID and timestamp for chronological analysis

### 2. Speed Behavior Clustering
- Applied **DBSCAN** to GPS points to detect clusters of **low-speed** and **high-speed** movement  
- Mapped spatial clusters to visualize congestion-prone or efficient areas  
- Interpreted speed zones relative to industrial zones, port access, and highways

### 3. CO₂ Emissions Estimation
- Calculated trip distances and average speeds using timestamped location data  
- Estimated CO₂ output using published emission factors (grams CO₂ per ton-kilometer)  
- Generated a **baseline emissions profile** for current road transport operations

## 📂 Deliverables
- Structured and cleaned GPS dataset  
- Python notebooks for clustering, visualization, and emissions modeling  
- Emission baseline report to support future modal shift or policy planning  
