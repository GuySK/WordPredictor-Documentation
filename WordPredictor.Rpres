WordPredictor
===
author: gsk
date: April 2015

What is it?
===
<small style="font-size: .9em">

**WordPredictor** is a prototype of a statistical learning model for word prediction. 

Given a certain text, **WordPredictor** suggests one or more words for the following word. 

The current prototype version of **WordPredictor** has been trained inspecting more than 400,000 documents in a blogs data set.

**WordPredictor** has an average accuracy rate of of 16.9%, 7.4% and 4.6% for the first three words suggested correspondingly.

</small>

Highlights
===================================
<small style="font-size: .9em">

**WordPredictor** has been completely developed from scratch in R. It includes the following capabilities.

* Transformation, Training & Evaluation functions
* Prediction functions
* Data encoding functions
* Data structures management functions

**WordPredictor** uses an algorithm for encoding n-grams as floating-point numbers that allows for fast searches and efficient memory usage. The prototype application, code and data structures included, requires no more than 25 MB of storage.

</small>

Technical Specifications
===================================
<small style="font-size: .8em">
- **Prediction Model.** Trigram Back-off with Witten-Belt smoothing probabilities.
- **Word encoding.** N-grams stored as floating point numbers.<br>Max Vocabulary size is 131,071 types.
- **Stepped Training functions.** Designed to be run as a sequence of processes, they can train any amount of data, even in systems with small processing power. 
- **Lean data structures.** Just 5 R objects required (3 data frames, 1 hash table and 1 Environment). Low memory requirements thanks to encoding scheme.
- **Evaluation functions.** Randomized stepped functions. Supported metrics: Accuracy and Perplexity.
- **R Packages requirements.** TM and Hash.
</small>

WordPredictor App
===
![WordPredictor Shinny App](./WPFigures/Screen4.PNG)
<small style="font-size: .5em">

1. Enter the number of words you want to get.
1. Choose if you want probabilities for each suggested word.
1. Enter text and press the **PREDICT** button.

</small><small style="font-size: .7em">
Time to try it...<br>
<a href="http://guye.shinyapps.io/WordPredictor" target="_blank">Open **WordPredictor** Shiny App cliking here</a>
</small>

References
===
<small style="font-size: .9em">

You can find more information about **WordPredictor** here.

- [WordPredictor Extended Information]()
- [Model Training and Testing Code](https://github.com/GuySK/Capstone)
- [WordPredictor Code and Data Structures](https://github.com/GuySK/CapstonePj-DataProduct)
- [WordPredictor Metrics Evaluation]()

</small>
