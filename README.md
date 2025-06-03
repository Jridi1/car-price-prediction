# 🏎️ Car Price Analysis & Prediction

This project focuses on analyzing a dataset of used cars and building a simple predictive model to estimate **selling prices** based on various car features.

The goal is to understand feature relationships, clean and preprocess the data, perform visual exploration, and implement a **Linear Regression model** to predict car prices.

---

## 📂 Project Structure

- `Car_Price_Analysis_Abderrahim.ipynb`: Main Jupyter Notebook containing EDA, preprocessing, modeling, and evaluation
- `cars.csv`: Dataset (not included here for licensing reasons)
- `README.md`: Project documentation (this file)

---

## 🔍 Objectives

- Explore key attributes affecting car prices (e.g. mileage, fuel type, power)
- Detect and handle missing values
- Engineer features and encode categorical data
- Visualize relationships and correlations
- Train and evaluate a **Linear Regression** model
- Predict the price of a new car

---

## 📈 Key Insights

- **Selling price** is highly correlated with `max_power` and `engine`
- Cars with more previous owners tend to sell for less
- Outliers are present in price, mileage, and power — identified via boxplots
- Categorical variables such as `fuel`, `transmission`, and `owner` significantly influence pricing

---

## ⚙️ Technologies Used

- **Languages**: Python (Pandas, NumPy, Seaborn, Matplotlib)
- **Modeling**: Scikit-learn (Linear Regression)
- **Notebook**: Jupyter (.ipynb)

---

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/car-price-analysis.git
   cd car-price-analysis
   ```

2. Install dependencies (optional):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Car_Price_Analysis_Abderrahim.ipynb
   ```

4. Replace or add your own `cars.csv` dataset file in the same directory.

---

## 🔮 Prediction Example

The notebook ends with a sample prediction for a new car using this input format:
```python
new_car = [[73000, 0, 0, 0, 1, 45, 2775, 86, 2, 9]]
```
This array represents a car’s numerical features (e.g. mileage, fuel, transmission, power, age...).

---

## 👤 Author

**Abderrahim Jridi**  
[LinkedIn](https://www.linkedin.com/in/abderrahim-jridi)  
Email: abderrahim.jridi@gmail.com

---

> “Data is the new oil, but only if refined.”  
Let’s build better decisions with clean, structured, and intelligent data.
