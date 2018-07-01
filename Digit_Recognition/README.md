# Digit Recognizer Challenge Kaggle

[Dataset](https://www.kaggle.com/c/digit-recognizer/data)

Hand written digits classification task
The shared kernel gives 0.97314 score on Kaggle leaderboard.

The grid search step can't be performed on all of the data because of the large size.
Around 5000 can be taken for this step
## Steps
1. Perform feature scaling
2. Perform PCA (200 was chosen as it covered around 87% of variance)
3. Perform Grid Search for SVM ( C=8 and gamma=0.002 was found best)
4. Output the results

### Improvemnets
CNN can be used for better results
