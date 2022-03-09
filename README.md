# Object-Detection--crop-disease-detection

Convolutional Neural Network is very efficient in terms of processing a large amount of data in very less time. We are using the CNN model along with object detection
techniques for the processing of the image data of leaf, stem, root, fruits etc. parts of the crop which are infected from diseases and pest. Using deep learning approach, object
detection techniques with convolutional neural networks, the objectives can be summarized as:

- To detect the crop disease from the images of all parts of the infected crop.
  - The images in the dataset will be laboratory condition as well as field condition.
  - The images with heterogeneous background will also be considered.
• Detecting location of disease or pest.
• Detection of the various kinds of pests.
• To detect the severity of disease.
• To provide performance comparison of various pre-trained CNN models along with object detection models to detect crop disease based on training-testing ratio, batch size and epochs.

This research work basically uses the transfer learning approach for the detection of disease and pests of the crop. For this work various pre-trained networks are used. 
So,the scope of the work includes,
• Detecting different diseases and/or pest in initially on one crop and can be extended to various types of crops.
• Comparing various performances of pre-trained networks like Inception, ResNet, MobileNet etc.
• Comparing different object detection methods such as Faster RCNN, SSD and RFCN.
• Comparison of results by taking different parameters of fine tuning the models like epochs, learning rate, batch size.

![image](https://user-images.githubusercontent.com/85123149/157534216-534bc107-f737-4b20-aa00-cb3e403837fe.png)

The following shows workflow:


![image](https://user-images.githubusercontent.com/85123149/157534344-3f3c07f2-b9bc-41a3-a2d2-c11c42ab4d09.png)

The proposed methodology is implemented on various types of object detection models using infected different parts of the crop and pests along with the severity. Comparison of object detection algorithms with different types of CNNs is made and as results are shown that currently the best suitable model is Faster R-CNN with ResNet101 which has highest Average Precision with IoU=0.50 (0.907) and execution time is also not much (5048s). For the future work, various crop types can be added in the dataset to get more generalized dataset and to get more accurate model. Also, more object detection algorithms will be tested on dataset like Mask R-CNN, YOLO.

Published Paper: https://ieeexplore.ieee.org/document/8869510
