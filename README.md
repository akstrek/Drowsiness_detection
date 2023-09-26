# Driver Drowsiness Detection System with OpenCV & Keras

#### In this Python project, we will be making a drowsiness detection system. A countless number of people drive on the highway day and night, including taxi drivers, bus drivers, truck drivers, and people traveling long-distance. These people often suffer from lack of sleep, which can make it very dangerous to drive.

#### A large percentage of accidents are caused by drowsy driving. To prevent these accidents, we will build a system using Python, OpenCV, and Keras that will alert the driver when they are feeling sleepy. The system will use a camera to track the driver's eyes and facial expressions. If the driver's eyes are closed for an extended period of time or if their facial expressions indicate that they are drowsy, the system will alert the driver.

#### This drowsiness detection system has the potential to save lives by preventing drowsy driving accidents.

### Driver Drowsiness Detection Dataset
#### The dataset used for this model was created by us. We wrote a script to capture eyes from a camera and store them on our local disk. The images were taken under different lighting conditions and include people of all ages, races, and genders. We separated the images into their respective labels "Open" or "Closed" and manually cleaned the data by removing unwanted images. The dataset comprises around 7000 images.
#### After training the model on our dataset, we have attached the final weights and model architecture file "models/cnnCat2.h5".

### The Model Architecture
#### The model we used is built with Keras using Convolutional Neural Networks (CNN). A convolutional neural network is a special type of deep neural network which performs extremely well for image classification purposes.

### Project Prerequisites
#### OpenCV – pip install opencv-python (face and eye detection).
#### TensorFlow – pip install tensorflow (keras uses TensorFlow as backend).
#### Keras – pip install keras (to build our classification model).
#### Pygame – pip install pygame (to play alarm sound).
