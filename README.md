# Crime Prediction in London’s LSOAs Using STGNN-ZINB

## Project Overview
This dissertation project develops a **spatio-temporal graph neural network with zero-inflated negative binomial distribution (STGNN-ZINB)** to predict crime counts across **4,835 LSOAs (Lower Super Output Areas) in London**. The model captures both **spatial dependencies and temporal trends**, while handling **excess zero counts** in crime data. The aim is to enable more accurate, fine-grained crime forecasting and support informed resource allocation for law enforcement and city planning.

## Key Features
- Predicts crime counts at the LSOA level in London.
- Uses **STGNN-ZINB** to handle spatio-temporal dependencies and zero-inflation.
- Provides **actionable insights** into crime trends over time.
- Visualizations for spatial distribution and temporal patterns of crime.

## Methodology
1. **Data Collection:** Crime records aggregated at the LSOA level.
2. **Data Preprocessing:** Handling missing values, zero-inflated counts, and normalization.
3. **Modeling:**  
   - Constructed a **spatio-temporal graph neural network**.  
   - Modeled counts with **zero-inflated negative binomial distribution**.
4. **Evaluation:**  
   - Metrics: RMSE, MAE, and goodness-of-fit.  
   - Visualized predictions vs. actual crime counts across LSOAs.

## Results
- The model effectively predicts high-risk areas and captures both spatial and temporal trends.
- Zero-inflated modeling improves accuracy for areas with rare or no crimes.
- Provides insights for **resource allocation, policy planning, and preventive measures**.

## Tools & Libraries
- Python 3.x  
- PyTorch / TensorFlow (for GNN implementation)  
- Pandas, NumPy, SciPy  
- Matplotlib, Seaborn, Geopandas  
- NetworkX (for graph construction)  

## License
All rights reserved. This code and model are **proprietary** and cannot be copied, distributed, or modified without explicit written permission from the author.

## Author
**Khit Si Thu**  
Dissertation Project 
