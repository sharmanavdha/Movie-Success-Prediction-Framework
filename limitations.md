# Project Limitations & Future Improvements

## Current Limitations

### 1. Limited Dataset Size
The dataset used for training is relatively small, which may reduce the model's ability to generalize to unseen movies.

### 2. Imbalanced Classes
The dataset contains significantly more unsuccessful movies than successful ones. Although SMOTE was applied, synthetic balancing may still introduce bias.

### 3. Limited Features
The model currently focuses on structured features such as:
- genres
- release timing
- language

However, important real-world factors are missing:
- cast popularity
- director reputation
- social media buzz
- marketing budget
- critic reviews
- audience sentiment

### 4. Static Data
The model does not use real-time information such as:
- trending topics
- streaming popularity
- online engagement

### 5. Overfitting Risk
Complex models like Random Forest and XGBoost may overfit the training data if hyperparameters are not optimized carefully.

### 6. Interpretability
Some ensemble models are difficult to interpret compared to simpler machine learning algorithms.

---

# Suggested Improvements

## 1. Increase Dataset Size
Collect larger and more diverse movie datasets from:
- IMDb
- TMDb
- Kaggle
- Rotten Tomatoes

## 2. Add More Features
Future versions can include:
- actor popularity
- director success rate
- production budget
- trailer views
- social media trends
- review sentiment analysis

## 3. Use Deep Learning
Experiment with:
- Neural Networks
- Transformers
- Hybrid ML models

## 4. Real-Time Prediction System
Build an API-based pipeline that updates predictions using live movie trends.

## 5. Better Evaluation Metrics
Use:
- ROC-AUC
- Precision-Recall curves
- Cross-validation
- F1 optimization

## 6. Deploy as Web Application
Convert the notebook into:
- Flask app
- Streamlit dashboard
- interactive prediction website

---

# Conclusion

While the current predictive model performs reasonably well, there are several opportunities to improve accuracy, scalability, and real-world usability. Future enhancements involving richer datasets and advanced machine learning techniques could significantly improve prediction performance.