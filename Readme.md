# 📘 NLP Toolkit

A comprehensive and interactive Natural Language Processing (NLP) toolkit built in Python using NLTK, scikit-learn, TextBlob, Gensim, Textstat, WordCloud, and Matplotlib.

This tool allows you to input text (or load from a file) and performs end-to-end NLP analysis including tokenization, stopword removal, stemming, lemmatization, POS tagging, named entity recognition, n-grams, TF-IDF, sentiment analysis, readability, and visualizations.

---

## 🚀 Features

-   📑 **Sentence & Word Tokenization**
-   🛑 **Stopword Removal**
-   📖 **Vocabulary Extraction**
-   ✂️ **Stemming & Lemmatization**
-   📊 **Word Frequency** (Top 10 words)
-   🏷 **POS Tagging** (Nouns, Adjectives, Verbs, etc.)
-   👫 **Bigrams & Trigrams**
-   🏢 **Named Entity Recognition (NER)**
-   📈 **Term Frequency (TF) & TF-IDF**
-   😀 **Sentiment Analysis** (via TextBlob & VADER)
-   📚 **Readability Metrics** (Flesch Reading Ease, Gunning Fog Index)
-   🧠 **Topic Modeling** with Gensim LDA
-   🎨 **Visualizations**:
    -   Word Frequency Bar Chart
    -   POS Tag Distribution Pie Chart
    -   Word Cloud
    -   Bigram Network Graph

---

## 🛠 Installation

Clone this repository and install dependencies:

[https://github.com/Sage-Of-Nine-Paths/NLP-Toolkit/](https://github.com/Sage-Of-Nine-Paths/NLP-Toolkit)

Install Python dependencies:

```bash
pip install nltk textblob textstat wordcloud matplotlib seaborn gensim scikit-learn
```

Download required NLTK resources (first-time only):

```python
import nltk
nltk.download("punkt")
nltk.download("stopwords")
nltk.download("averaged_perceptron_tagger")
nltk.download("wordnet")
nltk.download("omw-1.4")
nltk.download("maxent_ne_chunker")
nltk.download("words")
```

-----

## ▶️ Usage

Run the script:

```bash
python nlp_toolkit.py
```

You will be prompted:

```
=== NLP Toolkit ===
Do you want to enter your own text? (y/n): 
```

  - Enter `y` to type custom text.
  - Enter `n` to load text from `sample.txt`.

-----

## 📊 Example Output

For input text:

```
Natural Language Processing (NLP) enables computers to understand and process human language. It involves tasks such as tokenization, stop-word removal, lemmatization, and POS tagging. NLP has applications in machine translation, sentiment analysis, chatbots, and more.
```

### Sample Results

  - **Sentences**: 3
  - **Tokens**: 46
  - **Vocabulary Size**: 23
  - **Top Frequent Words**: `[('NLP', 2), ('language', 2), ...]`
  - **Nouns**: `['Language', 'Processing', 'NLP', 'computer', ...]`
  - **Adjectives**: `['Natural', 'human']`
  - **Readability (Flesch)**: \~ -76.2 (very complex)
  - **Sentiment (TextBlob)**: Polarity = 0.12, Subjectivity = 0.36
  - **Topics (LDA)**: e.g. language, processing, translation, machine

-----

## 📉 Visualizations

The toolkit generates multiple plots:

  - Word Frequency Bar Chart
  - POS Tag Distribution Pie Chart
  - Word Cloud
  - Bigram Network Graph


-----

## 📂 Project Structure

```
nlp-toolkit/
│── sample.txt          # Sample input file
│── nlp_toolkit.py      # Main script
│── README.md           # Documentation
```

-----

## ✅ Future Improvements

  - Build a Streamlit/Gradio Web UI
  - Multi-language support

<!-- end list -->
