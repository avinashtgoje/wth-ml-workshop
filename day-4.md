
# 17th March 2017

## All knowledge accumlulated here are provided by the workshop participants.

## Please get ready the following BEFORE the workshop:
- load iris data into `dataframe`
- split the data into training and test set
- train a k-nn classifier
- have www.7-zip.org/ program downloaded (for imdb dataset)

## How well the model is performing?
- what metrics do sklearn provide
  -?
- **confusion matrix**
- http://machinelearningmastery.com/classification-accuracy-is-not-enough-more-performance-measures-you-can-use/

- **Evaluation vs Cross-Validation**
- https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-evaluate-model-performance
- Performance measures for machine learning
- https://www.cs.cornell.edu/courses/cs578/2003fa/performance_measures.pdf
- http://machinelearningmastery.com/how-to-evaluate-machine-learning-algorithms

- **Unbalanced Data**
- http://machinelearningmastery.com/tactics-to-combat-imbalanced-classes-in-your-machine-learning-dataset/
- https://www.quora.com/In-classification-how-do-you-handle-an-unbalanced-training-set

## Today's lab
- [Hands-on exercise](https://github.com/ryubidragonfire/python-machine-learning-101/blob/master/model-evaluation.ipynb)

# Group project
- 4 groups, each group with 2-3 members
  - Robot Iris
  - Fun with Data
  - Pyfun
  
- define a classification question
  - Robot Iris
    - IMDb score (labelled as high / medium / low)
    - Country of origin
    - Facebook likes
  - Fun with Data
    - [Current choice]Predict the genre of the movie depending on x features e.g. Plot key words, content_rating, actors, facebook likes, year?
    - Predict the rating of the movie depending on xfeatures e.g. Plot key words, Actors, facebook likes, age of the movie, title length
    - Predict the parental guidance the be depending on x features
    - Predict the country of origin of the movie depending on x features
    - Predict the duration of the movie depending on x features
    - Predict the budget of the movie depending on x features - complexity with year made and inflation.
  - Pyfun
    - Predict the gross earnings depending x features
  
- build a classifier that can answer that question
- suggest: come in every Friday to disucss with your group member and work on it.

## github
- create a repo for your project, with your team members as `contributor`. 
- you are not allowed to leave the workshop, until you get this done :)

## imdb dataset
- http://www.imdb.com/interfaces, click on either of these:
 - ftp.fu-berlin.de (Germany)
 - ftp.funet.fi (Finland)
- imdb dataset prepared by [chuansun76](https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset)
  - download this one
  - visualise the dataset
  - what questions to ask? 
  - what are the possible solutions (limit this to classification, for now)?

## imdb example
- https://blog.nycdatascience.com/student-works/machine-learning/movie-rating-prediction/

lots of examples of manipulating the data set here:
https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset/kernels

- Natural Language Toolkit (NLTK) - processing human language
- https://nltk.readthedocs.io/en/latest/



