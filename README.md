# SportsProductsMulti-ClassClassification

## Definition
In previous people used  traditional ways to classify products then they used some basic computers software to manage it but in case of using images as products description we need something different to use computer to solve this problem, our thoughts turns quickly to computer vision or machine learning techniques to help us to work with image classification. So, in our project we will work on deep learning project to help us in Sports products multi-class classification problem.
## Dataset
Using webscrapping techniques to scrape the images after that segmenting the scrapped images into 11 classes.
<br/>
<br/>
!['DataSet_img'](Images/TSNE.png)
<br/>
<br/>
- Finally, 11 classes were split into training, validation, and testing data sets of 440, 55, and 55 images, respectively.
- By using data augmentation on these photos, it is possible to increase the size of the train set by modifying the original data through rotation (by 90 degrees), shearing (by 0.5), zooming (by 0.2), and horizontal flipping as shown in Figure III (4). Making the model learn on all sides of the images will make learning and predicting easier and prevent overfitting.
  ## METHODS

### First Model (ResNet):
!['resnet'](Images/ResNetarch.png)

### Second Model (VGGModel):
!['VGG'](Images/VGGModel.jpg)

### Third Model (AlexNet):
!['AlexNet'](Images/AlexNet.png)

## EVALUATION
!['Sports Products'](Images/EvalutionCV.jpg)

## Champion model
We have found that the tuned ResNet152 model gave us 
89% accuracy on out test dataset.

## Deployment 
- Using HTML , CSS and JavaScript for the design.
- Using  a flask library to connect our model with the user interface
- This GIF IMG depicts the website that displays the champion model's results 
![Deployment](Images/Deployment.gif)


## CONCLUSION
we found that there are a lot of options to play with and different things to try in the transfer learning architectures, after we got our champion model which is ResNet152, we conclude that this is reasonable thing because the ResNet152 architecture is a big and complex architecture that contains different layers, also we learnt a lot of new stuff in this project like deployment techniques and we learned also different visualization and tuning techniques, the table in below show the different models test accuracies that we have obtained.







