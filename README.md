# song-genre-classification

## Project Description:

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), you will train a classifier to distinguish between the two genres based only on track information derived from [Echonest](http://the.echonest.com) (now part of Spotify). You will first make use of `pandas` and `seaborn` packages in Python for subsetting the data, aggregating information, and creating plots when exploring the data for obvious trends or factors you should be aware of when doing machine learning. Next, you will use the `scikit-learn` package to predict whether you can correctly classify a song's genre based on features such as danceability, energy, acousticness, tempo, etc. You will go over implementations of common algorithms such as PCA, logistic regression, decision trees, and so forth

## Approach:

- Performed data cleaning, merging, normalization, correlation analysis, feature reduction (PCA with scree plots) on datasets consisting of metadata (21 features) and metrics (danceability, acousticness etc.) data (9 features). 
- Handled class imbalance with under-sampling; Applied Decision Tree, Logistic Regression with GridSearchCV for hyperparameter tuning. 

## Results:

- Achieved accuracy of 82 % with Logistic Regression. 

## Acknowledgements:

- https://www.datacamp.com/projects/449
