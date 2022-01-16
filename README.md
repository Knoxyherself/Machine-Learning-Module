# Machine-Learning-Module

## Dataset
The dataset contains 22424 driver images in total downloaded from [kaggle](https://www.kaggle.com/c/state-farm-distracted-driver-detection/data). The dataset contains coloured images of size 640 x 480 pixels which are resized to 64 X 64 coloured images for training and testing pusposes.
Stratified splitting is used to split the dataset into 80:10 Training-Testing ratio. The training dataset is further split into 90:10 Training-Validation set.

The 10 classes to predict are:
- Safe driving 
- Texting(right hand) 
- Talking on the phone (right hand)
- Texting (left hand) 
- Talking on the phone (left hand)
- Operating the radio 
- Drinking 
- Reaching behind 
- Hair and makeup  
- Talking to passenger(s). 

<div align="center"><img src="plots/classes_imgs.jpg" height='200px'/></div>
