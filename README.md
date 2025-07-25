# sentiment-analysis
my training cum intern task or minor project-3

<h3> #
- ✅ This project was developed and executed using **Google Colab**, providing an easy-to-use cloud-based Python environment with built-in support for libraries like scikit-learn, NLTK, and matplotlib.
 </h3>
# 🎬 IMDb Sentiment Analysis using Machine Learning

This project performs sentiment analysis on IMDb movie reviews using traditional machine learning techniques. It includes detailed text preprocessing, model training, evaluation, visualization, and custom review prediction, all done in a clean Jupyter Notebook format.

---
<h2>
## 📌 Key Features
</h2>
- 📥 **Dataset**: IMDb 50,000 labeled reviews (balanced positive and negative).
- 🧹 **Text Preprocessing**:
  - Lowercasing
  - HTML tag removal
  - Removal of special characters and stopwords
  - Tokenization and lemmatization using NLTK
- 📊 **Exploratory Data Analysis**:
  - Class distribution visualization
  - Word clouds and frequency plots
- 🔢 **Feature Engineering**:
  - TF-IDF Vectorization (unigrams and bigrams)
- 🔁 **Model Training & Evaluation**:
  - Trained Logistic Regression, Naive Bayes, SVM, and Random Forest
  - Evaluated using Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix and ROC-AUC Curve visualization
- 🧠 **Best Model Selection**:
  - Compared models to select the best-performing classifier
- 💬 **Custom Review Prediction**:
  - Accepts manual input and returns predicted sentiment
- 📈 **Feature Importance Visualization**:
  - Top weighted words from TF-IDF for each sentiment

---

## 📂 Dataset

- **Source**: [IMDb Movie Review Dataset](https://raw.githubusercontent.com/datasets/sentiment-analysis-imdb/master/data/imdb-dataset.csv)
- **Size**: 50,000 movie reviews (25k positive, 25k negative)

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/DND1064/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
