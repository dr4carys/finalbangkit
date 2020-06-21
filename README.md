# Final Project Bangkit - Beef and Pork Meat Identification

The increasing consumption of beef in Indonesia provides a loophole for certain parties to reap more profits by cheating. One way is to mix it with pork. Seeing the existing problems, therefore in this project, the we wants to identify beef and pork using CNN.

The model for this dataset is quite simple with only two classes, so we chose this dataset.

Files :

modelImprovedTest.ipynb -- Notebook to test the model(can open with google colab), this file uploaded to Google Cloud Service for the Web Application.

trainModel.ipynb -- Notebook to train the model(can open with google colab).

Datasets :

The datasets in this project using Google drive storage, so it is need to import the google drive service and mount the drive with the code below

  from google.colab import drive
  drive.mount('/content/gdrive')

This code will prompt the URL link, so we can get the authorization code. The datasets can be copied from the link below for the datasets below. 

  https://drive.google.com/folderview?id=1eBzuWx-HSno0FYWSFn-QmCTG6pw0QPGJ
