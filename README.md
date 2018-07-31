# Chinese-Word-Detection
In this task, the YOLO framework was applied on the Chinese Text in the Wild (CTW) dataset to detect the Chinese characters in the images. 

Reference Paper: https://arxiv.org/abs/1803.00085
Dataset: https://ctwdataset.github.io/downloads.html

The YOLO model trained using the training and validation set of the CTW dataset (available on the link for dataset) was used to evaluate the performance of the detection task.

System requirements:
The code is designed to run on a machine with a GPU and Ubuntu operating system. 

The detailed steps on installing the required packages and downloading the data is given at
https://github.com/yuantailing/ctw-baseline/blob/master/tutorial/1-basics.ipynb

The procedure to run the detection framework is explained at
https://github.com/yuantailing/ctw-baseline/blob/master/tutorial/3-detection.ipynb

Sample data and result files

sample data
This folder contains sample cropped images and the corresponding annotation files.

yolo-chinese_final.weights
These are the weights corresponding to the trained model

cates.json
This file contains information about the frequency of occurrence of each of the character categories. 

sample_detections.jsonl
This file contains the region proposals and detections along with the image ID for a few sample images.

