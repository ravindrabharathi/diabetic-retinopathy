# Detection of Diabetic Retinopathy using Deep Learning 

We will use Convolutional Neural Networks to classify if an image of Retina shows signs of Diabetic Retinopathy 

Diabetic Retinopathy afflicts a large poulation and mostly becomes severe , even leading to blindness, due to lack of access to easily accessible detection tools in rural areas. By training a deep learning model to detect Retinopathy from images , we could make a mobile application available for a primary health care center or an NGO who can then use it do preliminary screening once they have the means to capture retinal images. 

For initial exploration we will use a Dataset from https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid

This dataset contains 413 Training images and 103 Test images .The GroundTruth labels are present for Retinopathy and macular edema risk. Right now we will focus on retinopathy classification( 5 classes) . Once we have formed a strategy , we will switch to bigger datasets which will help us train a better performing model 


We will use Keras with tensorflow for this . In the next stages we could use this library https://github.com/ravindrabharathi/tf_utils. This library is a work in progress but it already gives us the ability to build an input data pipeline using TfRecords, tf.Data Datasets , augmentation strategies like cutout , random-pad-crop, the ability to plot misclassified images and also ability to plot confusion matrix 

**Link to Notebook for Preliminary analysis :** 

https://github.com/ravindrabharathi/diabetic-retinopathy/blob/master/Diabetic_Retinopathy.ipynb
