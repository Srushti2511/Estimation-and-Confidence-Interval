# Estimation-and-Confidence-Interval
# 📈 Confidence Interval Estimation

This project demonstrates how to compute **99% confidence intervals** for the durability of print-heads using Python.

---

## 📊 Dataset

Durability values (in millions of characters) for 15 randomly selected print-heads.

---

## 🧪 Methods Used

### 1️⃣ Using Sample Standard Deviation (t-distribution)
- Population standard deviation unknown
- Small sample size (n = 15)
- Used `scipy.stats.t.interval`

### 2️⃣ Using Known Population Standard Deviation (z-distribution)
- Population σ = 0.2 given
- Used `scipy.stats.norm.ppf` for z-critical value

---

## 🐍 Python Libraries

- `numpy`  
- `scipy.stats`

---

## 👩‍💻 Author

**Srushti Yadav**  
