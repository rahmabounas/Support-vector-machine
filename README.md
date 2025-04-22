# 🚗 Electric Vehicle Price Prediction using Support Vector Machines (SVM)

## 📌 Project Overview

This project focuses on building a **Support Vector Regression (SVR)** model to estimate the **expected market price** of electric vehicles. Using a real-world dataset provided by the **Washington State Department of Licensing**, we apply machine learning techniques to predict prices based on vehicle characteristics and registration details.

> 🎯 **Objective**:  
> _"Given the make, model, year, and other vehicle attributes, estimate its expected market price."_

---

![Electric Vehicle Banner](https://i.imgur.com/IpuCW3s.jpg)

## 📂 Dataset Summary

The dataset includes over 100,000 records of **Battery Electric Vehicles (BEVs)** and **Plug-in Hybrid Electric Vehicles (PHEVs)** registered in Washington State.

- **Source**: [Data.gov - WA State EV Population](https://catalog.data.gov/dataset/electric-vehicle-population-data)
- **Hosted On**: Kaggle (Private Competition)

---

## 🧾 Key Features

| Feature Name | Description |
|--------------|-------------|
| `VIN (1-10)` | First 10 characters of Vehicle Identification Number |
| `County`, `City`, `ZIP Code` | Owner’s geographic information |
| `Model Year`, `Make`, `Model` | Vehicle production and branding |
| `Electric Vehicle Type` | BEV or PHEV |
| `CAFV Eligibility` | Clean Fuel Vehicle Program eligibility |
| `Electric Range` | Max range on electric power |
| `Base MSRP` | Manufacturer’s Suggested Retail Price |
| `Expected Price` | ✅ Target variable (training data only) |

⚠️ **Note**: High-cardinality fields like `VIN` or `DOL Vehicle ID` and others were excluded from modeling.

---

## 🧠 Machine Learning Approach

- **Problem Type**: Supervised Regression
- **Algorithm Used**: `SVR` from `scikit-learn`
- **Target Variable**: `Expected Price`
- **Metrics Evaluated**: RMSE, MAE

---

## 🧠 Technical Highlights

- Utilized **Pipelines** for modular preprocessing and model training.
- Compared **kernel functions** (`rbf`, `poly`) for optimal performance.
- Emphasized **feature scaling**, critical for SVM-based models.

---

## 📎 References

- 📘 [Scikit-learn Documentation – SVR](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)
- 🗂️ [Dataset Source - Data.gov](https://catalog.data.gov/dataset/electric-vehicle-population-data)

---

## 💼 About the Author

This project was completed as part of a machine learning curriculum checkpoint. It demonstrates skills in **data preprocessing**, **regression modeling**, **hyperparameter tuning**, and **pipeline construction**—all essential for real-world data science applications.

---

## 📬 Contact

Feel free to connect if you'd like to discuss the project or explore potential collaboration opportunities!

> **Bounas Rahma** – Data Science Student  
> [LinkedIn](https://www.linkedin.com/in/rahmabounas/) | [GitHub](https://github.com/rahmabounas) | [Email](bounasrahma@gmail.com)

