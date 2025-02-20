# 🚀 Transaction Fraud Detection Using Machine Learning

## 📌 Overview
Transaction fraud is a significant challenge in financial systems, leading to substantial financial losses and security concerns. This project aims to develop a **fraud detection system** using machine learning techniques to identify and prevent fraudulent transactions effectively.

![Fraud Detection](https://img.shields.io/badge/Fraud%20Detection-Secure%20Transactions-red?style=for-the-badge&logo=databricks&logoColor=white)  
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Model%20Training-blue?style=for-the-badge&logo=scikitlearn&logoColor=white)  
![Random Forest](https://img.shields.io/badge/Random%20Forest-Classification-green?style=for-the-badge&logo=python&logoColor=white)  
![SVM](https://img.shields.io/badge/SVM-Support%20Vector%20Machine-purple?style=for-the-badge&logo=scikitlearn&logoColor=white)  
![KNN](https://img.shields.io/badge/KNN-K--Nearest%20Neighbors-orange?style=for-the-badge&logo=python&logoColor=white)  
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-EDA%20&%20Feature%20Engineering-yellow?style=for-the-badge&logo=pandas&logoColor=white)  

## 🎯 Key Features
- 🔍 **Data Preprocessing**: Handling missing values, outlier detection, and feature engineering.
- 📊 **Exploratory Data Analysis (EDA)**: Visualizing transaction patterns and fraud trends.
- 🏆 **Classification Models**: Implemented five powerful machine learning algorithms:
  - Logistic Regression
  - Gradient Boost
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- ✅ **Model Evaluation**: Using precision, recall, F1-score, and ROC-AUC for performance analysis.
- 🔒 **Fraud Probability Score**: Assigns a probability score to each transaction.
- ⚡ **Real-time Detection**: The model can be deployed for live transaction monitoring.

## 🛠️ Technology Stack
- **Programming Language**: Python 🐍
- **Libraries Used**:
  - Pandas & NumPy (Data Handling)
  - Matplotlib & Seaborn (Visualization)
  - Scikit-learn (Machine Learning Models)
- **Jupyter Notebook / Google Colab** for experimentation

## 📂 Project Structure
```
Transaction-Fraud-detection/
│── dataset/
│   ├── transactions.csv  # Not available in repository due to size(145MB)
│── transaction.py  # Data cleaning and transformation
│── README.md  # Project documentation
```

## 🚀 Installation & Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nithish-m123/Transaction-Fraud-detection.git
   cd Transaction-Fraud-detection
   ```
2. **Create a Virtual Environment** (Optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r dependencies(numpy,pandas,scikit-learn,etc.)
   ```
4. **Run the Model**:
   ```bash
   python transaction.py
   ```

## 📊 Dataset
- The dataset used in this project contains transaction details such as **transactionType	amount	initiator	oldBalInitiator	newBalInitiator	recipient	oldBalRecipient	newBalRecipient	isFraud**.
- It includes both **fraudulent and non-fraudulent transactions** for model training.
- If no dataset is provided, you can use publicly available datasets like **Kaggle’s Credit Card Fraud Detection dataset**.

## 📈 Model Performance
| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| Logistic Regression   | 89.0%    | 88.3%     | 85.7%  | 86.9%    |
| XGBoost              | 90.0%    | 90.0%     | 99.0%  | 95.0%    |
| Random Forest       | 88.44%    | 91.0%     | 96.0%  | 94.0%    |
| SVM                 | 95.6%    | 92.7%     | 91.0%  | 91.8%    |
| KNN                 | 88.21%    | 92.0%     | 96.0%  | 94.0%    |

## 📌 Future Enhancements
🔹 Implement **Deep Learning** techniques for better accuracy.  
🔹 Use **Anomaly Detection** methods like Isolation Forest.  
🔹 Deploy the model as a real-time fraud detection API.  

## 🤝 Contribution
Contributions are welcome! If you’d like to improve the project, feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

## 📧 Contact
For any queries or collaboration, feel free to reach out:
- **GitHub**: [nithish-m123](https://github.com/nithish-m123)
- **Email**: mekalcheruvunithish2580@gmail.com

---
🚀 **Transaction Fraud Detection** – Secure Transactions, Smarter Banking 💰💡

