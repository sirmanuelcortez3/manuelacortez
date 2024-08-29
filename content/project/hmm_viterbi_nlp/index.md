---
date: "2024-02-25T00:00:00Z"
summary: Building and Evaluating a Hidden Markov Model and a Viterbi Algorithm in NLP
title: HMM and Viterbi in NLP
---
In this project, I built and evaluated a Hidden Markov Model (HMM) with a Viterbi algorithm for part-of-speech tagging using the Brown corpus. After pre-processing the data and splitting it into training and test sets, I trained five different HMM models with various smoothing techniques, such as Lidstone, Maximum Likelihood Estimation (MLE), and Expected Likelihood Estimation (ELE). I then evaluated each model by predicting tags on the test dataset and compared their performance using metrics like precision, recall, and F1-score. I analyzed the results to identify the best-performing model, taking into account the effects of different smoothing techniques and comparing them to a pure HMM. Finally, I selected the best model and serialized it with the `dill` library.

See [github repository](https://github.com/sirmanuelcortez3/HMM-Viterbi-in-NLP.git) for full project. Available upon request.