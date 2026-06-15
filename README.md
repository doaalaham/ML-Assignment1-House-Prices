# ML-Assignment1-House-Prices
Steps Completed:
1. **Data Retrieval**: Loaded train and test sets, managed memory by downcasting float variables and converting categories.
2. **Data Cleaning**: Filled specific "NaN" values with 'None' (e.g., PoolQC, Alley), imputed other missing values using the median, removed outliers in GrLivArea, and normalized SalePrice using log transformation.
3. **EDA**: Visualized correlation heatmap for top 5 features, created scatter plots for GrLivArea against SalePrice, and analyzed prices across neighborhoods.
4. **Feature Engineering**: Engineered a new feature `TotalSF` and applied Label Encoding and One-Hot Encoding consistently to avoid data leakage.
