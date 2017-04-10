# DS420 Machine Learning Resources


> Brad Miller <br />
> Olin 321 <br />
> bmiller@luther.edu <br />
> Office Hours: 2:00 -- 3:00 Daily.  By Appointment, [Use my Calendar](https://calendar.google.com/calendar/embed?mode=WEEK&src=millbr02%40luther.edu&ctz=America/Chicago)  Do not email me to ask when I can meet, use the calendar. <br />
> Slack Channel:  I'll use this to post hints and screen captures of notes.  Using your norsekey [signup for slack](https://luthercs.slack.com/signup)

* [Jupyter Notebook Server](https://knuth.luther.edu:8443) on knuth

## Schedule for Spring 2017

### Week of April 10

* Grayscale Conversion
* Perceptual Hash
* Gradient calculation

    We use a perceptual image hash called dHash (“difference hash”), which was developed by Neal Krawetz in his work on photo forensics. It’s a very simple but surprisingly effective algorithm that involves the following steps (to produce a 128-bit hash value):

    1. Convert the image to grayscale
    2. Downsize to a 9x9 square of gray values (or 17x17 for a larger, 512-bit hash)
    3. Calculate the “row hash”: for each row, move from left to right, and output a 1 bit if the next gray value is greater than or equal to the previous one, or a 0 bit if it’s less (each 9-pixel row produces 8 bits of output)
    4. Calculate the “column hash”: same as above, but for each column, move top to bottom
    5. Concatenate the two 64-bit values together to get the final 128-bit hash

    Using the cat as a sample image:

    ```
    from skimage import data
    cat = data.chelsea()

    I get the following hash value:  34915958146687236057193665901289989262173766774601642120423352010357722744229801684300512507318457538866989474872132612585051623814050377534543743034965266053329718
    ```

### Week of March 13

#### Face Recognition Project

* [Image Processing Tutorial](http://www.python-course.eu/python_image_processing.php)
* [Image Convolution](https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721#.dk8sxq6pj)
* [Face Recognition](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78#.mxargj89r)


### Week of March 6

* Monday
  * Logistic Regression -- listen to Data Skeptic podcast mini
  * https://dataskeptic.com/blog/episodes/2017/logistic-regression-on-audio-data

* Wednesday -- No Class
* Friday -- No Class


#### Week of Feb 27
* Wednesday
  * Perceptron Homework due

* Friday
  * Concepts from Chapter 4
  * Lab on Perceptron learning rates and improvements -- Due next Wednesday

**Assignment for Monday**

* Find a dataset that is suitable for clustering.  Make up a Hypothesis about the dataset that you would like to test.  find one where the data already has a categorical variable so you can do an experiment to see how well a couple different algorithms work for that data.  You will work on performing this experiment and it will be due Monday March 13.

#### Week of Feb 20
* Perceptrons and binary clustering

#### Week of Feb 13
* working through chapter 2

#### Week of Feb 6
* working through chapter 2

#### Week of Feb 1

* Jupyter Notebooks and Pandas (If you were in 320 this is review)
* Plotting with Pandas, matplotlib, Bokeh, Altair, etc.

** For Friday **

* Read Chapter 1 of [HoML](http://shop.oreilly.com/product/0636920052289.do)

**Resources**

* [ipython Notebook cheatsheet](http://nbviewer.ipython.org/github/pybokeh/ipython_notebooks/blob/master/pandas/PandasCheatSheet.ipynb#options)
* [important features in Pandas](http://nbviewer.ipython.org/urls/gist.github.com/wesm/4757075/raw/a72d3450ad4924d0e74fb57c9f62d1d895ea4574/PandasTour.ipynb)
* [Pandas Tutorial Part I](https://www.dataquest.io/blog/pandas-python-tutorial/)
* [Pandas Tutorial Part II](https://www.dataquest.io/blog/pandas-tutorial-python-2/)

#### Week of Feb 6

* We will work through the example in chapter 2 together
* Getting data
* Cleaning up data
* Our first ML algorithm

**For Monday** Read chapter 2 quickly.

**Other Resources**

* Machine Learning Overview with scikit-learn
* First half of https://www.youtube.com/watch?v=L7R4HUQ-eQ0
