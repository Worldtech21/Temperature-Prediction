# 🌡️ Climate Temperature Prediction using XGBoost

This project leverages machine learning, specifically **XGBoost**, to predict annual temperature based on early monthly temperatures. The model is trained and evaluated on climate data, achieving high accuracy and offering insights into temperature trends.

---

## 📋 Project Overview

Predicting climate patterns is critical for understanding environmental changes. This model takes January, February, and April temperatures as inputs and predicts the annual average temperature. With an R² score of 0.79, this model demonstrates strong performance and serves as a foundation for further climate analysis projects.

---

## 📂 Dataset

Data preprocessing step is feature selection to ensure optimal model performance.
We use Powerbi to get an intuitive idea of what features might be relevant. Please findd the images in repo😊

---

## ⚙️ Model Training

The model uses **XGBoost Regressor** with hyperparameters tuned for optimal performance. The key features are January, February, and April temperatures, with the target variable being the annual temperature.

---

## 📊 Results

### Model Performance
- **Mean Squared Error (MSE)**: 0.036
- **R² Score**: 0.79

These results indicate that the model explains 79% of the variance in the target variable, with low prediction error.

### Key Insights
- Monthly temperatures have a significant impact on predicting the annual temperature.
- XGBoost captures complex patterns in climate data, making it suitable for climate-related predictions.

---

## 📈 Visualizations

Included visualizations:
1. **Feature Correlation Heatmap**: Shows relationships between input features.
2. **Residual Plot**: Visualizes the difference between predicted and actual values.
3. **Feature Importance Plot**: Highlights which months contribute most to the annual prediction.

---

## 🛠️ Future Work

Potential next steps to improve and expand the project:
- **Add Additional Monthly Temperatures**: Include more months for a richer feature set.
- **Hyperparameter Tuning**: Further optimize model parameters for even better performance.
- **Time-Series Analysis**: Explore year-over-year trends in climate data.

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy exploring climate patterns and temperature prediction with machine learning! 😊🌍
