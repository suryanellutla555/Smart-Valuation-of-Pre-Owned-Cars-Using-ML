# Smart-Valuation-of-Pre-Owned-Cars-Using-ML

> A machine learning-based solution to estimate the resale price of used cars using various regression algorithms.

---

### 📌 Overview

This project predicts the resale value of used cars based on multiple vehicle features. Using historical data from [CarDekho.com](https://www.cardekho.com), it compares the performance of different regression models including **Decision Tree**, **Random Forest**, **Extra Trees**, and **Bagging Regressor** to determine the most accurate pricing model. The goal is to aid both **buyers** and **sellers** in making informed decisions.

---

### 💻 Tech Stack

* **Language:** Python
* **Libraries:** pandas, NumPy, scikit-learn, seaborn, matplotlib
* **Algorithms:**

  * Decision Tree Regressor
  * Random Forest Regressor
  * Extra Trees Regressor
  * Bagging Regressor

---

### 🧪 Dataset

* Sourced from **CarDekho.com**
* Contains features like:

  * Year
  * Present Price
  * Kilometers Driven
  * Fuel Type
  * Seller Type
  * Transmission
  * Owner

---

### 📊 Methodology

* Data cleaning and preprocessing
* Feature engineering (e.g., `no_year`, one-hot encoding)
* Correlation analysis to find most impactful features
* Model training and evaluation
* Performance comparison using:

  * **MAE** (Mean Absolute Error)
  * **MSE** (Mean Squared Error)
  * **RMSE** (Root Mean Squared Error)
  * **R² Score**
  * **Accuracy (%)**

---

### 🏁 Results

| Model             | R² Score   | Accuracy (%) | MAE       | RMSE      |
| ----------------- | ---------- | ------------ | --------- | --------- |
| Decision Tree     | 0.9457     | 83.71%       | 0.691     | 1.170     |
| Random Forest     | 0.9573     | 87.92%       | 0.614     | 1.038     |
| **Extra Trees**   | **0.9616** | **89.12%**   | **0.542** | **0.984** |
| Bagging Regressor | 0.9540     | 87.57%       | 0.647     | 1.077     |

✅ **Extra Trees Regressor** achieved the highest accuracy and lowest error, making it the most effective model for this task.

---

### 📌 Key Learnings

* Strong correlation between **present price**, **fuel type**, and **seller type** with resale value.
* Ensemble models like **Extra Trees** and **Random Forest** perform significantly better than a single decision tree.
* Feature engineering plays a vital role in boosting model accuracy.

---

### 📂 Repository Structure

```
├── car_data.csv
├── used_car_price_prediction.ipynb
├── README.md
└── report.pdf  ← [Optional: Upload your project PDF here]
```

---

### 📈 Future Improvements

* Include additional features like brand reputation, number of past owners, service history.
* Implement deep learning models or ANN for non-linear relationships.
* Develop a web app using Flask or Django for end-user predictions.

---

### 👨‍💻 Authors

* **Surya Prakash Nellutla** (19BPS1052)
* M. Anil (19BPS1047)
* M. Hanuman Sai (19BPS1066)
* G. Vijay (19BPS1078)

> Guided by: *Dr. Lakshmi Pathi Jakkamputi – VIT Chennai*




