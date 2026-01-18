#  Influencers Data Analysis Project

##  Project Overview

This project analyzes social media influencers data to understand how different factors such as followers, posts, and average likes contribute to an influencer’s overall **influence score**.

The project follows a complete **Data Analyst + Machine Learning workflow** including data understanding, feature selection, model building, and evaluation, strictly based on the provided dataset structure.

---

##  Project Objective

* Analyze influencer popularity and engagement metrics
* Study the relationship between followers, posts, and likes
* Build a machine learning model to predict **influence score**
* Derive meaningful insights from influencer data

---

##  Dataset Information

* **File name:** `Influencers Data.csv`
* **Total records:** 200
* **Columns in dataset:**

  * `rank`
  * `channel_info`
  * `influence_score` (Target variable)
  * `posts`
  * `followers`
  * `avg_likes`
  * `60_day_eng_rate`
  * `new_post_avg_like`
  * `total_likes`
  * `country`

---

##  Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* VS Code / Jupyter Notebook

---

##  Project Workflow

1. Data Loading and Understanding
2. Feature Selection based on dataset columns
3. Exploratory Data Analysis (EDA)
4. Machine Learning Model Building
5. Model Evaluation using performance metrics
6. Insights and Conclusion

---

##  Machine Learning Model

* **Model Used:** Linear Regression
* **Target Variable:** `influence_score`
* **Features Used:**

  * `followers`
  * `posts`
  * `avg_likes`

---

##  Model Evaluation

* **Evaluation Metrics:**

  * Mean Squared Error (MSE)
  * R² Score
* The model helps understand how influencer metrics contribute to influence score.

---

## ▶️ How to Run the Project

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python main.py
```

---

## Key Insights

* Influencers with higher followers and average likes tend to have higher influence scores
* Posting frequency alone does not guarantee higher influence
* Engagement-related metrics play a crucial role in influencer performance
