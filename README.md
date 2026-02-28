📧 Email Spam Detection Model

📖 Project Overview
This project builds a Machine Learning classification model to detect whether an email or SMS message is Spam or Not Spam (Ham). The goal is to automatically filter unwanted messages using Natural Language Processing (NLP) techniques.

🎯 Problem Statement
Spam messages are unwanted and potentially harmful. This project aims to build a classification model that can accurately predict whether a message is spam or legitimate based on its text content.

## 📊 Dataset Information
- Total Rows: 5572
- Total Columns: 5 (cleaned to 2 useful columns)
- Target Variable: Category (Spam or Ham)
- Features Used: Message Text
- Dataset: spam.csv

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Natural Language Processing (NLP)

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Removed unnecessary columns
- Renamed columns properly
- Checked for null values
- Removed duplicate messages

### 2️⃣ Text Preprocessing
- Converted text to lowercase
- Removed special characters and punctuation
- Tokenization
- Removed stopwords
- Applied stemming using Porter Stemmer

### 3️⃣ Feature Extraction
- Used CountVectorizer / TF-IDF Vectorizer
- Converted text data into numerical format

### 4️⃣ Model Building
- Implemented Multinomial Naive Bayes
- Trained model on processed text data

### 5️⃣ Model Evaluation
- Evaluated using Accuracy Score
- Generated Confusion Matrix
- Checked Precision and Recall

## 📈 Model Performance
- Accuracy Score: 0.97+
- High Precision for Spam class
- Low False Positive Rate

## 🏆 Best Model
Multinomial Naive Bayes performed well because it works efficiently for text classification problems and handles word frequency features effectively.

## 🌍 Real-World Application
- Email filtering systems
- SMS spam detection
- Social media message filtering
- Enterprise security systems

## 🚀 How to Run the Project
1. Clone the repository
2. Install dependencies using: pip install -r requirements.txt
3. Run the Jupyter Notebook using: jupyter notebook

## 🔮 Future Improvements
- Hyperparameter tuning
- Try Logistic Regression and SVM
- Deploy using Streamlit
- Use advanced NLP models

## 📚 Key Learnings
- Practical understanding of NLP preprocessing
- Feature extraction using TF-IDF
- Text classification using Naive Bayes
- Model evaluation using confusion matrix and accuracy metrics
