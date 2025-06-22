![GitHub](https://img.shields.io/github/license/DataForScience/NLP)
[![Twitter @data4sci](https://img.shields.io/twitter/follow/data4sci)](https://twitter.com/intent/follow?screen_name=data4sci)
![GitHub top language](https://img.shields.io/github/languages/top/DataForScience/NLP)
![GitHub repo size](https://img.shields.io/github/repo-size/DataForScience/NLP)
![GitHub last commit](https://img.shields.io/github/last-commit/DataForScience/NLP)

[![Graphs For Science](https://img.shields.io/badge/Graphs_For_Science-Subscribe-blue)](https://graphs4sci.substack.com/)
[![Sunday Briefing](https://img.shields.io/badge/Sunday_Briefing-Subscribe-blue)](https://data4science.ck.page/a63d4cc8d9)


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DataForScience/NLP/master)

# Natural Language Processing For Everyone

### Code and slides to accompany the online series of webinars: https://data4sci.com/nlp by Data For Science.

### Run the code in Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DataForScience/NLP/master)

The rise of online social platforms has resulted in an explosion of written text in the form of blogs, posts, tweets, wiki pages, and more. This new wealth of data provides a unique opportunity to explore natural language in its many forms, both as a way of automatically extracting information from written text and as a way of artificially producing text that looks natural.

In this class we introduce viewers to natural language processing from scratch. Each concept is introduced and explained through coding examples using nothing more than just plain Python and numpy. In this way, attendees learn in depth about the underlying concepts and techniques instead of just learning how to use a specific NLP library.

## Schedule

### 1. Text Representation
- Represent words and numbers
- Use One-Hot Encoding
- Implement Bag of Words
- Apply stopwords
- Understand TF/IDF
- Understand Stemming

### 2. Topic Modeling
- Find topics in documents
- Perform Explicit Semantic Analysis
- Understand Document clustering
- Implement Latent Semantic Analysis
- Implement Non-negative Matrix factorization

### 3. Sentiment Analysis
- Quantify words and feelings
- Use Negations and modifiers
- Understand corpus based approaches

### 4. Applications
- Understand Word2vec word embeddings
- Define GloVe
- Apply Language detection

Slides: http://data4sci.com/landing/nlp/

## Is Traditional NLP (TF-IDF, BoW, syntactic parsing) Still Relevant?
✅ YES — but with a shift in purpose.
While large language models (LLMs) have revolutionized NLP, classic techniques still matter for:

# 🔧 1. Speed and Simplicity
TF-IDF, POS tagging, regex parsing are fast, interpretable, and light on memory

Used in search engines, spam filters, news deduplication, etc.

# 🧪 2. Explainability
A judge or doctor might not trust a BERT model, but they can understand TF-IDF weights or dependency trees

Classical NLP is easier to audit and debug

# 💡 3. Preprocessing for ML Pipelines
Tokenization, stemming, lemmatization, and named entity recognition (NER) are still core inputs to many systems — even those that aren't LLMs

# 🔗 4. Hybrid Systems
LLMs often use traditional NLP under the hood (e.g., for aligning outputs, extracting structured fields, or preparing training corpora)

# 🚪 5. Low-resource or Offline Environments
Mobile apps, embedded devices, or legal/medical deployments may avoid cloud-based models and use classic NLP

# 🌉 In Summary
Traditional NLP is no longer the final destination, but it is still a solid foundation — and often part of the road to deep semantic models.

You're doing exactly the right thing: mastering the basics so you can understand and even control the behavior of LLMs and embeddings later.
