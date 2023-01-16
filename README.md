# Deep Learning Project Seminar HBRS (Recommender System)

## Movie Rating Prediction with TensorFlow

This is a deep learning model for movie rating prediction using TensorFlow. The model uses a combination of user and movie embedding layers and dense layers to predict a rating for a given user and movie. The training process is logged using TensorBoard for visualization of the model's performance.

### Requirements
* TensorFlow
* Pandas
* Numpy
### Data Preparation
The model requires a dataset with columns for user, movie, and rating. The script maps the user and movie IDs to unique integers and creates a train and test set.

### Model Architecture
The model uses user and movie embedding layers to create a low-dimensional representations of the user and movie. These representations are then concatenated and passed through dense layers to make the final rating prediction.

### Training
The model is trained using the Adam optimizer and mean squared error loss function. The training process is logged using TensorBoard for visualization of the model's performance.

### Evaluation
The model's performance is evaluated by computing the Root Mean Squared Error (RMSE) of the predictions on the test set.

### This repository contains the following files:
* Slideshow of the final presentaion as a .pdf file.
* Jupyter Notebook file where the data preprocessing and all the coding of the recommender system is done.
* Screenshots of the results from different training and testing parameters.


### Template of the model and the used data can be found here:
* https://www.kaggle.com/code/morrisb/how-to-recommend-anything-deep-recommender


Sources:

* https://link.springer.com/content/pdf/10.1007/s11257-011-9112-x.pdf?pdf=inline%20link
* https://www.tensorflow.org/recommenders/examples/quickstart
* https://www.inf.unibz.it/~ricci/ISR/papers/ieeecomputer.pdf
* Also, with the help of ChatGPT
