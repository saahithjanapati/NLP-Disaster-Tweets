# NLP-Disaster-Tweets

This repository contains two baseline solutions for Kaggle’s [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started) competition.  
Both approaches fine-tune large pretrained language models and attach a lightweight linear classification head to predict whether a tweet is about a real disaster.

## Approaches

| # | Model | Notebook | Submission | Public LB Score |
|---|-------|----------|------------|-----------------|
| 1 | BERT-Base (uncased) + Linear Head | [`bert.ipynb`](bert.ipynb) | [`bert_submission.csv`](bert_submission.csv) | **0.83757** |
| 2 | GPT-2 (small) + Linear Head | [`gpt2.ipynb`](gpt2.ipynb) | [`gpt_submission.csv`](gpt_submission.csv) | **0.81090** |