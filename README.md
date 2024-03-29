# NLP
Machine Learning


-----------
|Description|
----------
This particular challenge is perfect for data scientists looking to get started with Natural Language Processing.
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

-----------
|Evaluation|
----------
Submissions are evaluated using F1 between the predicted and expected answers.

F1 is calculated as follows:
F1=2∗precision∗recallprecision+recall
where:

    precision=TPTP+FP
    recall=TPTP+FN
and:

    True Positive [TP] = your prediction is 1, and the ground truth is also 1 - you predicted a positive and that's true!
    False Positive [FP] = your prediction is 1, and the ground truth is 0 - you predicted a positive, and that's false.
    False Negative [FN] = your prediction is 0, and the ground truth is 1 - you predicted a negative, and that's false.
    
-----------
|Dataset Description|
----------
What files do I need?
You'll need train.csv, test.csv and sample_submission.csv.

What should I expect the data format to be?
  Each sample in the train and test set has the following information:

The text of a tweet
  A keyword from that tweet (although this may be blank!)
  The location the tweet was sent from (may also be blank)
  What am I predicting?
  You are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.

Files

    train.csv - the training set
    test.csv - the test set
    sample_submission.csv - a sample submission file in the correct format
    
Columns
    id - a unique identifier for each tweet
    text - the text of the tweet
    location - the location the tweet was sent from (may be blank)
    keyword - a particular keyword from the tweet (may be blank)
    target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)
