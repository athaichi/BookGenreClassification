
<!--# BookGenreClassification -->

Book Genre Classification Based on Synopsis
==========================================
*AIT Fall 2021 Deep Learning Final Project*
--------------

Authors: Ayla Kurdak and Lanea Rohan

Abstract
--------
The goal of this project is to create a deep neural network in order to produce a list of genre tags from a book synopsis. The genres should correspond to the genre of the book the synopsis belongs to. The synopsis and genre tag data was collected from the **Blurb Genre Collection**, which you can find more about here: https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/blurb-genre-collection.html. 

Data
-----
As mentioned, we used the **Blurb Genre Collection** as our dataset. The dataset comes pre-divided into training, test and validation sets. The original dataset comes with a lot of extra information for each book entry - we pared it down to just the book synopsis and the list of genre tags. You can find the original datasets in the `\data` folder. To see our cleaned data, check in `\code\milestone1.ipynb`. 

Mile Stone 1
----------
For the python notebook for milestone one can be found in `\code\milestone1.ipynb`. The notebook takes in a text file from the collection of blurbs and outputs two arrays: a *X-set* (just the synopses of the books) and a *Y-set* (an array that contains each tag associated with the synopsis). You can see demonstrations of each input set (training, validation and testing) in this file as well. 

For a more in-depth look at how data changes at each step, check out the `\code\preMilestone1.ipynb`. 

