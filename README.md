# OpenCV
Image Recognition by OpenCV

The main property of Viola-Jones algorithm is that training is slow, but detection is fast.

The characteristics of Viola–Jones algorithm which make it a good detection algorithm are:
Robust – very high detection rate (true-positive rate) & very low false-positive rate always.
Real time – For practical applications at least 2 frames per second must be processed.
Face detection only (not recognition) - The goal is to distinguish faces from non-faces 
(detection is the first step in the recognition process).

The algorithm has four stages:

Haar Feature Selection
Creating an Integral Image
Adaboost Training
Cascading Classifiers
