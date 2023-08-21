"# movie-sentiment-analysis" 


This app describes the implementation of sentiment analysis using Python.


1. First I loaded the necessary packages.
I chose python 3 for this project, and for inspiration I chose kaggle
Useful packages to load are numpy (for linear algebra),
pandas (read a text file that has a specific format that saves data in a structured table format)
and sklearn (make AI train). It is necessary to import all related nltk packages related to sentiment analysis.

2. Import os
Make the input data files available in the computer directory.
 In this case, running this will list the files in the inbox

3. Make the creation of the data in subjective and objective viewpoints of the sentences.
Read 100 obj phases and 100 subj phases.

4.We have split the 2 types of sentences to maintain an evenly balanced distribution.

5. I created unigrams for then the single strokes of the words that are used, managing the negation.
For unigram we will have 3 characteristics and all 3 are independent of each other.

6.We are ready to train our classifier on the training set and output the evaluation results:
Training classifier

7. Definition of test phrase list
Paragraph manipulation