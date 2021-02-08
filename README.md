# Face-Mask-Identifier
Mask Detection using OpenCV

The aim is to create a deep learning model using Keras and Tensorflow to detect whether a person is wearing a face mask or not. Wearing masks and social distancing are two most important precautions to take.  
I have used OpenCV to take a video as input and return a set of images that detect whether an individual is wearing a mask or not. This will be further updated to achieve a higher accuracy.  
The CNN Model built is explained with the help of a flow diagram, as shown below.  
![CNN Model](https://github.com/taarusshwd/Face-Mask-Identifier/blob/main/Model%20Screenshot/Model.JPG)

## Dataset
The dataset used in this project can be found [here](https://www.kaggle.com/prithwirajmitra/covid-face-mask-detection-dataset). 

## Technologies Used 
* python
* tensorflow
* keras
* OpenCV
* numpy 
* matplotlib

## Running The Project
1) Run the [jupyter notebook](https://github.com/taarusshwd/Face-Mask-Identifier/blob/main/COVID_Mask_Detection.ipynb) as is. 
2) In the last step of the notebook we save our CNN Model as 'model.h5'. Download this model and save it in the same directory as all the other files. 
3) Create an empty folder named 'input'. The frames will be extracted from the video stream and saved in this folder. Each of these images will then be analysed separately. 
4) Run 'mask.py'

### Star the repo if you found this useful! 

## Thank you!
