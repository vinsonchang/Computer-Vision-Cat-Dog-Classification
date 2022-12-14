# Computer-Vision-Cat-Dog-Classification
Create an algorithm to distinguish dogs from cats

Dataset can be downloaded from here: https://www.kaggle.com/competitions/dogs-vs-cats/data

Below are samples from training dataset

![image](https://user-images.githubusercontent.com/98190799/200108413-6bb1c239-1417-47ac-8eca-55c6fa03caf9.png)

The training archive contains 25,000 images of dogs and cats. Train your algorithm on these files and predict the labels for test1.zip (1 = dog, 0 = cat).

# Model Exploration
I have tried a baseline model (3 layers ConvNet) which gave us 67% accuracy in the test dataset. Moreover, I have utilized the transfer learning model Resnet18 with Feature Extraction(96% accuracy), and Resnet18 with fine tuning(99% accuracy). 
