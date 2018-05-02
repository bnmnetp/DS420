# DS420 Machine Learning Resources


> Brad Miller <br />
> Olin 321 <br />
> bmiller@luther.edu <br />
> Office Hours: 9:30 -- 10:30 Tues, Wed, Thurs.  Other times By Appointment, [Use my Calendar](https://calendar.google.com/calendar/embed?mode=WEEK&src=millbr02%40luther.edu&ctz=America/Chicago)  Do not email me to ask when I can meet, use the calendar. <br />
> Slack Channel:  I'll use this to post hints and screen captures of notes.  Using your norsekey [signup for slack](https://luthercs.slack.com/signup)

* [Jupyter Notebook Server](https://knuth.luther.edu:8443) on knuth

## Final Project


Your final project will be some kind of applied machine learning system that you will demo during the final week of class.  Some examples or ideas to get you thinking include:

* A face recognition system that would be capable of identifying your classmates.
* An image recognition system that can decide whether a given image contains a particular object.
* Build a skill for Alexa or Google Home
* Create a simple chat bot
* Build a neural net that can predict the next word in a sentence or next letter in a word.
* I might also accept a project where you take on a contest data set from kaggle that would use a neural network.  

You will find publications that can help you or even lead you through some version of many of these ideas and you are welcome to use and cite such an article.

This project can be a team project of no more than 3 people.

We are getting close to the end of the semester so you really need

You will demo these projects on the last day of class.

## Schedule for Spring 2018
### Week of May 8



### Week of May 1

* Hand written digit recognition with Keras and tensorflow
* See [Good starting docs](https://machinelearningmastery.com/build-multi-layer-perceptron-neural-network-models-keras/)
* Image processing with numpy
* Convolutional Neural Networks


### Week of April 24

* Tuesday Multi-Layer Perceptrons

* Thursday - No Class

  * Starting from your mid-term project See if you can improve your recommendations by doing the following:

    1. Do some exploratory data analysis on the incorrectly classified rows of data.  What can you learn aobut this subset?  How does it compare to the dataset as a whole or even look at how it compares to the set of correctly classified instances.  Does this inspire any further preprocessing of the data or perhaps some additional variables that  you could add?  If so add them and investigate the results.
    2.  Use either the GridSearchCV or RandomizedSearchCV class to try to find the best values for the hyperparameters for one or more of your algorithms.  You should use the sklearn documenation to select some hyper parameters as well as for the details of how to use the Grid or Randomized search models. 
    3. Finally, the ensemble learning idea could really help improve your results.  That is use all three (or more) of your models and have them vote on the final classification.  You can implement a simple Python class that provides a fit and predict method.


### Week of April 17

* Tuesday - In class presentations
* Thursday - Perceptrons -- Neural Networks
* Here are a couple of good resources for you to watch on your own:
  
  - [Neural Networks Demystified](https://www.youtube.com/playlist?list=PLiaHhY2iBX9hdHaRr6b7XevZtgZRa1PoU)  - Even if you don't follow all of the calculus these are still quite good to help you get a feeling for backpropagation.
  - [Step by Step backpropagation](https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/) Walks you through a back propagation example one step at a time.  Again there is calculus involved but it can still help you get a good feel for how the learning works.

### Week of April 10

* Tuesday - No Class
* Thursday - Presentations of midterm projects

### Week of April 3

* Tuesday  -- 

  * [Shared Spreadsheet for Midterm Datasets](https://docs.google.com/spreadsheets/d/14UQbP5DUnkTGpVX4qDNpb1woel9G9qagY3q14phrmJM/edit?usp=sharing)
  
  * https://github.com/dask/dask-tutorial

  * Team work on contest

  * Midterm Analysis Requirements
    
    * Select a dataset that requires classification -- I'll set up a shared google spreadsheet for you to publish your selected dataset.  I'd like to keep duplication to a minimum.
    * Prepare a Jupyter notebook that demonstrates you have done exploratory data analysis on your selected data set.  Make sure you document at the top of the notebook what you are classifying.
    * Clean and prepare your dataset, documenting any additional variables you have computed, rescaling, removal of variables, etc.
    * Compare the results of the classification task using 3 different methods that we have discussed in class.  You should have a summary section where you do the comparison of - accuracy, confusion matrix, report, ROC curve and area under the ROC.  Make sure to explain any big differences between your different methods.
  
  * Due: By Thursday April 12.  We will use class time on the 12th and 17th for each of you to make a presentation of your work.

* Thursday - short team presentations on contest
  
  * By Tuesday April 10 Can you reproduce your results on the full data set??

### Week of March 13

* Look at the Gaussian Naive Bayes and Decision Tree classifiers and/or dive into the kaggle contest.

* Tuesday

  - Take a look at [This Kaggle Contest](https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection?utm_medium=email&utm_source=intercom&utm_campaign=talkingdata+competition+2018)  Shall we give it a try?

### Week of March 6

* Tuesday 

  - Logistic Regression
  - Gradient Descent

* Thursday

  - Finish up Gradient Descent

    - Run our linear regression algorithm on the mushroom data -- We'll need to tweak our class just a bit to adjust sizes based on the data we give it.
    - Tweak our learning to adjust the learning rate as we iterate
    - Convert our algorithm to learn using the logistic function *and be amazed*
    - Make a version that can use the logistic regression algorithm to classify multiple classes


### Week of Feb 27

* Tuesday 

  - Regression with the mushroom data.

* Wednesday -- iriskm assignment due at 5:00


* Thursday -- Guest speaker on Support Vector Machines


### Week of Feb 20

* Tuesday

  - finish up the curse of dimensionality
  - what is principle components analysis
  - doing PCA on our mushroom data
  - doing PCA with iris data

* Wednesday -- First Iris Assignment due at 5:00

* Thursday
  
  - Kmeans clustering
  - Kmeans on our reduced PCA data
  - scoring kmeans


### Week of Feb 13

* For Tuesday you should have asked and answered two questions about the mushroom data set.  Be prepeared to share those questions and answers in class
* Tuesday: - The Curse of dimensionality


* Thursday: - Principle Components Analysis

### Week of Feb 8

* Mushrooms! - Should you eat this one or not?

* Getting data
* Cleaning and plotting data
* Starting to use scikit-learn

**Resources**

* Machine Learning Overview with scikit-learn
* First half of https://www.youtube.com/watch?v=L7R4HUQ-eQ0

* [ipython Notebook cheatsheet](http://nbviewer.ipython.org/github/pybokeh/ipython_notebooks/blob/master/pandas/PandasCheatSheet.ipynb#options)
* [important features in Pandas](http://nbviewer.ipython.org/urls/gist.github.com/wesm/4757075/raw/a72d3450ad4924d0e74fb57c9f62d1d895ea4574/PandasTour.ipynb)
* [Pandas Tutorial Part I](https://www.dataquest.io/blog/pandas-python-tutorial/)
* [Pandas Tutorial Part II](https://www.dataquest.io/blog/pandas-tutorial-python-2/)
