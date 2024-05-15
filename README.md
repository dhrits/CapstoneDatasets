
# Instructions
Please install all dependencies spefied in `requirements.txt` before moving forward. Datatset download instructions are included in the jupyter notebook `Capstone Datasets Summary.ipynb`.

# Project Summary

This repository aims to satisfy the capstone data gathering project. Due to the size of the datasets, I have not included them in the repo. However I have uploaded them all to [this S3 bucket](https://dsagar-springboard-capstone-data.s3.us-east-2.amazonaws.com/data.tar.gz). **Please respect the license of the underlying datasets if downloading them. See homepage of each dataset below for license.** 

Tentatively, my project aims to build a web/mobile app which allows visual detection classification of dog breeds using deep neural networks. To this end, the datasets must consist of images of various dog breeds and corresponding breed labels. As per the requirements of this mini-project, three datasets are described below. 

# Stanford Dogs Dataset
The [stanford dogs dataset consists](http://vision.stanford.edu/aditya86/ImageNetDogs/) of **20,580 images of 120 different dog breeds**. The dataset consists of both bounding boxes (for object detection) as well as dog breed labels. Based on discussions and leaderboards at paperswithcode, this dataset has become an important benchmark for dog breed classification.

 Tsinghua Dogs Dataset

[Tsinghua University Dogs Dataset](https://cg.cs.tsinghua.edu.cn/ThuDogs/) is another important benchmark dataset for dogbreed classification and detection. This dataset consists of **70428 images of 130 different dog breeds**. Each dog breed has anywhere from 200 to 7449 images represented in this dataset and the sample sizes are roughly representative of frequencies of dog breeds found in China. 

As is the case with Stanford Dogs dataset, this dataset also consists of class labels as well as bounding boxes. 

# Kaggle Dog Breeds Classification Dataset

This is yet another dataset for **20,000 images of 120 different breeds.**. However, a drawback of this dataset is that it only consists of labels of dog breeds and not bounding boxes. However, on the plus side, the data is pre-cropped so each image represents mostly only the dog. 

Since this dataset is associated with a Kaggle competition, downloading it programmatically requires a Kaggle account. Please follow instructions [here](https://www.kaggle.com/docs/api) on how to use the Kaggle API. 