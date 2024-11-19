Melanoma Detection using Custom Convolutional Neural Network   
Building a multiclass classification model to detect melanoma from skin images.

Table of Contents 

**General Information**
This project aims to build a custom convolutional neural network in TensorFlow to detect melanoma, a deadly type of skin cancer.    
Background:  Manual examination of skin images by dermatologists is time-consuming. Automated detection can reduce manual effort.     
Business Problem:  Develop an accurate multiclass classification model to detect melanoma from skin images.     
Dataset:  2357 images from the International Skin Imaging Collaboration (ISIC), including 9 classes: Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, and Vascular lesion.

Conclusions    
Conclusion 1:    
1.The training accuracy steadily improves, nearing 1.0, while the training loss reduces significantly, indicating the model is learning well on the training data.

2. Validation accuracy follows the trend of training accuracy but fluctuates after epoch 10, suggesting overfitting might begin. The validation loss also shows spikes after epoch 10.

Conclusion 2:  
1.Training Performance: Training accuracy improves  nearing 0.8, while training loss decreases steadily, shows model is learning

2.: Validation accuracy tracks closely with training accuracy, with minor fluctuations, and validation loss decreases alongside training loss, indicating no severe overfitting.
   
Conclusion 3:   With data augmentation added, show that the validation loss is still rising and fluctuating, while validation accuracy remains relatively flat. 
This indicates that although augmentation is adding some variety, it hasn’t fully resolved the overfitting or the model's inability to generalize well on validation data.

1.Training Performance: Training accuracy rapidly improves and stabilizes above 0.9, while training loss significantly decreases, indicating strong performance on training data.

2.Validation Performance: Validation accuracy closely follows training accuracy, stabilizing slightly below 0.9. Validation loss decreases but exhibits spikes toward the later epochs, suggesting some noise or mild overfitting.


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
