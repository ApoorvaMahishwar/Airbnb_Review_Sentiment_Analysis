# AirBnb Reviews Sentiment Analysis

Analyzes AirBnb user reviews to classify sentiment using a multi-stage pipeline: **data preprocessing, classical machine learning, deep learning, and LLM-based approaches**. Includes an **interactive dashboard** for exploring results and visualizations.

---

## Dataset

AirBnb user reviews:  
- Raw dataset: [Kaggle Link](https://www.kaggle.com/datasets/YOUR_DATASET_LINK_HERE)  
- Cleaned dataset stored in: 'Dataset/Cleaned_Data/reviews.csv'

## Tech Stack

- **Data processing:** pandas, numpy  
- **Classical ML:** scikit-learn (Logistic Regression, Random Forest, Decision Tree, KNN, AdaBoost, Gradient Boosting, SVM)  
- **Feature extraction:** TF-IDF vectorization  
- **Deep learning:** see notebook 3  
- **LLM-based classification:** see notebook 4  
- **Dashboard & visualization:** Dash / Plotly  
- **Model persistence:** joblib / pickle  

---

## Results

The project compares multiple ML approaches for sentiment classification on AirBnb reviews:  

- Logistic Regression  
- Random Forest  
- Decision Tree  
- KNN  
- AdaBoost  
- Gradient Boosting  
- SVM (using TF-IDF features)  

It also includes **deep learning** and **LLM-based methods**. See notebooks for detailed results and visualizations.

---

## How to Run

1. Install dependencies: pip install pandas numpy scikit-learn plotly dash

2. Run the notebooks in order:
   - 1_dataPreprocessing.ipynb → Clean and prepare the review data
   - 2_machineLearning.ipynb → Train and evaluate ML models
   - 3_deepLearning.ipynb → Deep Learning experiments
   - 4_LLM.ipynb → LLM-based sentiment analysis

3. Launch the dashboard: python dashboard.py

--


