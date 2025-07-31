## 📊 Hotel Review Sentiment Analysis

This project performs *text preprocessing* and *sentiment analysis* on hotel reviews using Python. It focuses on cleaning and analyzing textual data to extract insights from customer feedback such as common keywords, word frequency, and sentiment-related patterns.

---

### 📝 Project Description

The goal of this project is to preprocess a dataset of hotel reviews and prepare it for sentiment analysis using natural language processing (NLP) techniques. This includes steps like tokenization, removing stop words, stemming, lemmatization, and visualizing insights from the reviews.

---

### 📁 Dataset

* The dataset is loaded from a CSV file: hotel_reviews.csv
* Key column: Rating_attribute — contains review text from hotel guests

---

### 🔧 Features & Functionality

* Data loading and initial exploration
* Null and duplicate value checking
* Word cloud visualization of review content
* Target word frequency visualization (good, great, amazing, bad)
* Text preprocessing:

  * Lowercasing
  * Tokenization
  * Stop word removal
  * Stemming (using PorterStemmer)
  * Lemmatization (using WordNetLemmatizer)
  * Number removal
  * Contraction expansion
  * Emoji handling
  * HTML tag removal

---

### 📦 Installation

Before running the notebook or script, install the required libraries:

bash
pip install pandas matplotlib seaborn nltk wordcloud contractions pycontractions emoji beautifulsoup4


Also, download necessary NLTK resources (within your script or manually):

python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')


---

### 🖼 Visualizations

* *Word Cloud*: Visual representation of frequently occurring words.
* *Bar Chart*: Frequency of specific sentiment-related words like "good", "bad", etc.

---

### 🧹 Preprocessing Pipeline

1. Lowercasing the text
2. Tokenization using NLTK
3. Removing stop words
4. Stemming & Lemmatization
5. Expanding contractions (e.g., "don't" → "do not")
6. Emoji normalization (e.g., 😊 → :smiling_face_with_smiling_eyes:)
7. Removing HTML tags using BeautifulSoup
8. Number removal (if included later)

---

### 📂 Output Columns

* Tokens – Tokenized words after stopword removal
* stemmer – Stemmed version of the reviews
* Lemmatized – Lemmatized version
* Expanded – Reviews with contractions expanded
* Emoji – Reviews with emojis converted to text
* cleaned – Final cleaned version after HTML removal

---

### 🚀 Future Work

* Sentiment classification using ML models
* Integration with deep learning models (LSTM, BERT)
* Topic modeling (LDA)
* Review polarity scoring

---

### 📃 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 🙋‍♂ Author

M G N Satish Kumar
\[https://github.com/Satish0Kumar]


---

