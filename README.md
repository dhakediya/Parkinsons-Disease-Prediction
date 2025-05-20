
🧠 Parkinson's Disease Prediction Using Machine Learning

This project aims to predict whether a person is affected by Parkinson’s disease using vocal features from a dataset. We use various machine learning algorithms including **Logistic Regression**, **Random Forest**, **Decision Tree**, **Naive Bayes**, and **K-Nearest Neighbors** to compare their performance.

---

 📂 Dataset

The dataset used is `parkinsons.data`, containing 195 voice recordings from individuals with and without Parkinson’s Disease.

Target Column: `status`

  * 1 = Parkinson’s Disease
  * 0 = Healthy

---

🔧 Libraries Used

Install using:

```bash
pip install pandas-profiling
```

Also requires:

```python
pandas, numpy, seaborn, matplotlib, scikit-learn
```

---

 📊 Data Exploration

* Dataset overview and summary statistics
* Null value check and data types
* Data distribution plots for skewness
* Histograms and bar plots for key features like `NHR`, `HNR`, and `RPDE`
* Correlation matrix and heatmap

---

🧪 Machine Learning Models Used

| Model               | Metrics Evaluated                                 |
| ------------------- | ------------------------------------------------- |
| Logistic Regression | Accuracy, Confusion Matrix, Classification Report |
| Random Forest       | Accuracy, Confusion Matrix, Kappa Score           |
| Decision Tree       | Accuracy, Confusion Matrix, Kappa Score           |
| Naive Bayes         | Accuracy, Confusion Matrix, Kappa Score           |
| K-Nearest Neighbors | Accuracy, Confusion Matrix, Kappa Score           |

Each model is trained and evaluated on an 80/20 train-test split. The models are compared using:

* Accuracy on training and test sets
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)
* Cohen’s Kappa Score
* Count of incorrect predictions

---

 📈 Highlights

* Performed **exploratory data analysis** using graphs and statistical summaries.
* Implemented and evaluated **five classification models**.
* Visualized correlations and distributions to understand feature importance.
* Evaluated model performance using **Kappa Score** for better agreement measurement.

---

