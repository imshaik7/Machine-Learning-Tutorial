# 🎓 Mastering Support Vector Machines (SVM) - A Machine Learning Tutorial

Welcome to an in-depth tutorial on **Support Vector Machines (SVM)**—one of the most powerful and widely used supervised machine learning algorithms. This repository includes theoretical insights, practical code implementations, visualizations, and performance analysis using real-world datasets.

---

## 📌 Project Overview

This project was developed as part of the coursework for the module **Machine Learning and Neural Networks**. It aims to:

- Introduce the theoretical foundation behind SVMs.
- Demonstrate practical implementations using Scikit-Learn.
- Explore the impact of different kernel functions.
- Apply SVM on both synthetic and real-world datasets.
- Perform hyperparameter tuning and compare SVM with other models.

---

## 📚 Table of Contents

- [Project Overview](#-project-overview)
- [Technologies Used](#-technologies-used)
- [Dataset Details](#-dataset-details)
- [Getting Started](#-getting-started)
- [Results and Visualizations](#-results-and-visualizations)
- [Key Learnings](#-key-learnings)
- [References](#-references)
- [Author](#-author)
- [License](#-license)

---

## 🛠 Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Scikit-Learn**
- **Matplotlib**
- **NumPy / Pandas**

---

## 📊 Dataset Details

### 1. **Synthetic Dataset**
- Created using `make_moons()` from Scikit-Learn.
- Ideal for visualizing decision boundaries.

### 2. **Breast Cancer Wisconsin Dataset**
- Real-world dataset used to classify malignant vs benign tumors.
- Features include mean radius, texture, area, etc.

---

## 🚀 Getting Started

### 🔧 Prerequisites
Ensure you have the following installed:
```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### 🏃‍♂️ To Run the Notebooks:
```bash
git clone https://github.com/imshaik7/Machine-Learning-Tutorial.git
cd Machine-Learning-Tutorial
jupyter notebook breast_cancer_svm_analysis.ipynb
```

### 🎨 To Visualize Kernels:
```bash
python svm_visualizations.py
```

---

## 📈 Results and Visualizations

- **Kernel Comparison**: RBF kernel performed best on non-linear datasets.
- **Metrics Used**: Accuracy, Precision, Recall, and F1-score.
- **Visual Insights**: Decision boundaries plotted for each kernel.

---

## 💡 Key Learnings

1. **Kernel Flexibility**: RBF and Polynomial kernels handle non-linearity better than linear.
2. **Hyperparameter Tuning**: Parameters like `C` and `gamma` are crucial for optimal results.
3. **Model Comparison**: SVM outperformed Logistic Regression and Decision Trees on the given dataset.
4. **Visualization**: Helps in better understanding of how SVM distinguishes between classes.
5. **Real-World Relevance**: SVMs are widely used in fields like medical diagnostics, text classification, and fraud detection.

---

## 📚 References

- Bishop, C. M. (2006). *Pattern Recognition and Machine Learning*. Springer.
- Cortes, C., & Vapnik, V. (1995). *Support-vector networks*. Machine Learning, 20(3), 273–297.
- Scikit-learn Documentation: https://scikit-learn.org
- Analytics Steps. (2020). *How does Support Vector Machine algorithm work in Machine Learning?* https://www.analyticssteps.com/blogs/how-does-support-vector-machine-algorithm-works-machine-learning
- GeeksforGeeks – SVM: https://www.geeksforgeeks.org/support-vector-machine-algorithm/

---

## 👤 Author

**Imthiyaz Shaik**  
📘 *MSc Data Science (2024–2026)*  
👨‍🏫 Tutor: Peter Scicluna  
📅 Submitted: 27 March 2025  
🌐 [GitHub Profile](https://github.com/imshaik7)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
