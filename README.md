# 🌾 Climate Change Impact on Agriculture – 2024

This project analyzes how climate change variables affect global agricultural productivity using Tableau. The dashboard provides insights into the impact of rising temperatures, precipitation patterns, CO₂ emissions, and adaptive strategies on crop yields and economic performance.

---

## 📦 Project Overview

- **Toolset**:
  - **Tableau Desktop** – for visualization
  - **Tableau Cloud + Bridge** – for scheduled automated refreshes
  - **Tableau Prep** – for data cleaning and transformation

- **Dataset**:
  - 10,000 records (1998–2024)
  - Fields include: Temperature, Precipitation, CO₂ Emissions, Crop Yield, Extreme Weather, Soil Health, Fertilizer/Pesticide Use, Adaptation Strategy, and Economic Impact

---

## 🎯 Project Goals

- Analyze the relationship between climate factors and crop yields
- Measure economic loss due to climate change by region
- Highlight trends in adaptation strategies across countries
- Identify policy-relevant insights for sustainable agriculture

---

## 🧼 Data Preparation

Performed using **Tableau Prep**:
- Removed nulls and outliers
- Unified naming conventions across regions and countries
- Normalized numerical columns for clean trendline analysis

---

## 📊 Visual Insights

| 📍 Visualization                | 🔍 Insight |
|-------------------------------|------------|
| **Global Heatmap**            | Visualizes regions with highest climate-induced economic losses |
| **Crop Yield vs Temperature** | Shows weak correlation in current data |
| **Precipitation Patterns**    | No significant linear correlation found |
| **Adaptation Strategy Map**   | Highlights regions adopting irrigation or rotation strategies |
| **Soil Health vs Fertilizer** | Excess fertilizer use linked with declining soil health |

---

## 📈 Data Analysis – R² Accuracy

> While Tableau is not designed for predictive modeling, trend-based linear analysis was performed for core variable pairs:

| Relationship                            | R² Score | Interpretation |
|-----------------------------------------|----------|----------------|
| Crop Yield vs Temperature               | 0.07     | Weak linear trend |
| Crop Yield vs Precipitation             | 0.001    | No linear correlation |
| CO₂ Emissions vs Economic Impact        | 0.003    | No significant linear relationship |

> These scores indicate that simple linear models are **not effective predictors** for this dataset. Relationships may be **non-linear** or influenced by **combined variables**.

---

## ☁️ Cloud & Automation

- Dashboards are hosted on **Tableau Cloud**
- **Automated refreshes** handled via Tableau Bridge
- Stakeholders can access live dashboards without manual updates

---

## 🧠 Key Takeaways

- Climate impact on agriculture is **complex and region-dependent**
- Linear trends in this dataset are minimal, suggesting need for **advanced modeling**
- Soil health and economic impact are influenced by **management practices** more than single climate variables
- **Adaptation strategies** vary significantly across regions

---


---

## 🚀 Future Enhancements

- Integrate **machine learning models** for non-linear prediction
- Add **real-time weather API feeds**
- Deploy with **Tableau Public** for broader access
- Create an interactive policy impact simulation tool

---

## 🙏 Acknowledgements

- Food and Agriculture Organization (FAO)
- Intergovernmental Panel on Climate Change (IPCC)
- Tableau for data visualization capabilities

---

## 📬 Contact

Created by: **Harshavardhan Reddy Chamakura**  
Email: chamakharsha10@gmail.com  
  



