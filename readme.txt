In the "Complete code" folder:
"train_model.py" is the file that performs the training.
"test_model.py" is the file that executes the test.
"train_data" folder is a training sample set.
"test_result.py" is the folder where the segmentation result graph is saved.
"logs" is the folder that generates the trained model.

In the "Total data set" folder:
"Test set" is the folder of the test set, which contains test sets in a pure background and in a complex background.
"Training samples" is the folder for the training sample set. It contains training sets for each part of the fish (which contains the annotation files required for training.)

When training, change the name of the corresponding study object in "train_model.py".
When testing, change the name of the corresponding study object in "test_model.py".