# 🏡 House Price Prediction using Linear Regression

This project uses **Linear Regression** to predict house prices based on various features from a housing dataset. It covers end-to-end data processing, exploratory data analysis, model building, and evaluation.

---

## 📂 Dataset

The dataset used contains features such as:
- Area
- Number of Bedrooms, Bathrooms, Stories, Parking
- Presence of Main Road, Guest Room, Basement
- Hot Water Heating, Air Conditioning
- Preferred Area, Furnishing Status
- **Target Variable**: Price

Dataset was imported as:
```python
housing = pd.read_csv("/content/Housing_final_dataset.csv")
