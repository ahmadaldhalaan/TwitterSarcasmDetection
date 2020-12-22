# Twitter Sarcasm Detection

This Twitter Sarcasm Detector was submitted as part of a text classification competition for the Master of Computer Science program at the University of Illinois at Urbana-Champaign.

The code classifies tweets as either “Sarcasm” or “Not Sarcasm”. We are given 5000 tweets with half labelled as “SARCASM” and the other half labelled as “NOT_SARCASM”. The code pre-processes this training set, trains a model and evaluates the model on a test set of 1800 unlabeled tweets.

We use a large-scale pre-trained model, called DistilBERT, which is then fine-tuned on our twitter sarcasm dataset. Our model achieves an F1 score of 0.735 with a precision of 0.626 and a recall of 0.889, outperforming the competition baseline. 

Implementation and usage details are included along with the python code for reproducibility.
