<h1 align="center">
  <br>
  <img src="https://github.com/1Tatsumaru1/topic-and-image-classification/blob/master/img/yelp.png" alt="Yelp">
  <br>
  Topic and image classification
  <br>
</h1>

<h4 align="center">
  Based on  
  <a href="https://www.kaggle.com/kazanova/sentiment140" target="_blank">Yelp datasets</a>.
</h4>

![screenshot](https://github.com/1Tatsumaru1/topic-and-image-classification/blob/master/img/topics.png)

<p align="center">
  <a href="#description">Description</a> •
  <a href="#contents">Contents</a> •
  <a href="#credits">Credits</a> •
  <a href="#links">Links</a>
</p>

## Description

This project was part of my IA Engineering course at OpenClassrooms. 
The aim was to :<br>
* Analyse restaurant reviews by customer in order to détermine the various insatisfaction topics
  - Cleaning of the dataset (lemmatization, normalization, tokenization)
  - Topic determination through different means (LDA, TF-IDF, NMF, Word embeddings)
  - Hybridation of methods

* Analyse an image dataset in order to train a classification model able to sort pictures according to 5 preset categories (inside, outside, menu, food, drink)
  - Manual feature extraction using SIFT
  - Automatic feature discovery with deep learning using VGG16 and RESNET50

![screenshot](https://github.com/1Tatsumaru1/topic-and-image-classification/blob/master/img/features.png)

* Summarize the finding in a HTML web page (generated from Python)

* Build a requests pipeline allowing continuous data-collection from Yelp API (both legacy and GraphQL API have been tested)


## Contents

* **Findings** (HTML) : This findings oriented Web page displays nicely on any Web browser
* **Analysis** (Jupyter notebook) : contains all the analysis, topic discovery and image classification model building process

## Credits

This project makes use of the following packages:

- [Keras](https://keras.io/)
- [PIL](https://pypi.org/project/Pillow/)
- [NLTK](https://www.nltk.org/)
- [Scikit-learn](https://scikit-learn.org/stable/index.html)
- [Contractions](https://pypi.org/project/pycontractions/)
- [Gensim](https://pypi.org/project/gensim/)
- [pyLDAvis](https://pypi.org/project/pyLDAvis/)

## Links

> <a href="https://anthony.ledouguet.com"><img src="https://github.com/1Tatsumaru1/azure_reco_api/blob/main/img/world.png" alt="website" width="20" /> anthony.ledouguet.com</a><br>
> <a href="https://github.com/1Tatsumaru1"><img src="https://github.com/1Tatsumaru1/azure_reco_api/blob/main/img/github.png" alt="github" width="20" /> GitHub</a><br>
> <a href="https://www.linkedin.com/in/anthony-le-douguet/"><img src="https://github.com/1Tatsumaru1/azure_reco_api/blob/main/img/linkedin.png" alt="linkedin" width="20" />
LinkedIn</a>
