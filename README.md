# Wildfire-Equity-Impact-Project

**Using WatchDuty wildfire data to identify and address inequities in evacuation systems before real wildfires occur.**

---

## 📌 Project Overview

This project develops a **reproducible framework** to measure and visualize disparities in wildfire evacuation systems using:

- **Evacuation Equity Index (EEI)** — combining alert latency, coverage, and community vulnerability.
- **Prescribed Fires as Stress Tests** — using past controlled burns to detect inequities before emergencies.
- **Interactive Dashboards** — to help agencies prioritize interventions in vulnerable tracts.

📝 Target audience: Public agencies, fire responders, and community organizations aiming to pilot equity-centered evacuation improvements within 1–2 fire seasons.

---

## 📁 Repository Structure
notebooks/ ← Jupyter notebooks for each analysis phase  
src/ ← Reusable helper functions (geospatial, visualization, etc.)  
data/ ← Raw & processed datasets (not tracked if large)  
dashboard/ ← Prototype dashboard (Streamlit/Dash)  
reports/ ← Paper drafts, figures, policy briefs  
docs/ ← Methodology, references, data dictionary  

---

## 🧰 Key Dependencies
1. pandas, geopandas, shapely, rasterio, rasterstats
2. matplotlib/ plotly/ folium for visualization
3. streamlit for dashboard
4. scikit-learn (optional) for clustering or anomaly detection

---

## 🔐 Data
1. **WatchDuty wildfire** alerts, perimeters, and evacuation zones
2. **CDC/ATSDR SVI** for social vulnerability
3. **US Census ACS** for language, mobility and income data

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/wildfire-equity-project.git
cd wildfire-equity-project

# Create virtual environment
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
```

---

## 📝 Citation
If you use this framework, please cite:  
Lahkar, S., [Year]. Evacuation Equity Index & Prescribed Fire Stress Tests: A Reproducible Framework for Wildfire Resilience.

---

## 🤝 Acknowledgements
1. **WatchDuty** for real-time wildfire data
2. **CDC SVI/ US Census Bureau** for vulnerability datasets





