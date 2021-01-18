# NIH-Chest-x-ray-detection

There are 5,606 images of size 1024*1024 pixel in .png format and there are total of 15 classes.
BASIC PREPROCESSING
 Added path to image index
 Remove Y,M,D from patient age
 Split labels in finding label column
 Converted labels into dummies
EDA
 Plotted random images using matplotlib
 countplot for label distribution using seaborn
 countplot for label distribution across patient gender
 plot of positive and negative frequencies of class to check imbalancing.
 histogram for visualizing mean and standard deviation of image
IMAGE PREPROCESSING
 Imagedatagenerator for samplewise mean and standard deviation and converted image to 128*128 pixel size.
 made a customized loss function to treat class imbalancing problem.
MODEL
 convolutional neural network
EVALUATION
 roc curve for evaluation
 
 
  
 
