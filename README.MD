# 🌾 AI-Based Crop Yield Prediction and Agricultural Production Analysis

## 📌 Project Overview

This project was developed as part of the **Fundamentals of AI Using Agriculture Data Set** course offered by **ANNAM.AI – Centre of Excellence, IIT Ropar**.

The project uses the **All India Crop-wise Area, Production & Yield** dataset published by the **Department of Agriculture & Farmers Welfare, Government of India** to analyze historical agricultural trends and predict crop yield using Machine Learning techniques.

The objective is to demonstrate how Artificial Intelligence can support data-driven agricultural planning by analyzing crop-wise area, production, and yield data collected over multiple years.

---

# 🎯 Objectives

- Analyze historical agricultural data.
- Perform data preprocessing and cleaning.
- Explore agricultural trends using visualizations.
- Build Machine Learning models for crop yield prediction.
- Compare multiple regression algorithms.
- Select the best-performing model.
- Evaluate model performance using standard regression metrics.

---

# 📂 Dataset

**Dataset Name**

> All India Crop-wise Area, Production & Yield

**Source**

Department of Agriculture & Farmers Welfare  
Government of India

---

## Dataset Summary

| Attribute | Value |
|-----------|------:|
| Records | 98 |
| Columns | 17 |
| Crops | 34 |
| Seasons | 4 |
| Years | 2021–22 to 2025–26 |

---

## Dataset Features

### Categorical Features

- Crop
- Season

### Numerical Features

- Area (2021–22 to 2025–26)
- Production (2021–22 to 2025–26)
- Yield (2021–22 to 2025–26)

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset structure
- Identified missing values
- Checked duplicate records
- Converted numerical columns
- Filled missing values using the median
- Encoded Crop using Label Encoding
- Encoded Season using Label Encoding

---

# 📊 Exploratory Data Analysis

The following visualizations were generated:

- Crop Distribution
- Season Distribution
- Average Yield by Crop
- Production by Year
- Area vs Production
- Yield Trend
- Correlation Heatmap
- Boxplot
- Histogram
- Average Cultivated Area by Crop

---

# 🤖 Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

---

# ⚙️ Feature Engineering

## Input Features

- Crop
- Season
- Year
- Area-2025-26
- Production-2025-26

## Target Variable

- Yield-2025-26

---

# 📈 Model Evaluation

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

# 🏆 Results

| Model | R² Score |
|---------|----------:|
| Linear Regression | -2.4747 |
| Decision Tree Regressor | 0.6842 |
| Random Forest Regressor | 0.8465 |
| **Gradient Boosting Regressor** | **0.9175** |

## Best Model

**Gradient Boosting Regressor**

Performance Metrics

- R² Score : **0.9175**
- MAE : **206.36**
- MSE : **62539.85**
- RMSE : **250.08**

---

# 📁 Project Structure

```text
IIT_Ropar_2026/
│
├── README.md
├── VT-RushiKannan_Agriculture_Dataset.ipynb
├── VT-RushiKannan-Project_Report.pdf
│
└── IIT_Ropar_2026/
    │
    ├── All-India_-Crop-wise-Area,-Production-&-Yield.csv
    │
    ├── models/
    │   └── best_crop_yield_model.pkl
    │
    ├── results/
    │   ├── actual_vs_predicted_yield.png
    │   ├── error_distribution.png
    │   ├── feature_importance.png
    │   └── residual_plot.png
    │
    └── IIT_Ropar_2026/
        └── results/
            ├── area_vs_production.png
            ├── average_area_by_crop.png
            ├── average_yield_by_crop.png
            ├── boxplot.png
            ├── correlation_heatmap.png
            ├── crop_distribution.png
            ├── histogram.png
            ├── production_by_year.png
            ├── season_distribution.png
            └── yield_trend.png
```

---

# 🚀 How to Run the Project

## Clone the repository

```bash
git clone https://github.com/your-username/AI-Crop-Yield-Prediction.git
```

## Change directory

```bash
cd AI-Crop-Yield-Prediction
```

## Install dependencies

```bash
pip install -r requirements.txt
```


---

# 📦 Required Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

---

# 💡 Key Insights

- Crop yield varies significantly across crops and seasons.
- Data preprocessing improves model reliability.
- Tree-based models outperformed Linear Regression.
- Gradient Boosting achieved the highest prediction accuracy.
- Historical agricultural data can be effectively used for crop yield prediction.

---

# ⚠️ Limitations

- Small dataset (98 records).
- Missing values in the 2021–22 data.
- No rainfall information.
- No soil characteristics.
- No fertilizer usage data.
- No weather-related variables.

---

# 🔮 Future Work

Possible improvements include:

- Incorporating rainfall and weather data.
- Including soil properties and fertilizer usage.
- Using larger and more recent datasets.
- Applying deep learning models.
- Developing a real-time crop yield prediction system.

---

# 📚 References

- Department of Agriculture & Farmers Welfare, Government of India
- Python Documentation
- Pandas Documentation
- Scikit-learn Documentation
- Matplotlib Documentation
- Google Colab

---

# 👨‍💻 Author

**VT Rushi Kannan**

B.Tech Artificial Intelligence & Data Science

KL University, Hyderabad

---

# 📄 License

This project was developed for educational and academic purposes as part of the **Fundamentals of AI Using Agriculture Data Set** course.