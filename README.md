# UISProject_NLPAnalysis

# Reddit Semantic Analysis – A Case Study on Public Discourse

## Abstract
This repository contains the implementation of a Natural Language Processing (NLP) pipeline developed to investigate public discourse on Reddit.  
The project focuses on collecting, preprocessing, and analyzing large-scale textual data to extract semantic patterns and community narratives.  
It is intended as a reproducible framework that can be adapted to similar research contexts involving social media and unstructured text.

---

## Research Objectives
- To systematically collect and structure Reddit data related to a case study of societal relevance.  
- To apply semantic and sentiment analysis methods in order to identify patterns in online discussions.  
- To evaluate the potential of NLP for supporting social science and computational linguistics research.  

---

## Methodology

### 1. Data Collection
- **Notebook:** `RedditScraper.ipynb`  
- Reddit posts and comments were collected using the [PRAW API](https://praw.readthedocs.io/).  
- Data was filtered to target specific keywords and subreddits of interest.  

### 2. Data Preprocessing
- **Notebook:** `DataManipulation.ipynb`  
- Steps included:
  - Removal of duplicates and noise.  
  - Normalization (tokenization, lowercasing, punctuation removal).  
  - Handling of missing values.  

### 3. Semantic Analysis
- **Notebook:** `SemanticAnalysis.ipynb`  
- Employed NLP libraries such as **spaCy, NLTK, TextBlob** and **scikit-learn**.  
- Techniques applied:
  - Vectorization (TF-IDF, embeddings).  
  - Clustering and topic modeling.  
  - Sentiment distribution analysis.  
  - Visualization of semantic structures.  

---

## Results (Summary)
- Identification of key narratives and recurring themes in Reddit discussions.  
- Evidence of sentiment polarization in relation to specific topics.  
- Semantic clustering highlights the emergence of coherent discourse communities.  

Detailed findings are reported in the related article: *[insert link to article or presentation when available]*.  

---

## Technical Requirements
- **Python 3.10+**  
- **Dependencies:** pandas, numpy, scikit-learn, nltk, spacy, textblob, matplotlib, seaborn, praw, tqdm  
- Execution environment: Jupyter Notebook or Google Colab.  

Install dependencies with:
```bash
pip install -r requirements.txt 
