# Sign-Language-Recognizer

This project uses a simple CNN to classify the alphabets in the American Sign Language.

The data set consists of 2000 images of each alphabet, which has been split as 1750 for training and 250 for testing.

The model was trained on a very simple CNN with around 50,000 parameters and it gives an accuracy of 90-95%.
The training time is around 30 minutes for 25 epochs.

The model can be trained using model.py or you can directly use the trained weights (weights.h5).
Test.py is used to run the model on any given image in the test or training set.
Recognise.py is used to run the model on a live camera feed. To make sure that works properly, use the trackbars to set the hsv values
such that there is a clear contrast between the hand and the background.

All the relevant pictures can be found in the pictures folder.
