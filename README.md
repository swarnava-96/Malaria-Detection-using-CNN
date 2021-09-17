# Malaria-Detection-using-Deep Learning
### Goal: The Goal of this project is to detect whether a person is suffering from Malaria or not using CNN and VGG19.

### About the Data set:
The data set is collected from [Kaggle](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria). I have used a small sample of this dataset that is present in the Dataset.zip file. The data contains cell images of human beings of two categories namely, Parasite (affected with Malaria) and Uninfected (not affected with Malaria).

### About the project:
In this project, I have created a CNN from scratch consisting of six hidden layers and two output layers. The model is trained on Google Colab using GPU and it took 15 minutes to complete the entire model training. The model worked well identifying images of both the categories. The training accuracy of the model is 99.7% and the validation accuracy is 94%. The model was run for 100 epochs setting steps per epoch equal to the training set length and the length of test set equals validation steps. 

Similarly, I have used a Transfer Learning technique, VGG19 on the same dataset and trained for 25 epochs and it gave me a training accuracy of 98% and a validation accuracy of 94%.

The following Google Drive link contains the model.

https://drive.google.com/file/d/1-Dz_UiJtCBmPe4DU9FYp7dLXVc9k84By/view?usp=sharing
