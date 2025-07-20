
---

# 🏦 Bankruptcy Prediction in Poland

This project is part of the **Applied Data Science Lab** by WorldQuant University and demonstrates an **end-to-end machine learning pipeline** for predicting company bankruptcy using real financial data collected by Polish economists. The focus is on building accurate models while handling **imbalanced classification problems**—a common challenge in real-world financial datasets.

🔗 **Live Repository:** [https://github.com/Houssam-123-ship-it/Predicting-Bankruptcy-In-Poland-End-to-End-Machine-Learning-Project-]
---

## 📌 Project Workflow

### 1. **Prepare Data**

* Navigated the file system via Linux terminal
* Loaded and cleaned the dataset using `pandas`
* Conducted EDA and explored class imbalance
* Applied **resampling techniques** (e.g. Over sampling ) to balance classes 

### 2. **Build Model**

* Trained two ensemble models:
✅ **Random Forest Classifier**
An ensemble of decision parallel trees that votes on the final prediction to improve accuracy and reduce overfitting.

✅ **Gradient Boosting Classifier**
A sequential model that builds trees to correct previous errors, optimizing performance through gradient descent.
* Tuned hyperparameters using `GridSearchCV` (14-minute grid search)
* Saved the best-performing model using best

### 3. **Communicate Results**

* Evaluated model using **precision, recall**, and **confusion matrix**
* Visualized **feature importance** and **confusion matrice**
* Created a custom Python module for real-world bankruptcy predictions

---

## 📘 Included Notebooks

| Notebook                             | Description                                                                                                             |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------          |
| `1- working_with_JSON.ipynb`         | Load, explore, clean, and balance the dataset                                                                           |
| `2- imbalanced_data.ipynb`           |  Load, explore, clean, and balance the dataset                                                                          |
| `3- random-forest.ipynb`             | Train ensemble models and perform hyperparameter tuning Evaluate model, visualize metrics, and predict new data         |
| `4- gradient-boosting.ipynb`         | Train ensemble models and perform hyperparameter tuning Evaluate model, visualize metrics, and predict new data         |
| `5- assignment.ipynb`                | Revise all the work with taiwan-bankruptcy-data.json.gz dataset , differ a little bit from the poland companies dataset  |
---

## 🧠 Skills Gained

* Linux terminal navigation and file operations
* Data loading and cleaning with `pandas`
* Dealing with **imbalanced datasets** using `imbalanced-learn`
* Training **ensemble classifiers** for binary prediction tasks
* Model tuning with `GridSearchCV`
* Performance evaluation with precision, recall, F1-score
* Model serialization and loading for reuse
* Building reusable Python modules

---

## 🛠️ Dependencies

Install the Python libraries , see all of them on notebooks

---

## 📊 Data Source

The dataset contains financial ratios and metrics for Polish companies, labeled with whether they went bankrupt. The data was curated by a team of economists to support bankruptcy risk research. See the Metadata inside the dataset for more informations, data/Data Dictionary.ipynb for feature infos 

---

## ✅ How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/Houssam-123-ship-it/Predicting-Bankruptcy-In-Poland-End-to-End-Machine-Learning-Project-
   cd Predicting-Bankruptcy-In-Poland-End-to-End-Machine-Learning-Project-
   ```

2. Install dependencies (see above)


3. Use `my_predictor_lesson.py` or `my_predictor_assignment.py` to test your own data or integrate into a larger project.

---

## 🏁 Final Thoughts

This project was an invaluable opportunity to apply advanced machine learning to a **high-impact financial domain**. It strengthened my understanding of **imbalanced data challenges**, **ensemble learning**, and how to **build and deploy models** that can be reused and shared across projects.

It’s more than just a predictive model—it's a hands-on tool you can extend to evaluate real-world bankruptcy risk scenarios.


