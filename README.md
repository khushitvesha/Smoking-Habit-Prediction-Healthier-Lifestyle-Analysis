# 🚭 Smoking Habit Prediction – Healthier Lifestyle Analysis

This project focuses on building a predictive machine learning model to determine an individual's smoking status using physiological and medical data. With a large dataset and a business-focused perspective, the analysis also quantifies misclassification costs and the potential impact on insurance and public health outcomes.

---

## 📌 Project Objective

To identify smoking habits based on routine health indicators, enabling early intervention, personalized healthcare, and informed decision-making for individuals, providers, and insurers.

---

## 👥 Stakeholders

- Individuals & Healthcare Providers  
- Public Health Organizations  
- Insurance Companies  

---

## 🗂️ Dataset

- Sample size: 100,000 individuals  
- Features: Demographics, vitals, blood test results, and hearing/sight measurements  
- Target: `SMK_stat_type_cd` (smoking status)

---

## 🔍 Key Analyses

- **EDA**: Distribution of age, gender, blood pressure, and cholesterol by smoking status  
- **Feature Engineering**: Identified relevant predictors from 20+ physiological metrics  
- **Modeling**:
  - Decision Tree
  - Random Forest
  - **XGBoost (best performance)**

---

## 📊 Results

| Model         | Accuracy | Misclassification Cost |
|---------------|----------|------------------------|
| Decision Tree | 82.9%    | \$1,272.40             |
| Random Forest | ~83%     | \$1,575.60             |
| **XGBoost**   | **83.2%**| **\$1,680.00**         |

---

## 💡 Business Impact

- **Cost Savings**: Up to **\$11.89 million annually** through improved risk classification  
- **Prescriptive Intervention**: Earlier health alerts can improve outcomes and reduce claims  
- **Fair Premium Adjustments**: Enables accurate premium pricing for smokers vs. non-smokers

---

## ⚠️ Challenges

- Large dataset processing  
- Complex feature engineering  
- Model interpretability concerns  
- Real-world data noise and imbalance  
- Scalability for deployment

---

## 📎 Files Included

- `Smoking_Prediction.ipynb` – Full notebook with code and visuals  
- `Smoking_Prediction.pptx` – Business presentation  
- `Smoking_Prediction_Report.pdf` – Summary report  
- `README.md` – This documentation

---

## 🔗 Colab Notebook

[Open in Google Colab](https://colab.research.google.com/drive/1FyA-S01jiYnfqv0M_TW1iU7t-yWBPfsh?authuser=1#scrollTo=QogeawzOwO1M&uniqifier=9)

---

## 🛠️ Tools & Libraries

`Python`, `Pandas`, `Seaborn`, `Matplotlib`, `Scikit-learn`, `XGBoost`, `NumPy`, `SHAP`


