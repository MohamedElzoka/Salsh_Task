## Salsh_Task
# Data-Collection 
in this task i take screenshots form slash mobile app and classify them to 4 categories(handmade, fashion, cosmetics,accssespries)
they all about 200 photo and i didnot use scrapping but i want to use a technecis for generating images as GANS and AutoEncoder but as i work on local CPU i couldn't and also because of time constrain so i make Data Augumentation 
# 1-preprocessing:
-Get list of all image files
-Extract class labels from file paths
-Map class labels to integers
-Convert labels to integers
-Create DataFrame with file paths and labels
-Convert label column to string
-Split data into training and validation sets
# Create data generators for training and validation
-Make Data Agumentation (rescale-rotation-width shift-height shift-zoom-flip)
# make some visualization to our data and their Labels
# Define the model architecture:
CNN Model using some technecqes as early stopping and regularization 
1-Compile the model
2-Define early stopping to prevent overfitting
3-Train the model
4-Evaluate the model
# Fine-Tuning
i use these models (VGG16,ResNet50,InceptionV3,DenseNet121)
# Testing the model with sampels outside the dataset
Getting sampels outside the Dataset
# link of demonstrating video and Dataset
https://drive.google.com/drive/folders/1hyhStDSJ2vgQNNUr0nbMY5Ohgu0JLg9E
