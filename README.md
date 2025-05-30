# 🧠 An Interpretable Machine Learning Approach for Bengali Toxic Comments Detection

[![DOI](https://img.shields.io/badge/DOI-10.1109%2FECCE64574.2025.11014029-blue)](https://doi.org/10.1109/ECCE64574.2025.11014029)
[![Conference and Paper Link](https://img.shields.io/badge/Presented%20At-ECCE%202025-orange)](https://www.researchgate.net/publication/392212652_An_Interpretable_Machine_Learning_Approach_for_Bengali_Toxic_Comments_Detection)
[![License](https://img.shields.io/github/license/ZobayerAkib/An-Interpretable-Machine-Learning-Approach-for-Bengali-Toxic-Comments-Detection-IEEE2025)](./LICENSE)
[![Code Status](https://img.shields.io/badge/Code-Available-green)](https://github.com/ZobayerAkib/An-Interpretable-Machine-Learning-Approach-for-Bengali-Toxic-Comments-Detection-IEEE2025)

> 🔍 A Machine Learning pipeline for detecting Bengali toxic and bullying comments, enriched with **Explainable AI (XAI)** using **LIME** for model transparency and interpretability.

---

## 📘 Abstract

Toxic comment detection is vital to ensure a safe and healthy online environment, especially in underrepresented languages like Bengali. This research proposes a robust and interpretable machine learning pipeline to classify Bengali comments as **toxic** or **non-toxic**. Two public datasets were used, containing **16,073** and **44,001** comments respectively. After preprocessing and **TF-IDF feature extraction**, various machine learning models were trained and evaluated.

- ✅ **Best Model (Dataset-1)**: SGD Classifier — F1 Score: 0.91 | Accuracy: 91.44%
- ✅ **Best Model (Dataset-2)**: SGD Classifier — F1 Score: 0.88 | Accuracy: 88.42%

To enhance transparency, **LIME (Local Interpretable Model-agnostic Explanations)** was used to explain predictions, making the system more interpretable and trustworthy.

---

## 🏛️ Presented At

**2025 International Conference on Electrical, Computer and Communication Engineering (ECCE)**  
🔗 [IEEE ECCE 2025](https://doi.org/10.1109/ECCE64574.2025.11014029)

---

## 🧪 Datasets Used

1. **Dataset-1**: 16,073 Bengali comments  
   - Toxic: 8,488  
   - Not Toxic: 7,585  
2. **Dataset-2 (Mendeley Data)**: 44,001 Bengali comments  
   - Toxic/Bully: 28,661  
   - Not Toxic: 15,340

---

## 🛠️ Techniques Used

- ✅ Text Preprocessing (Cleaning, Tokenization)
- ✅ Feature Extraction using **TF-IDF**
- ✅ Classifiers: SGD, SVM, Logistic Regression, Random Forest, etc.
- ✅ Model Evaluation: Confusion Matrix, Accuracy, Precision, Recall, F1 Score
- ✅ Explainable AI using **LIME**

---

## 🔍 Explainable AI (XAI) with LIME

We integrated **LIME** to explain how our classifier made specific predictions — enabling deeper insights into which words or phrases contributed most to a toxic classification.

> 🌐 Transparency = Trust.

![lime-example](https://raw.githubusercontent.com/ZobayerAkib/An-Interpretable-Machine-Learning-Approach-for-Bengali-Toxic-Comments-Detection-IEEE2025/main/images/lime_example.png)

---

## 📊 Results Summary

| Dataset | Best Model       | Accuracy | F1 Score |
|---------|------------------|----------|----------|
| Dataset-1 | SGD Classifier  | 91.44%   | 0.91     |
| Dataset-2 | SGD Classifier  | 88.42%   | 0.88     |

---

## 📚 Citation

If you find this work useful, please consider citing us:

```bibtex
@INPROCEEDINGS{11014029,
  author={Kabir, Md. Zobayer Ibna},
  booktitle={2025 International Conference on Electrical, Computer and Communication Engineering (ECCE)}, 
  title={An Interpretable Machine Learning Approach for Bengali Toxic Comments Detection}, 
  year={2025},
  pages={1-6},
  keywords={Bengali Toxic Comment; Bangla Cyberbullying; Bangla Hate Speech; TF-IDF; Machine Learning; SVM; Explainable AI (XAI); LIME},
  doi={10.1109/ECCE64574.2025.11014029}
}


