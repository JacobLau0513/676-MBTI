# Introduction
This repository is used to predict personality types using nueral networks.
## MBTI dataset
kaggle dataset: https://www.kaggle.com/datasnaek/mbti-type/kernels 
The Myers-Briggs Type Indicator (MBTI) is a widely-used personality assessment tool. It has four pairs of preferences: 

* Introversion/Extraversion
* Intuition/Sensing
* Feeling/Thinking
* Perception/Judging

# Training model

    python train.py -m model_name [-e|-s|-c]
    
# Files
MBTI.csv, glove.6B.50d.txt
___
# Model Infomation
CNN info:

    Accuracy(Total) on test set(20%) = 0.28
    [I] precision: 0.544, recall: 0.919, f1: 0.684
    [E] precision: 0.970, recall: 0.774, f1: 0.861
    [N] precision: 0.509, recall: 0.987, f1: 0.672
    [S] precision: 0.998, recall: 0.853, f1: 0.920
    [T] precision: 0.890, recall: 0.763, f1: 0.821
    [P] precision: 0.767, recall: 0.892, f1: 0.825
    [J] precision: 0.808, recall: 0.787, f1: 0.797
    [F] precision: 0.673, recall: 0.701, f1: 0.686
