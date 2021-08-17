# song-genre-classification

## Project Description:

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), we need to train a classifier to distinguish between the two genres based only on track information derived from [Echonest](http://the.echonest.com) (now part of Spotify). Our task is to predict whether we can correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc. We will go over implementations of common algorithms such as PCA, logistic regression, decision trees, and so forth

## Approach:

- Performed data preprocessing, feature reduction (PCA with scree plots), class balancing with SMOTE. 
- Applied Decision Tree, Logistic Regression Classifiers and compared them based on accuracy and F1-score. 

## Results:

- Achieved 10-Fold Cross Validation accuracy of 86 % with Logistic Regression. 

## Acknowledgements:

- https://www.datacamp.com/projects/449
