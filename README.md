# Skin-Lesion-CNN
Skin cancer is one of the most common cancers worldwide. 
Both melanoma and non-melanoma cancers are highly curable if the cancer is diagnosed and treated in its early stage to reduce their development and spread.
Deep neural architectures have shown outstanding results in a variety of disciplines, including dermatology.
In this project we develop a deep learning architecture trying to solve the classification problem. 
The proposed method consists in an image processing-based approach that takes the digital image of the disease skin area and then 
uses image analysis in order to identify the type of disease.
First, we tried to define some architectures from scratch, to propose our own custom architecture for solving the problem. Afterwards, since it is quite difficult to develop powerful networks able to generalize effectively, we tried to reach better performances by exploiting transfer learning. 
So, different pre-trained networks were used to address this problem in both feature extraction and fine-tuning. 
The pre-trained networks that we used are the following:
- ResNet
- EfficientNet
- MobileNet
- InceptionV3

Finally, an esamble approach was used in order to increese the classification performances.
