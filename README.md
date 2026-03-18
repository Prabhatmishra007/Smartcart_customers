# 🧠 Customer Data Analysis using PCA

## 📌 About This Project

This project is a simple attempt to understand customer data by applying basic data preprocessing techniques and reducing dimensions using PCA (Principal Component Analysis).

The idea was to take raw data, clean it, transform it, and then visualize it in a way that helps reveal patterns (if any).

---

## 🚀 What I Did

* Cleaned the dataset (handled missing values, formatted columns)
* Created a new feature `Living_with` from `Marital_Status`
* Converted categorical data into numerical using One-Hot Encoding
* Scaled the data using StandardScaler
* Applied PCA to reduce dimensions to 2 components
* Visualized the result using a scatter plot

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 📊 What I Observed

After applying PCA and plotting the data:

* The points form a dense cluster (kind of like a blob)
* There is no clear separation between groups

This suggests:

* The first two principal components don’t capture a lot of useful structure
* The dataset may not have strong patterns (at least not in 2D)

---

## 📂 Project Files

```bash
smartcart.ipynb   # Main notebook with all steps
README.md         # Project description
```

---

## ⚙️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/smartcart-analysis.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

3. Open the notebook

```bash
jupyter notebook smartcart.ipynb
```

---

## 🔮 What Can Be Improved

This is just a starting point. Some things I can explore next:

* Apply clustering (like KMeans) to find customer groups
* Try better visualization techniques like t-SNE or UMAP
* Improve feature selection for better PCA results

---

## 👤 Author

Prabhat Mishra

---

## 📜 Note

This project is part of my learning journey in Data Science and Machine Learning.
