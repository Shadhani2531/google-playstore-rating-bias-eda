# Do App Ratings Lie?
### Exploratory Data Analysis of Google Play Store Apps

## 📌 Overview
App ratings are often used as a proxy for quality, but do they actually reflect real user satisfaction?
This project performs an exploratory data analysis (EDA) on Google Play Store apps to investigate
whether app ratings are influenced by factors such as review count, pricing model, app category,
and install volume.

The goal is not to build a predictive model, but to uncover patterns, biases, and limitations
in how ratings should be interpreted.

---

## 📊 Dataset
- **Source:** Google Play Store Apps dataset (Kaggle)
- **Link:** https://www.kaggle.com/datasets/lava18/google-play-store-apps

Due to licensing restrictions, the raw dataset is not included in this repository.
Please download `googleplaystore.csv` from the source link to reproduce the analysis.

- **Key Columns Used:**
  - Category
  - Rating
  - Reviews
  - Installs
  - Type (Free / Paid)
  - Price
  - Size

---

## 🔍 Key Questions Explored
- Do apps with more reviews have more reliable ratings?
- Are free apps rated differently than paid apps?
- Which categories appear overrated or underrated?
- Does app size or install count influence user ratings?

---

## 📈 Major Insights
- App ratings are heavily skewed toward higher values, indicating possible rating inflation.
- Ratings from apps with very few reviews tend to be more extreme and less reliable.
- Paid apps show lower variance in ratings compared to free apps.
- Category-wise average ratings can be misleading without considering sample size.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Conclusion
This analysis highlights that app ratings alone are not a sufficient measure of quality.
Review volume and contextual factors play a critical role in interpreting user feedback.
Such insights are valuable for users, developers, and product analysts when making decisions
based on app ratings.

---


