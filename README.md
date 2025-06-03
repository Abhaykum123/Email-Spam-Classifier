## 🚀 Email/SMS Spam Classifier
A lightweight and efficient machine learning-powered web app built with Streamlit to detect whether a given message is Spam or Not Spam. This project combines natural language processing (NLP) techniques and a trained classification model to provide real-time predictions.

---

### 🌟 Key Features
- 🔍 Real-Time Spam Detection – Enter any text message and instantly find out if it's spam.

- 🧹 Text Preprocessing Pipeline – Includes lowercasing, tokenization, stopword removal, and stemming.

- 📊 TF-IDF Vectorization – Transforms text into numerical features for ML.

- 🤖 Pre-Trained ML Model – Fast and accurate classification.

- 🖥️ Streamlit Interface – Clean, intuitive UI for quick predictions.

---

### 📁 Project Structure
```
📦 Email-SMS-Spam-Classifier
├── app.py                    # Main Streamlit app
├── model.pkl                 # Pre-trained ML classification model
├── vectorizer.pkl            # Trained TF-IDF vectorizer
├── Email_Spam_Classifies.ipynb  # Jupyter notebook with training workflow
└── README.md                 # Project documentation
```

### 🔧 Setup Instructions
1. Clone the Repository
```
git clone https://github.com/yourusername/email-sms-spam-classifier.git
cd email-sms-spam-classifier
```
2. (Optional) Create a Virtual Environment
```
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```
4. Download NLTK Resources (One-time Setup)
```
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

### ▶️ Run the App
Launch the Streamlit app in your browser:
```
streamlit run app.py
```
---
### 📓 Training Workflow
Check out the full model training and preprocessing pipeline in the provided Jupyter notebook:

- Email_Spam_Classifies.ipynb

- This includes:

- Data cleaning and exploration

- Text normalization and transformation

- TF-IDF vectorization

- Model training (likely Naive Bayes or Logistic Regression)

- Model saving (model.pkl, vectorizer.pkl)

---

### 🛠️ Tech Stack
- Python 3

- Streamlit

- NLTK – Natural language preprocessing

- Scikit-learn – Model training and TF-IDF vectorization

- Pickle – Model serialization

---

### 💡Author
#### Abhay Kumar

 Let's connect on [LinkedIn](https://www.linkedin.com/in/abhay-kumar-aa1a9129a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BiN9yMzITTT%2Bw7fOOwaUDpQ%3D%3D)<br>
Check out more of my work on [GitHub](https://github.com/Abhaykum123)
