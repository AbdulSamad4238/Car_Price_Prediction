# 🚗 Used Car Price Prediction

An end-to-end machine learning regression project using the **Quikr Car dataset**.  
The goal is to predict the selling price of used cars based on features such as company, year, kilometers driven, fuel type, and brand.

---

## 📌 Project Workflow
1. **Data Cleaning**
   - Handled messy values in `Price` (commas, "Ask For Price").
   - Converted `kms_driven` to numeric.
   - Fixed typecasting issues in `year`.
   - Imputed missing values.

2. **Feature Engineering**
   - Extracted `brand` from car name.
   - Created `car_age` feature.
   - Encoded categorical variables.

3. **Data Visualization**
   - Distribution of car prices.
   - Price trends by company, fuel type, and car age.
   - Boxplots, bar plots, violin plots.

4. **Modeling**
   - Train-test split.
   - Preprocessing pipeline (numeric scaling + categorical encoding).
   - Linear Regression model.
   - Evaluation using R² and RMSE.

5. **Results**
   - Achieved a reasonable R² score showing predictive capability.
   - Visualized actual vs predicted prices.

---

## 📊 Example Visualizations
- **Distribution of Car Prices**
- **Average Price by Company**
- **Car Age vs Price Scatterplot**
- **Actual vs Predicted Prices**

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/AbdulSamad4238/car-price-prediction.git
cd car-price-prediction
pip install -r requirements.txt
