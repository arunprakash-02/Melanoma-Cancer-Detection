Melanoma Detection using Custom Convolutional Neural Network   
Building a multiclass classification model to detect melanoma from skin images.

Table of Contents 
General Information
This project aims to build a custom convolutional neural network in TensorFlow to detect melanoma, a deadly type of skin cancer.    
Background:  Manual examination of skin images by dermatologists is time-consuming. Automated detection can reduce manual effort.     
Business Problem:  Develop an accurate multiclass classification model to detect melanoma from skin images.     
Dataset:  2357 images from the International Skin Imaging Collaboration (ISIC), including 9 classes: Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, and Vascular lesion.

Conclusions    
Conclusion 1:    
The training accuracy continues to improve steadily, reaching close to 0.7, while the validation accuracy plateaus around 0.5–0.6 and fluctuates.
This gap between training and validation accuracy indicates overfitting; the model is performing well on the training data but not generalizing as well on the validation data.

Conclusion 2:  
Training accuracy improves steadily over epochs. 
Validation accuracy shows fluctuations but generally follows the trend of training accuracy. 
This suggests the model is learning but might be slightly overfitting, as the validation accuracy is less stable. 
Training loss decreases consistently, indicating proper optimization. Validation loss also decreases but shows fluctuations, suggesting potential overfitting    
Conclusion 3:   With data augmentation added, show that the validation loss is still rising and fluctuating, while validation accuracy remains relatively flat. 
This indicates that although augmentation is adding some variety, it hasn’t fully resolved the overfitting or the model's inability to generalize well on validation data.

Technologies Used  

TensorFlow - version 2.x
Python - version 3.x
Google Colab (GPU runtime)
Augmentor library - version 0.2.8

Acknowledgements  
This project was inspired by the need for automated melanoma detection.
References: International Skin Imaging Collaboration (ISIC).
This project was based on TensorFlow tutorials.

Contact
Created by [@prakash-arun02] - feel free to contact me!
