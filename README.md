# sms_spam_classification

---

## 🛠️ Steps in the Project

1. **Data Loading & Cleaning**
   - Load dataset (`spam.csv`)
   - Remove duplicates & handle missing values
   - Encode target labels (ham=0, spam=1)

2. **Exploratory Data Analysis (EDA)**
   - Class balance visualization
   - Message length statistics (characters, words, sentences)
   - Word clouds for spam vs ham messages

3. **Text Preprocessing**
   - Lowercasing
   - Tokenization
   - Removing stopwords & punctuation
   - Stemming (Porter Stemmer)

4. **Feature Engineering**
   - TF-IDF vectorization (max_features=3000)
   - Meta features: message length, word count, etc.

5. **Model Training**
   - Logistic Regression
   - Naive Bayes
   - Support Vector Machine (SVC)
   - Random Forest

6. **Evaluation**
   - Metrics: Accuracy & Precision
   - Best performing models:  
     - **SVC**: Accuracy ≈ 98.7%, Precision ≈ 97.6%  
     - **Naive Bayes**: Accuracy ≈ 98.3%, Precision = 100%  

---

## 📊 Results
- **Naive Bayes** and **SVC** gave the best performance.  
- The model is highly precise in detecting spam while minimizing false positives.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Bilel-Amri/sms_spam_classification.git
   cd sms_spam_classification

