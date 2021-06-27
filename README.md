
# Project Title

Object Detection Model using Resnet50 

## Project Stack

- Using Transfer learning for achieving the multiclass classification model

- Initially classifying the images based on the training set which has been provided

- Added the dataset generator , which will capture the image from webcam and stores it in a 
  specified directory 

- Keeping the mimimum sample of 100 , and doing data augmentation on top of that

  
- Used flask framework and it can be deployed and run into amazon sagemaker and  heroku

- Have deployed on heroku , unfortunately heroku supports 500 mb for hosting 

- Data set generator contains two python files , which can be used as an enhancement for the project 


## File structure



```bash
Data set folder includes the training and test samples
static and templates folder contain css,html and the index.html 
modelresnet50.h5 is the saved model after the training and testing part is done
requirement.txt is being used for deployment in heroku
image classification is the main python file where the entire code is written
app.py is mapping everything 
```

Setup Backend

The git link [here](https://github.com/ajayvd/image-classifier.git)

Clone the repo for further check









