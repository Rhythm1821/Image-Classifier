# Image Classifier

This repository contains code for an image classifier that uses Support Vector Machine (SVM) to classify images into two categories: 'empty' and 'not_empty'.

## Requirements

To run the image classifier, ensure you have the following packages installed in your environment:

scikit-learn
scikit-image==0.19.3
numpy

You can install these dependencies by using the provided requirements.txt file:

pip install -r requirements.txt

## Dataset

The image classifier uses a dataset stored in the 'clf-data' directory. The dataset consists of images in two categories: 'empty' and 'not_empty'. The images are resized to 15x15 pixels using scikit-image's resize function.

The dataset can be accessed from the following link: 

https://drive.google.com/file/d/11DyZ165lZGzULEZSQNofyy9A8xaYgFJ2/view 

## Usage

Download the dataset from the provided link and place it in the 'clf-data' directory.

Run the 'main.py' script to train the image classifier and test its performance:

python main.py

The script will perform the following steps:

* Prepare the data by loading images from the 'clf-data' directory and resizing them.
* Split the data into training and testing sets.
* Train the Support Vector Machine classifier using GridSearchCV to find the best hyperparameters.
* Test the classifier's performance on the test set and print the accuracy score.
* Save the trained model as 'model.pkl'.

## Note

Make sure that the dataset files are organized correctly in the 'clf-data' directory, with images of each category placed in separate subdirectories.

## Support

If you have any questions or need assistance, feel free to reach out.