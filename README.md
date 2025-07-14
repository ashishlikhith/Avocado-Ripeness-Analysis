# 🥑 Avocado Ripeness Analysis using Data Science & Machine Learning

This project showcases how **data science** and **machine learning** can be leveraged to predict the **ripeness stage of avocados** based on physical and sensory parameters such as **firmness, hue, brightness, sound levels, and size**.


## 📌 Objective

To **analyze** avocado ripeness stages and develop a **predictive model** that accurately classifies the ripeness based on measurable features.


## 📂 Dataset Overview

* **Source:** `avocado_ripeness_dataset.csv`
* **Features:**

  * `firmness`
  * `hue`
  * `saturation`
  * `brightness`
  * `color_category`
  * `sound_db`
  * `weight_g`
  * `size_cm3`
  * `ripeness` *(Target variable)*


## 🔎 Exploratory Data Analysis (EDA)

* Checked for **missing values** and verified **data types**
* Key Visualizations:

  * Ripeness distribution – **count plot & pie chart**
  * **Firmness vs Sound Level** – scatter plot
  * **Firmness by Ripeness** – box plot
  * Firmness distribution – histogram
  * Feature **correlation matrix** – heatmap


🧠 Machine Learning Model

* **Model Used:** Random Forest Classifier

### 🛠 Preprocessing Steps:

* Applied **one-hot encoding** to categorical features
* Converted **ripeness labels** into numerical classes
* Ensured **train-test alignment** post encoding

### 📈 Model Training & Evaluation:

* Performed **80/20 train-test split**
* Achieved **100% accuracy** on test data *(Note: may require further validation for generalization)*
* Generated a **classification report** including:

  * **Precision**
  * **Recall**
  * **F1-Score**


## ✅ Results

The trained model can effectively classify avocados into multiple ripeness stages:

* **Hard**
* **Pre-conditioned**
* **Breaking**
* **Firm-ripe**
* **Ripe**

This proves that simple, non-invasive physical characteristics can be reliably used to assess ripeness—an impactful solution for **agriculture**, **food retail**, and **supply chain management**.


## 🛠 Tools & Libraries

* **Python**
* **pandas**
* **matplotlib**
* **seaborn**
* **scikit-learn**


## 📌 Conclusion

This project bridges **agri-tech** and **machine learning**, offering a scalable, low-cost solution to monitor and predict fruit ripeness using everyday measurable features. It paves the way for smarter inventory decisions, reduced waste, and better product quality.

