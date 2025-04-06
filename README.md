# ⚡ Distribution Network Analysis: Capacity Planning for Electric Vehicle (EV) Adoption

This project focuses on analyzing electricity distribution networks in the context of growing Electric Vehicle (EV) adoption. By leveraging Python libraries and geospatial analysis, it aims to assess current capacity, identify bottlenecks, and propose optimal strategies for network upgrades.

## 📌 Objectives

- Assess the capacity of existing electrical distribution networks.
- Identify bottlenecks and inefficiencies.
- Optimise upgrade strategies using data-driven methods.
- Provide actionable recommendations to support EV infrastructure expansion.

## 🧪 Methodology

1. **Data Import and Cleaning**  
   - Standardize and preprocess consumption, capacity, and spatial data.

2. **Exploratory Data Analysis (EDA)**  
   - Visualize consumption patterns and spatial distribution of substations and EV stations.

3. **Network Capacity Assessment**  
   - Evaluate current load vs capacity using consumption-to-capacity ratio.

4. **Optimising Network Upgrades**  
   - Identify critical points in the network needing reinforcement or expansion.

5. **Correlation Analysis**  
   - Examine relationships between EV counts, energy usage, and network strain.

## 📊 Key Insights

- **Average Consumption:** ~506 kWh, with higher outliers indicating variable demand.
- **Vehicle Type:** Electric scooters are the most prevalent, predominantly used by commercial clients.
- **Usage Pattern:** Daily charging results in consistent daily load patterns.
- **Spatial Mismatch:** Charging stations are frequently located far from substations.
- **Capacity Buffer:** Most substations operate below 50% of their capacity.
- **Correlation:** No direct link found between EV numbers and consumption-to-capacity ratio.

## ✅ Recommendations

- **Transmission Line Upgrades:** Prioritise areas with significant distance between charging stations and substations.
- **Geospatial Analysis:** Use GIS tools to identify optimal locations for new substations.
- **Advanced Monitoring:** Implement real-time systems for network health and performance tracking.
- **Cost-Benefit Analysis:** Assess financial and operational impacts of different upgrade strategies.
- **Customer Engagement:** Work with end-users to ensure infrastructure meets real-world needs.

## 🛠️ Tools & Libraries

- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Visualization  
- `geopandas`, `folium` – Geospatial analysis  
- `scikit-learn` – Correlation and modeling  
- `networkx` – Network structure representation (optional, depending on usage)

## 📁 Repository Structure

```
📦distribution-network-analysis
 ┣ 📂data/                  # Raw and processed data files
 ┣ 📂notebooks/             # Jupyter Notebooks for analysis
 ┣ 📂scripts/               # Python scripts for modular processing
 ┣ 📄README.md              # Project documentation
 ┗ 📄requirements.txt       # Python dependencies
```

## 📌 Future Work

- Integrate real-time data from IoT devices.
- Simulate future load scenarios based on EV market growth projections.
- Expand support for renewable energy input and storage systems.

## 📬 Contact

For questions or collaborations, please reach out via mariamfalabi409@gmail.com or open an issue in the repository.
