Project Name: Images of dog and cats can be collected from Kaggle website .Train a convolutional network for its recognition.

Project Details:

This code assumes that the training data is in a folder in the following format:
/training_data
     /dogs
     /cats

Similarly, we need the validation dataset in the following format:

/testing_data
     /dogs
     /cats
	 
Training data packaged here is only a sample to facilitate the code run.


Step 1. In order to start the training: 

Run this command
	  python train.py --train training_data/ --val testing_data/ --num_classes 2

Step 2. Once your model is trained, it will save the model files in the current folder. 

In order to predict using the trained model, we can run the predict.py code by passing it our test image. 

      python predict.py testing_data/cats/cat.1110.jpg


The model included in this package is a trained model for a large number of training data. This can be used to predict in step2 

I have used python version 3.7.1
"# Project-Cats-Dogs-Classifier" 
