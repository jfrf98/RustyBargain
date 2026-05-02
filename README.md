# 🚗 Rusty Bargain – Used Car Price Prediction

## The Business Problem

Rusty Bargain is a used-car marketplace that wants users to instantly estimate the market value of their vehicle.

To achieve this, the company needs a reliable pricing model based on historical car listings and technical specifications.

---

## My Contribution

I built and compared multiple predictive models to estimate used car prices, focusing on three key factors:

- Accuracy (How close predictions are to real prices)
- Training time (How long the model takes to learn)
- Prediction speed (How fast it can return results in an app)

---

## What I Did

- Built a full ML pipeline (avoiding data leakage)
- Applied preprocessing (scaling + encoding)
- Compared multiple models:
    - Linear Regression (baseline)
    - Decision Tree
    - Random Forest
    - LightGBM

---

## Tools Used

Python | Scikit-learn | LightGBM | Pandas | NumPy | Matplotlib | Seaborn

---

## Results

- Linear Regression struggled → RMSE ≈ 3200
- Random Forest achieved the best accuracy → RMSE ≈ 1750 and training time ≈ 8 minutes
- LightGBM delivered similar performance with drastically lower training time (~1–2 seconds)

(RMSE represents the average difference between predicted and real car prices — lower is better.)

---

## Why This Project Matters

This project demonstrates my ability to:

- Translate a business problem into a predictive solution
- Work with messy real-world data
- Compare models strategically (not just technically)
- Balance accuracy with performance constraints
- Deliver solutions suitable for production environments

---

