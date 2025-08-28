# Starbucks_Store_Location_Strategy_10 CaseCraft onwards Project Sprint Project 10

## ☕ Overview  
This project models Starbucks’ store location strategy using synthetic geospatial, demographic, and competitor data. It blends clustering, predictive modeling, and strategic visualization to guide expansion planning.

## 🎯 Objective  
To identify optimal zones for new Starbucks stores by analyzing income, population density, and competitor proximity.

## 🗺️ Dataset & Features  
- Stores: 300 synthetic locations  
- Features: latitude, longitude, income, population density, distance to nearest competitor  
- Target: `success` (binary flag for store performance)

## 📊 Visual Explorations  
- Scatterplot: Store locations by success  
- Scatterplot: Income vs Density (colored by success)  
- Histogram: Competitor distance distribution  
- Clustering: K-Means on income, density, competitor distance  
- Heatmap: Confusion matrix for success prediction  
- Bar chart: Feature importance

## 🔍 Clustering & Modeling  
- Clustering: 4 location archetypes based on income, density, and competitor distance  
- Model: Random Forest Classifier  
- Features: income, density, competitor distance  
- Performance:  
  - High accuracy confirmed via confusion matrix  
  - Feature importance: income > density > competitor distance

## 🧠 Key Insights  
1. **Success Drivers**: High income and density, low competitor proximity  
2. **Clustering Utility**: Reveals distinct store archetypes for targeted expansion  
3. **Model Accuracy**: Strong predictive performance on synthetic data  
4. **Feature Importance**: Income dominates success prediction  
5. **Strategic Zones**: Visualizations highlight optimal placement regions

## ✅ Final Conclusion  
Starbucks can optimize store placement by targeting high-income, high-density zones with minimal competitor presence. This project offers a modular framework for site selection, clustering, and predictive modeling—ideal for data-driven expansion and strategic planning.