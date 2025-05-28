# Introduction-to-Machine-Learning
Lecturer and Practice teacher: Olivier Jaylet



# 🏠 Apartment Price Prediction in Kazakhstan

## 🎯 Project Goal

The aim of this project is to predict apartment prices in Kazakhstan using machine learning techniques.  
We use features such as:

- Location (latitude, longitude)
- Total square meters
- Type of renovation
- Number of rooms
- Floor level
- Year of construction

The model helps real estate buyers, sellers, and analysts better understand what affects housing prices.

---

## 📊 Dataset

The dataset includes cleaned apartment sales data from across Kazakhstan.

- Source: Scraped / aggregated dataset (CSV format)
- Target variable: `price`
- Features: `square_meters`, `location`, `floor`, `renovation`, `year_built`, etc.

---

## 🧪 Methodology

The pipeline consists of:

1. **Exploratory Data Analysis (EDA)**
   - Visualizations using Matplotlib and Seaborn
   - Interactive maps of sold apartments using GeoPandas

2. **Preprocessing**
   - Handling missing values
   - Feature encoding (LabelEncoder, CategoryEncoder)
   - Standardization with `StandardScaler`

3. **Modeling**
   - Decision Tree Regressor
   - Random Forest Regressor
   - LightGBM Regressor

4. **Evaluation Metrics**
   - RMSE (Root Mean Squared Error)
   - MAE (Mean Absolute Error)
   - R² Score
   - Explained Variance Score

5. **Model Comparison**
   - Compare performance across all models
   - Select the best-performing one based on metrics

---

## 🛠 Technologies Used

- Python
- Pandas, NumPy
- GeoPandas, Matplotlib, Seaborn
- Scikit-Learn
- LightGBM
- Jupyter Notebook

---

## 📍 Visualization Example

One map visualization shows apartment sale locations overlaid on a map of Kazakhstan using `GeoPandas`.

---

## 📈 Results

After comparing models, LightGBM showed the best overall performance in terms of both accuracy and speed.  
It captured non-linear dependencies better than Decision Trees and Random Forest in this context.

---

## 🔮 Future Improvements

- Add more detailed geospatial features (e.g., distance to city center or metro)
- Try deep learning models (e.g., Neural Networks)
- Implement cross-validation for more robust evaluation

---

## 👨‍💻 Author

- Jemenei (Suleimmen)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
