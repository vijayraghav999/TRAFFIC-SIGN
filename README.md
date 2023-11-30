# **Traffic Sign Recognition**  
Traffic Sign Recognition is used to detect various road signs using image classification. It uses image processing techniques to detect the traffic signs. You must have heard of self-driving cars in which the passenger can fully depend on the car for traveling. This TSR helps vehicles to understand and follow traffic rules. There are several different types of traffic signs like speed limits, no entry, traffic signals, turn left or right, children crossing, no passing of heavy vehicles, etc. Traffic signs classification is the process of identifying which class a traffic sign belongs to. 

#### -- Project Status: [Completed]  

### **Dataset**
For this project, I used public dataset available at Kaggle. Here is [link](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign).

### **Methods Used**
* Machine Learning
* Deep Learning
* Feature Encoding
* Regularization Techniques

### **Technologies**
* Python
* Numpy
* Pandas
* Tensorflow, Keras
* Sklearn, jupyter


### **Description**

The dataset contains 40,000 training examples and 12,000 test examples. The project is a single-image, multi-class classification problem. It contains more than 40 classes and real-world examples. Our objective is to classify an image and identify its class Id (output). The main challenge I faced is sizes of training images are not consistent. So I used the inbuilt module in Keras to resize every image to a particular size. Since Convolutional Neural Nets are best suited for image recognition tasks so I used CNN for my project. By using regularization technique called dropout, I was able to increase the accuracy of my model from 91% to 96%.

### **Steps to build this Project**
* Import the packages
* Load the data
* Data Exploration
* Splitting train data into training and validation sets.
* One hot encoding (optional)
* Build the CNN model
* Train and validate the model
* Test the model with test dataset

### **Results**
* Model seems to perform very well on training and validation sets,
* The Accuracy on test dataset is 96.43%.
* Go through my jupyter notebook for more clear explanation.
