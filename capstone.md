Word Prediction: Coursera Data Science Capstone Project
========================================================
author: Krishan Bhatt
date: November 29, 2016

This is the final project for the Coursera Data Science Specialization from the Johns Hopkins University in colaboration with SwiftKey.


Introduction
========================================================

<small>The goal of this capstone project is to build a shiny application that is able to predict the next word.

Following steps has been taken place to build a model:

> 1. Exploratory Analysis
> 2. Leaning and preparing the data
> 3. Build n-grams from the data corpus
> 4. Build frequencies from the n-grams
> 5. Build the prediction model

All text data that is used to create a frequency dictionary and thus to predict the next words comes from a corpus called HC Corpora.</small>

The Predective Model
========================================================

<small>For this prediction model we have built a series on n-grams from a Corpus of Text from Blogs, Twitter and News. The algorithms takes the last three words of the typed text and looks for matches in the frequency tables which are based on these n-grams.

n-gram is a contiguous sequence of n items from a given sequence of text or speech. The items can be phonemes, syllables, letters, words or base pairs according to the application.</small>


The Shiny Application
========================================================


<small>Using the algorithm, a Shiny (http://shiny.rstudio.com/) application was developed that accepts a 
phrase as input, suggests word completion from the unigrams, and predicts the most likely next word based 
on the linear interpolation of trigrams, bigrams, and unigrams. The application can be below link.

> https://kbhatt.shinyapps.io/Capstone_Project/ 

All the source files for this applicationcan can be found in GIT:

> https://github.com/kdbhatt/DataScience_Capstone 
</small>


Using the Application
========================================================

<small>User can type some text without punctuation in the input box. As the user types, the text is printed in the field below along with a suggested word completion. At the bottom of the screen, the 
predicted next word in the phrase is shown.</small>

![alt text](capstone.jpg)
