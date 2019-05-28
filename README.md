# GameOfDeepLearning
![alt text](https://datahack.analyticsvidhya.com/media/__sized__/contest_cover/god_2-thumbnail-1200x1200-90.jpg)

Problem Statement
Ship or vessel detection has a wide range of applications, in the areas of maritime safety,  fisheries management, marine pollution, defence and maritime security, protection from piracy, illegal migration, etc.

Keeping this in mind, a Governmental Maritime and Coastguard Agency is planning to deploy a computer vision based automated system to identify ship type only from the images taken by the survey boats. You have been hired as a consultant to build an efficient model for this project.

There are 5 classes of ships to be detected which are as follows:
![alt text](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2019/05/Screenshot-2019-05-23-at-2.54.19-PM.png)

Dataset Description
There are 6252 images in train and 2680 images in test data. The categories of ships and their corresponding codes in the dataset are as follows -
#'Cargo': 1, 
#'Military': 2, 
#'Carrier': 3, 
#'Cruise': 4, 
#'Tankers': 5}
There are three files provided to you, viz train.zip, test.csv and sample_submission.csv which have the following structure.

| Variable | Definition |
| --- | --- |
| `image` |Name of the image in the dataset (ID column) |
| `category` | Ship category code|

train.zip contains the images corresponding to both train and test set along with the true labels for train set images in train.csv
 
Evaluation Metric
The Evaluation metric is accuracy.

Python 3.6 libraries
fastai==1.0.50.post1
torch==1.0.1.post2
torchvision==0.2.2
pretrainedmodels
