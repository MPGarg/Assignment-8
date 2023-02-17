# Assignment-8

## Problem Statement

![image](https://user-images.githubusercontent.com/120099863/219730140-cb7ad7a9-b949-435a-9eac-a76b06daa21e.png)
![image](https://user-images.githubusercontent.com/120099863/219730718-ef054212-68a8-4459-9509-ade96b9f07ed.png)

## Code Details

All classes & functions are defined in [link](https://github.com/MPGarg/main_repo). 

In notebook EVA8_Assigment_8.ipynb [link](EVA8_Assigment_8.ipynb) functions from the main repository are called. Model Custom_ResNet is trained for 24 Epochs on CIFAR10 dataset using OneCycle Scheduler with 96.50% training and 92.07% testing accuracy.

### Training Log

Last Few Epochs:

![image](https://user-images.githubusercontent.com/120099863/219732816-3474d8e7-3517-4aca-9246-ab4586c268bc.png)

### Accuracy & Loss Curve

![image](https://user-images.githubusercontent.com/120099863/219733104-0480ac9d-e151-4e73-83ed-50300d8d411c.png)

### Misclassified Images

![image](https://user-images.githubusercontent.com/120099863/219733446-4bbf9cb7-1439-475b-8721-ee7275c2d54e.png)

### GradCam Output

Misclassified:

![image](https://user-images.githubusercontent.com/120099863/219733768-e1908e4f-12ea-42c3-9bc2-c2ede5082258.png)

Correct Ones:

![image](https://user-images.githubusercontent.com/120099863/219734067-e6f2e678-5759-4915-a595-c5f6fc6cd879.png)

## Conclusion

* It can be seen via GradCam images what the network is seeing while predicting class
* For some images it is looking beyond the main object & detecting non-similar objects. Like predicting bird instead of deer
* In some images it is getting confused between cat & dog, deer & horse
* In some cases it is covering extra areas & predicting wrongly. For e.g. plane instead of horse

