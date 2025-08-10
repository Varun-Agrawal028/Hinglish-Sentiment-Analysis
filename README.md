Unsupervised Sentiment Analysis of Hinglish
📌 Overview
This project focuses on unsupervised sentiment analysis of Hinglish text — a mix of Hindi and English often found in social media, chats, and online forums. Unlike supervised approaches, this method does not rely on pre-labeled datasets. Instead, it leverages BERT-based contextual embeddings and clustering algorithms to automatically group sentences into sentiment categories. The approach is optimized for handling Hinglish-specific challenges such as spelling variations, transliteration, and mixed script usage.

🚀 Features
Text Preprocessing: Handles transliteration, stopword removal, and normalization for Hinglish data.

Contextual Embeddings: Uses sentence-transformers for deep semantic representation.

Clustering: Applies KMeans for unsupervised sentiment grouping.

Rule-Based Enhancement: Incorporates polarity words, negations, and emoji sentiment scoring.

Visualization: Generates pie charts, bar plots, and boxplots to illustrate sentiment distribution.

📂 Dataset
The repository includes a Hinglish dataset of 4,000 sentences.

File location: data/hinglish_sentences.csv

🛠️ Technologies Used
Python

pandas, numpy

scikit-learn

matplotlib, seaborn

sentence-transformers

nltk, spacy

umap-learn

📊 Example Output
Sentiment distribution pie chart

Cluster visualization using UMAP

Top positive & negative words by frequency

📜 How to Run
Clone the repository:
git clone https://github.com/YourUsername/Hinglish-Sentiment-Analysis.git

cd Hinglish-Sentiment-Analysis

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook Hinglish.ipynb

📌 Future Enhancements
Integration with BERTopic for topic modeling

Fine-tuning a Hinglish RoBERTa model for classification

Interactive dashboard with Plotly or Streamlit