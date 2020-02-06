# Self-Driving-Car

Self-Driving-Car 
Problem Definition We are here building a minimal version of self driving car. Here, we have a front camera view. This will transfer input to the computer. Then Deep Learning algorithm in computer predicts the steering angle to avoid all sorts of collisions. Predicting steering angle can be thought of as a regression problem. We will feed images to Convolutional Neural Network and the label will be the steering angle in that image. Model will learn the steering angle from the as per the turns in the image and will finally predicts steering angle for unknown images. 


How to Run Just download the repository then run "Self-Driving-Car.ipynb" file for training the model. You can directly restore the pre-trained model from "Saver" folder and predict the output or fine-tune the model further.


Dataset Refer this: https://github.com/SullyChen/Autopilot-TensorFlow 


There are total 45406 images in the dataset along with their steering angles. 


We will split the dataset into train and test in a ratio of 80:20 sequentially. 


Objective Our objective is to predict the correct steering angle from the given test image of the road. Here, our loss is Mean Squared Error(MSE). Our goal is to reduce the MSE error as low as possible.  


Prerequisites You need to have installed following softwares and libraries in your machine before running this project.  Python 3: https://www.python.org/downloads/ Anaconda: It will install ipython notebook and most of the libraries which are needed like pandas, matplotlib, numpy and scipy: https://www.anaconda.com/download/ 


Libraries: Tensorflow: It is a deep learning library. pip install tensorflow OpenCV: It is used for processing images. pip install opencv-python 


Authors • Shubham Shekhar- Complete work  


Acknowledgments • Applied AI Course
