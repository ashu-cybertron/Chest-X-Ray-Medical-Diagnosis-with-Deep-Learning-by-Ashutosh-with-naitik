# Chest-X-Ray-Medical-Diagnosis-with-Deep-Learning
Chest X Ray Medical Diagnosis with Deep Learning

Gist About the Project:  This project “Disease detection with Computer Vision” AI is transforming the practice of medicine. It’s helping doctors diagnose patients more accurately, make predictions about patients’ future health, and recommend better treatments. In this project we have created convolutional neural network image classification and segmentation models to make diagnoses of lung and the diagnoses our model can detect are: 
1.	Cardiomegaly
2.	Emphysema
3.	Effusion
4.	Hernia
5.	Infiltration
6.	Mass
7.	Nodule
8.	Atelectasis
9.	Pneumothorax
10.	Pleural Thickening
11.	Pneumonia
12.	Fibrosis
13.	Edema
14.	Consolidation 
In today’s world of automation we have to find the ways which can help doctors in their work, checking if the patient is diagnosed with one of the 14 diseases mentioned above, this approach is reliable, quick, works 24/7 without getting stressed. The best part about this model is that it not only detects if the person has been diagnosed with the disease or not, but it maps it out to where that particular disease is, and it even detects that if the person is diagnosed with more than one disease. We have used the dataset from NIH Medical Centre and the dataset itself is 40GB+ before doing data augmentation. Data Leakage has been checked to prevent optimistic accuracy levels. Training the whole model took a few hours on a GPU-equipped machine, so we have already provided the pretrained model, which we trained on a small dataset taken from NIH. 

Technologies Used: I’ve used Machine Learning Linear Regression Algorithm as the data contains two columns namely: Years of Experience and Salary. Using the historical data we can predict the salary of an employee.

Technologies Used- 
⮚	Deep learning:- For better accuracy of the model, because accuracy is the most important thing in Medical.
⮚	DenseNet:- We used DenseNet121 which we have used as a pre-trained model, and then we have added two layers on top of it. 
⮚	Pandas:- To read the csv file.
⮚	Keras:- Keras is a high level API built on TensorFlow (and can be used on top of Theano too). It is more user-friendly and easy to use as compared to TF.
⮚	ROC Curve And AUROC:- For model evaluation.
⮚	GradCAM:- To visualize where the model detects the diagnoses.
⮚	We have even used numpy, seaborn, matplotlib.pyplot, ImageDataGenerator, Dense, GlobalAveragePooling2D

Conclusion:  We have built a state of the art chest X-Ray classifier using Keras, which will help doctors in detecting if the patient has been diagnosed by 14 different lung diseases.

Future Scope: Yes, it has a future scope as we can train the model with different dataset to detect different diseases, like COVID-19 and a GUI version can be made or even a Mobile App can be made.  With the world experiencing different diseases, which are unheard of before, this model can be trained and tuned to detect them too.


For the dataset, head over to this site which is of nih and the dataset is of over 40GB in size, so I couldn't upload it to GitHub, and as soon as you download all of the dataset and unzip it to the folder in this repository named images-small, in the nih folder.
The link for the dataset: https://nihcc.app.box.com/v/ChestXray-NIHCC

The other option is that run the batch-0donload-zips.py file, this python script will download all of the deataset, so you don't need to individually download each and every zip file.
Remember that the files will be downloaded to the default location C:\Users\(Username), so make sure you have around 40GB free disk space.
