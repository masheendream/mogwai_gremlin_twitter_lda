# mogwai_gremlin_twitter_lda
This repository holds the SIUE Senior Project made by Caleb Hill, Derek Lopez, and Mike Holik for Gremlin Social

This project uses Latent Dirichlet Allocation (LDA) for twitter topic modelling. Six models are included in this repository, each one has been trained on users from a specific income group. For example, 'lda_model_40-60k_18topics.model' was trained on user text from the 40-60k income group and there are 18 topics used in this particular model. 

We cite this paper for the dataset of twitter id's and self-given user info that made this project possible:

Preoţiuc-Pietro D, Volkova S, Lampos V, Bachrach Y, Aletras N (2015). Studying User Income through Language, Behaviour and Affect in Social Media. PLoS ONE 10(9): e0138717


## To set up: 

### Enter your own Twitter API credentials in the provided credentials.json
This file is a template for your own credentials.

### Change directory to project.
```
cd senior-project-mogwai/code
```
### Install tweepy, gensim, pandas, nltk
```
pip3 install -r requirements.txt --user
```

##  To run: 
### Enter a twitter handle. This file will 
```
python3 user_stats.py 'TWITTER_HANDLE'
```


