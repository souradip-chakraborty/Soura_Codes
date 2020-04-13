### An attempt- Detection of COVID-19 presence from Chest X-ray scans using CNN & Class Activation Maps

![alt text](https://github.com/souradip-chakraborty/Soura_Codes/blob/master/Covid-19_Image_Analysis/Grad_cam_activations.png)


In a very recent paper ‘A deep learning algorithm using CT images to screen for Corona Virus Disease (COVID-19)’ published by Shuai Wang et. al they have used Deep Learning in extracting COVID-19’s graphical features from Computerized Tomography (CT) scans (images) in order to provide a clinical diagnosis ahead of the pathogenic test, thus saving critical time for disease control.

The study used transfer learning with an Inception Convolutional Neural Network (CNN) on 1,119 CT scans. The internal and external validation accuracy of the model was recorded at 89.5% and 79.3%, respectively.
In my experiment, I have performed a similar analysis but on Chest X-ray images and the major reason is that getting CXRs is more accessible for people than getting CT scans especially in rural and isolated areas. There will also be more potential data available.

Dr.Joseph Paul Cohen (Postdoctoral Fellow at the University of Montreal), recently open-sourced a database containing chest X-ray images of patients suffering from the COVID-19 disease. The dataset used is an open-source dataset which consists of COVID-19 images from publicly available research, as well as lung images with different pneumonia-causing diseases such as SARS, Streptococcus, and Pneumocystis.
So, the dataset consists of COVID-19 X-ray scan images and also the angle when the scan is taken. It turns out that the most frequently used view is the Posteroanterior view and I have considered the COVID-19 PA view X-ray scans for my analysis.
Now, I have also used the Kaggle’s Chest X-ray competitions dataset to extract X-rays of healthy patients and patients having pneumonia and have sampled 100 images of each class to have a balance with the COVID-19 available image. (Though I will work on this part and improve the approach

Please refer to my blog [An attempt- Detection of COVID-19 presence from Chest X-ray scans using CNN & Class Activation Maps](https://towardsdatascience.com/detection-of-covid-19-presence-from-chest-x-ray-scans-using-cnn-class-activation-maps-c1ab0d7c294b) for further details.


