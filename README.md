
## Crosswalk detection 
A project to detect crosswalk for impaired people 

### Description  
Create a deep learning model to detect crosswalk for impaired people  
be able to preprocess data for deep learning
be able to train apply and evaluate Yolov4 model with real world data

### Installation
In order to run the program, install the libraries in the using this command `pip install requirements.txt`.   

 ### files in this repo:
 ### Usage
1. generate_annotation.ipynb file is used to create the label for each of the images according to the yolo format.
2. The static\images folder contains the images that are used for testing.
3. The yolo-files folder contains files required to train the and test the model
4. The templates folder contains all the html pages used in the application.
5. app.py is the main python program that runs the application.
 
 ### Project Workflow

 ### Step1: installation
 How to Use YOLO
I) Clone the Repository
git clone https://github.com/pjreddie/darknet
II) Compile the Source
We can directly compile the source using make. Just go to the directory where darknet is cloned and run the command:https://github.com/pjreddie/darknet

Full Weight
To get full weights for YOLO V3, download it from https://pjreddie.com/media/files/yolov3.weights
This is the weight trained on full 9000+ classes.
Test YOLO
everything is run using the darknet exeutable file. Suppose we have an image named test.jpeg, then we can try predicting the objects as:
./darknet detect yolov3-tiny.cfg yolov3-tiny.weights test.jpeg
