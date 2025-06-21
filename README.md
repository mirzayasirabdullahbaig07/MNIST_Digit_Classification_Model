# 🧠 MNIST Handwritten Digit Recognition with Error Analysis & Gradio Deployment

This project presents a complete machine learning pipeline for recognizing handwritten digits from the **MNIST dataset** using **Scikit-learn**. It integrates both theoretical and practical components of classification — including model comparison, performance evaluation, error analysis, and deployment via Gradio.

---

## 📌 Key Objectives

- Understand binary vs multiclass classification
- Compare classifiers (SGD vs Random Forest)
- Evaluate model performance using:
  - Confusion Matrix
  - Precision, Recall, F1 Score, ROC Curve
- Conduct error analysis and identify patterns
- Improve model using preprocessing techniques
- Deploy final model using **Gradio web interface**
- Achieve **95%+ test accuracy**

---

## 🧠 Classification Concepts (From Chapter 3)

- **MNIST Data:** 28x28 grayscale pixel images
- **Binary vs Multiclass:** Using OvR and OvO strategies
- **Metrics Covered:**
  - Confusion Matrix
  - Precision, Recall, F1 Score
  - ROC Curve, PR Curve
- **Error Analysis:** Investigate frequent misclassifications
- **Advanced Concepts:**
  - Multilabel & Multioutput classification (explored theoretically)

---

## 🔧 Project Implementation Steps

1. Load MNIST dataset using `fetch_openml('mnist_784')`
2. Preprocess data and split into train/test (60K/10K)
3. Train and compare:
   - `SGDClassifier` (with hinge loss)
   - `RandomForestClassifier`
4. Evaluate using:
   - `classification_report`
   - `confusion_matrix`
5. Visualize misclassifications (e.g., top 10 errors)
6. Conduct error analysis and suggest improvements
7. Deploy final model using **Gradio**

---

## 📁 Folder Structure


---

## 📊 Results & Accuracy

- ✅ **Test Accuracy Achieved:** 95%+
- 🧩 Common Errors:
  - `9 → 4`
  - `5 → 3`
  - `7 → 1`
- 🔁 Proposed Fixes:
  - Preprocessing (e.g., image smoothing, contrast normalization)
  - Data augmentation (e.g., rotation, shift)

---

## 🌐 App Deployment (Gradio)

You can launch the digit recognition app locally using:

```bash
cd app
pip install -r requirements.txt
python app.py

---

## 👤 Author
📧 Email: yasirabdullah4549@gmail.com

💻 GitHub: mirzayasirabdullahbaig07

🔗 LinkedIn: mirza-yasir-abdullah-baig

---
