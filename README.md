# Detecting Potential Hazard due to Animals

## Problem Statement:
The goal of this project is to create a system that can detect animals and classify them as harmful and harmless. It must also alert the guard of the animal's presence if the person in its proximity is not moving.

## Pre-Requisites
**Softwares**:
1.Google Colab/Jupyter Notebook
2.GPUs(if available)

**Packages**:
*1.matplotlib>=3.2.2
*2.numpy>=1.18.5
*3.opencv-python>=4.1.1
*4.PyYAML>=5.3.1
*5.scipy>=1.4.1
*6.torch>=1.8.0  
*7.torchvision>=0.9.1
*8.tqdm>=4.64.0
*9.pandas>=1.1.4
*10.seaborn>=0.11.0
 
**NOTE**:
Python and pip are a must, using which the above packages can be installed during runtime.
 
**Dataset**:
->Creation of custom dataset using web scraping and plotting boundary boxes using "makesense.ai".
->Also, specify the images and labels folder paths in the yaml file, which is later uploaded into the program folder.

## Training on custom dataset
1.Create a dataset folder
2.Use makesense.ai to create a folder with labels for images from custom dataset
3.Define the paths to images and labels folder in .yaml file.
  
## References
https://github.com/ultralytics/yolov5


