Repository Structure:
  Naive_Bayes.py, GLM.py, LSTM.py, and Both_HMMs.py are the code to the machine learning models 
  Machine Learning Models for Decoding Eye State EEG Data.pdf is our 9-page technical paper

Project Description:
  This project involved testing five machine learning models to determine whether someone's eyes were open or closed based on EEG data. Our implementation of a unidirectional LSTM was the most effective, with 70% accuracy. We used a linear regression model (55% accuracy) and a naive bayes model (59% accuracy) as our baselines. Our unsupervised Hidden Markov Model (HMM) (64% accuracy) improved upon the static models by capturing temporal patterns in the signal. Our supervised HMM (67% accuracy), which incorporates the eye-state labels into its state transitions, performed even better, achieving the second highest accuracy. Our best results came from a unidirectional LSTM (70% accuracy), which effectively handled the temporal dependencies and noise in the EEG data, highlighting the value of sequence-aware models for predicting real world behavior.
