The initial model produced Accuracy: 0.7282798886299133 which is below 0.75.

I made 3 attempts to improve the result (see   AlphabetSoupCharity_Optimisation.ipynb):

## Attempt 1.
A slightly more complex model with drop out layer.
Accuracy: 0.7271137237548828

## Attempt 2.
Using hyperparameters optimization.
Accuracy: 0.7309038043022156
Improved, but still below the target

## Attempt 3.
Using hyperparameters optimization with more complex parameters 
and oversampling with SMOTE and learninig rate scheduler.
Accuracy: 0.7326530814170837
Improved, but still below the target.

It looks like there should have been more data cleaning carried out before training the models.