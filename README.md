# MNIST PCA Visualization

This project demonstrates how to load, visualize, and perform dimensionality reduction using PCA on the MNIST handwritten digit dataset.

## 📂 Dataset

- **Source:** [Kaggle MNIST Dataset](https://www.kaggle.com/c/digit-recognizer/data)
- **Format:** CSV file (`train.csv`) where:
  - The first column is the label (digit 0–9)
  - The rest are 784 pixel values (28x28 images)

## 📌 Objectives

- Visualize sample handwritten digits
- Apply Principal Component Analysis (PCA)
- Compare model accuracy before and after PCA
- Visualize PCA components and explained variance

## 🧪 Technologies Used

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib

## 📊 Visualizations

- **Digit samples:** Displayed using `matplotlib.pyplot.imshow()`
- **Label distribution:** Bar plot showing frequency of each digit
- **PCA Visualization:**
  - Scatter plot of first 2 principal components
  - Explained variance ratio curve
- **Model Accuracy:**
  - Accuracy score before and after PCA

## 📈 Results

- PCA significantly reduced dimensionality (784 → ~50 dimensions) while retaining most of the variance.
- Classifier performance might slightly drop but inference becomes faster.
- Great for visualizing data clusters in 2D.

## 💡 Learnings

- PCA helps in visualizing high-dimensional image data.
- There is a trade-off between dimensionality reduction and model performance.
- Even 2D PCA projections can reveal clear clusters for different digits.

---

**Note:** PCA should be used after standardization for meaningful results.

-


