# Quora-Question-Pair-Similarity
To Avoid Overwriting of Answer for the Same Question

Over 100 million people visit Quora every month,  so it's no surprise that many people ask similarly worded questions. 
Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. 
Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

Problem statement:
Identify which questions asked on Quora are duplicates of questions that have already been asked.
This could be useful to instantly provide answers to questions that have already been answered.
We are tasked with predicting whether a pair of questions are duplicates or not.

We are dealing the problem as a Binary Classification.

DATA OVERVIEW :
- Data will be in a file Train.csv
- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate
- Size of Train.csv - 60MB
- Number of rows in Train.csv = 404,290
- We build train and test by randomly splitting in the ratio of 70:30 or 80:20

Refer Writeup for further details.
