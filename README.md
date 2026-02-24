# 🐄 DigiCow Farmer Adoption Prediction

## 📌 Problem

Predict probability of adoption within:
- 7 days
- 90 days
- 120 days

Evaluation:
- 75% LogLoss
- 25% ROC-AU

## ⚠ Challenges

- Imbalanced dataset (~2%)
- Temporal drift (2024 → 2025)
- Multi-target problem

---

## 🧠 Strategy

### 1️⃣ Time-aware validation
Train: 2024  
Validation: 2025  

### 2️⃣ Feature Engineering
- Target Encoding
- Topic statistics
- Cyclical month encoding
- County × Registration interaction

### 3️⃣ Modeling
- CatBoost
- LightGBM
- Blending
- Stacking

---

## 📊 Best Public Score

0.91+
