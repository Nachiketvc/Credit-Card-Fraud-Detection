## Credit Card Fraud Detection using Machine Learning

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Technologies Packages & Libraries Used](#technologies-packages--libraries-used)
3. [Approach](#approach)
4. [Comparison of Algorithms](#Comparison-of-Algorithms)
5. [Results and Conclusion](#results-and-conclusion)


---

## Problem Statement and Dataset 

- The dataset consists of two days of credit card transactions, totaling 284,807 records. Among these, only 492 transactions are fraudulent, making the dataset highly imbalanced. The challenge is to develop a model that can effectively identify fraudulent transactions despite the imbalance. The features of the dataset include 28 anonymized variables derived using Principal Component Analysis (V1–V28), along with 'Time' and 'Amount', which were not transformed.

**What is Fraud Detection?**
- Fraud detection involves identifying unusual or suspicious activities that deviate from normal transaction patterns. In the context of credit card transactions, fraud detection aims to flag unauthorized or deceptive activities, helping to protect users and financial institutions from financial loss.

---

## Technologies Packages & Libraries Used
Below is a breakdown of the core technologies used in this project:



| Category     | Technology     |
|--------------|----------------|
| Programming Language       | Python |
| Libraries     | Scikit-learn, Pandas, Matplotlib, Seaborn |




---


## Approach

- Preprocessed data by handling missing values and normalizing features.

- Addressed class imbalance using SMOTE.

- Evaluated multiple algorithms: Logistic Regression, SVM, Random Forest, Isolation Forest, Local Outlier Factor, and K-means.

- Assessed performance using metrics like Accuracy, Precision, Recall, and F! Score.

---

## Comparison of Algorithms

| Model                 | F1 Score | Accuracy | Recall | Precision |
|-----------------------|----------|----------|--------|-----------|
| Logistic Regression    | 0.9326   | 0.9703   | 0.909  | 0.9574    |
| SVM                   | 0.9479   | 0.9849   | 0.9191 | 0.9785    |
| Random Forest         | 0.9435   | 0.9715   | 0.9293 | 0.9583    |
| Isolation Forest      | 0.67     | 0.9977   | 0.67   | 0.67      |
| Local Outlier Factor  | 0.25     | 0.9967   | 0.25   | 0.25      |
| K-means               | 0.926    | 0.9982   | 0.879  | 0.9798    |

---

## Results and Conclusion

Random Forest emerged as the best model, achieving:

- F1 Score: 0.9435

- Accuracy: 97.15%

- Recall: 92.93%

- Precision: 95.83%

**Conclusion**

- The Random Forest model performed well, but maintaining its effectiveness requires continuous evaluation, regular updates, and collaboration with domain experts to adapt to evolving fraud tactics. A multi-metric evaluation strategy is critical to ensure sustained reliability.
 
---
