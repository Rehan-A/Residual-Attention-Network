# Residual-Attention-Network
Light Intensity Adjustment and Severity Estimation for the Generic Disease of Tomato Plants

For disease classification Convolutional Neural Network (CNN) is being used which lets you
know what kind of disease has affected the crop. In this paper we have worked on self attention networks
to calculate the severity of the disease on the leaf . Self Attention Network introduced in the architecture
lets the model learn the feature more efficiently and focus more on the affected region of the leaf. The
model was trained and tested on the standard dataset (Plant Village) . The core processes comprises
image capturing, image processing and testing on Self Attention Convolutional Neural Network
architecture.
To refer to the complete research paper refer to DOI: 10.48175/IJARSCT-1147


File Description:
train_cifar10.py : Is the basic structure where the import statements are added and the model is deployed.

models/__init__.py : File is used for importing all the functions from the models/models.py file so that it can be used in another files as well.

models/models.py : This file contains multiple models. 

models/blocks.py : This includes the external functions which are common to all the models . 
