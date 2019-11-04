We did some exploratory ananlysis of the images and also pre-processing steps 

1. Training / Test images were rectangular with a lot of black picels at both the edges along the width . 
We cropped the images to remove the black pixels which would have contributed to noise 

![cropped file](https://github.com/ravindrabharathi/diabetic-retinopathy/blob/master/Screen%20Shot%202019-11-04%20at%208.25.43%20PM.png)

2. We plotted the 3 image channels separately to see which channel had more meaningful contextual information which could be used in training .
We found the green channel to be the one with richer contextual information 

![original image and 3 channels plotted side by side](https://github.com/ravindrabharathi/diabetic-retinopathy/blob/master/Screen%20Shot%202019-11-04%20at%208.24.54%20PM.png)

3. We cropped away black pixels at the edges and used the green channel for training 

![green channel](https://github.com/ravindrabharathi/diabetic-retinopathy/blob/master/Screen%20Shot%202019-11-04%20at%208.26.13%20PM.png)
