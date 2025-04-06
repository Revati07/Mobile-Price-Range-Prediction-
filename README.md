#  Mobile Price Range Prediction

A machine learning system that predicts the price category (low, medium, high, very high) of mobile phones based on their specifications. This project includes model comparison, hyperparameter tuning, and performance visualization.

---

#  Project Overview
Given a dataset of mobile phone features, the goal is to classify them into one of four price categories:
- 0: Low
- 1: Medium
- 2: High
- 3: Very High

---

#  Dataset
The dataset contains various mobile specifications such as:
- Battery Power
- RAM
- Internal Memory
- Number of Cores
- Front/Rear Camera
- Screen Dimensions
- 4G/3G/WiFi Support
- Touch Screen

# Target Variable
- `price_range` (0–3)

---

# Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

# Model Workflow
1. **Data Loading & Preprocessing**
2. **Model Training** with:
    - Random Forest
    - K-Nearest Neighbors
    - Support Vector Machine
    - Decision Tree
    - Gradient Boosting
3. **Hyperparameter Tuning** with GridSearchCV for top 3 models
4. **Evaluation & Accuracy Comparison**
5. **Visualization of Results**

---

# Results
- **Best Model**: Gradient Boosting Classifier
- **Top Accuracy**: ~90.5% after tuning
- **Other Strong Models**: Random Forest, SVM (~89%)

---

# Visuals
Bar chart comparing the performance of top 3 models after hyperparameter tuning.

---

# How to Run
1. Clone this repo
```bash
git clone https://github.com/yourusername/mobile-price-prediction.git
cd mobile-price-prediction
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Run the script
```bash
python mobile_price_prediction.py
```

---

# Future Improvements
- Deploy as a web app using Streamlit or Flask
- Use deep learning for better accuracy
- Add more advanced feature engineering

---

# Contributors
- Revati Mahajan

---

# Contact
📧 revatimahajan6055@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/revatimahajan)  
💻 [GitHub](https://github.com/Revati07)

---

# License
This project is open-source and available under the MIT License.
