# Assignment-8

## Problem Statement

![image](https://user-images.githubusercontent.com/120099863/219730140-cb7ad7a9-b949-435a-9eac-a76b06daa21e.png)
![image](https://user-images.githubusercontent.com/120099863/219730718-ef054212-68a8-4459-9509-ade96b9f07ed.png)

## Code Details

All classes & functions are defined in [link](https://github.com/MPGarg/main_repo). 

In notebook EVA8_Assigment_8.ipynb [link](EVA8_Assigment_8.ipynb) functions from the main repository are called. Model Custom_ResNet is trained for 24 Epochs on CIFAR10 dataset using OneCycle Scheduler with 96.60% training and 93.02% testing accuracy.

### Training Log

Last Few Epochs:

![image](https://user-images.githubusercontent.com/120099863/219870983-f54ddee5-9494-40cd-aac0-b92355f2399b.png)

### Accuracy & Loss Curve

![image](https://user-images.githubusercontent.com/120099863/219871001-bcafc73f-17de-4edc-95f1-6c1d467e21bf.png)

### Misclassified Images

![image](https://user-images.githubusercontent.com/120099863/219871024-3ccf044d-a85f-4fb5-855f-785292959c6a.png)

### GradCam Output

Misclassified:

![image](https://user-images.githubusercontent.com/120099863/219871058-7c16881b-b758-44e8-bade-1b1fdd81af1a.png)

## Conclusion

* One Cycle Policy helps in speeding of learning for the model
* Learning rate (maximum & minimum) can vary as per initialized weights of model and need to be determined for that particular model initialization
* Model was able to run quickly and achieve 93.02% testing accuracy in 24 epoch
* Model was overfitting and regularizations (Dropout & L2) are used to limit overfitting

