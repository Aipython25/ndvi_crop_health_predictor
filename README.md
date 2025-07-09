# ndvi_crop_health_predictor
# 🌱 NDVI-Based Crop Health Predictor using Logistic Regression

This project uses Normalized Difference Vegetation Index (NDVI) values to predict crop health (Healthy / Weak) using Machine Learning (Logistic Regression).

## 📊 Input
- NDVI values (between 0 to 1)
- Labelled data for crop health (0 = Weak, 1 = Healthy)

## ⚙️ Tech Used
- Python
- Pandas
- scikit-learn
- Logistic Regression

## 🚀 Output
The model predicts whether the sugarcane plant is healthy or weak based on NDVI value.

### Sample Prediction:
```python
NDVI = 0.25 → ❌ Weak Crop  
NDVI = 0.65 → ✅ Healthy Crop
