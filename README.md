# Fake News Detection

## Overview  
This project builds a machine learning model to classify news articles as **real** or **fake** based on their textual content.  
A robust fake news detector could be integrated into:  
- Browser extensions to warn readers of potentially unreliable content  
- Social media platforms to flag questionable posts  
- Standalone services where users can paste a link or article text to check credibility  

Such tools can help slow the spread of misinformation.

---

## Dataset  
The dataset comes from [Kaggle – Fake News Detection Dataset](https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets) and contains:  
- **21,417** real news articles (from Reuters)  
- **23,481** fake news articles (flagged by Politifact)  
- Content focuses mainly on **politics** and **world news** from **2016–2017**  

---

## Project Structure  
The project is divided into 7 parts:  
1. **Introduction** – Problem definition and dataset description  
2. **Data Preprocessing** – Cleaning and preparing text data  
3. **Exploratory Data Analysis (EDA)** – Understanding the dataset through statistics and visualizations  
4. **Feature Engineering** – Converting text into numerical features using TF-IDF and other techniques  
5. **Model Building** – Training multiple machine learning models  
6. **Model Evaluation** – Assessing model performance using metrics like accuracy, precision, recall, and F1-score  
7. **Model Interpretation** – Understanding which words and patterns contribute to predictions  

---

## Tools & Libraries  
- **Python** (Pandas, NumPy, re) – Data handling and preprocessing  
- **Matplotlib, Seaborn, WordCloud** – Data visualization  
- **Scikit-learn** – Feature extraction, model training, and evaluation  
- **NLTK** – Text processing and tokenization  
- **SHAP** – Model interpretation and explainability  

---

## Models Used  
- Logistic Regression  
- Passive Aggressive Classifier  
- Random Forest Classifier  
- Multinomial Naive Bayes  

---

## Key Results  
- Logistic Regression and Passive Aggressive Classifier performed best with high accuracy and balanced precision/recall.  
- SHAP values provided insights into feature importance and model decision-making.  

---

### Steps to Run Locally
1. Clone this repository.
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook fake_news_detection.ipynb
   ```

## Future Improvements
- Deploy the model as a web application or browser extension.
- Incorporate more recent datasets for improved relevance.

## Author
Anni Aalto 
GitHub: [mqanaa](https://github.com/mqanaa)