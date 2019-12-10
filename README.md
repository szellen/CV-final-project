# Food 101: A Healthy-eating Camera for Calorie Detection
This is the final project for UVA 2019Fall Computer Vision class.
In this work, we will use reduced-size Food101 data set. We will first apply AlexNet modal designed by Alex Krizhevsky in 2012 to extract features. Then, we will use fully connected layers to classify images into 55 food categories. We will discuss different activation functions' performance for our data set, and experiments how the food classification and calorie detection works for real image taken in our daily life.

## Data Set
We took first 55 food class from Food-101 dataset. Original data can be downloaded from https://www.vision.ee.ethz.ch/datasets_extra/food-101/

## File organization
* Part_1_Feature_Extraction_with_pretrained_AlexNet.ipynb: Extract features using Alexnet
* Part_2_Classification_and_Calories_Prediction.ipynb: Transfer learning, classification and calories prediction
* Plot: plots included in the paper
* Pickle file: preprocess image data from our own image
* Food 101-A Healthy-eating Camera for Calorie Detection: final paper summarized our works

