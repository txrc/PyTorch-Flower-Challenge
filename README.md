# PyTorch-Flower-Challenge
The PyTorch Scholarship challenge from Facebook needs us to classify the species of 102 different flowers into their respective classes using what we have learnt in the course. Transfer learning is used and I have specifically chosen ResNet18 for training as well as evaluating the model on the validation set.

## The Dataset
The data set contains images of flowers from 102 different species. You can download the images from [here](https://s3.amazonaws.com/content.udacity-data.com/courses/nd188/flower_data.zip) as a zipped archive. Just unzip it and you should be good to go. 
Train and Valid datasets are provided and will be used to train and fine tune the hyperparameters of the model based off the validation set. The test set is withheld by Udacity and we will need to submit it to their workspace for evaluation.