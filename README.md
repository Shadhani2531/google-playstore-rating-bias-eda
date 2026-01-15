# Do App Ratings Lie?

## About this project
When we choose apps from the Play Store, we often trust the star rating without thinking twice.
This project looks a little deeper.

The goal of this analysis is to understand whether app ratings actually represent user satisfaction,
or whether they are influenced by factors like the number of reviews, whether an app is free or paid,
and the category it belongs to.

This is an exploratory data analysis (EDA) project focused on understanding patterns and limitations
in app ratings, not on building prediction models.

---

## Dataset
The dataset used in this project is the Google Play Store Apps dataset from Kaggle.

Link to dataset:  
https://www.kaggle.com/datasets/lava18/google-play-store-apps

The raw data file is not included in this repository.  
Please download `googleplaystore.csv` from the link above to run the notebook.

---

## What I explored
- How app ratings are distributed across the Play Store
- Whether apps with more reviews have more reliable ratings
- Differences in ratings between free and paid apps
- Rating behavior across different app categories
- The relationship between installs, reviews, and ratings

---

## Key observations
- Most app ratings are clustered at the higher end, suggesting rating inflation
- Apps with very few reviews often show extreme ratings
- Paid apps tend to have more consistent ratings than free apps
- Category-wise average ratings can be misleading without considering sample size

---

## Tools used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Final note
This project helped me practice asking the right questions before jumping to conclusions.
It shows that ratings alone are not always enough to judge app quality, and context matters.
