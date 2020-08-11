# Topic-Based-Sentiment-Detection
Developed an approach that given a sample identifies the topics along with their respective sentiments. 

The solution uses a Semi-Supervised Topic Modeling approach using Guided LDA (https://guidedlda.readthedocs.io/en/latest/), followed by Multi-Class classification on Review-Topic pairs. Features used are GloVe embeddings and Topic Distributions on Review and Topic texts.

Please refer to this doc file for data overview, modeling approach and other details: https://docs.google.com/document/d/1v7v2LLpVzu_fbWUKPyqVrLL49YjoIAQRxXKeJbrHwZ8/edit?usp=sharing

#### Pre-requisite packages/libraries
```
pip install nltk
pip install flair
pip install lda
pip install guidedlda
pip install spacy
python -m spacy download en_core_web_lg
```
