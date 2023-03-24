# Detecting Potential Hazard due to Animals

## Problem Statement:
Are you tired of worrying about wild animals sneaking up on you? Well, imagine having a system that can not only detect the presence of animals but can also classify them as harmful or harmless. That's exactly what we achieved in this project! But we didn't stop there - we made sure to add an extra layer of protection by having the system alert the guard if it detects a potentially dangerous animal and the person in its proximity isn't moving. Now you can feel safe and secure even when you're out in the great outdoors!

## Pre-Requisites
**Softwares**:
1. Google Colab/Jupyter Notebook
2. GPUs(if available)

**Packages**:
1. matplotlib>=3.2.2
2. numpy>=1.18.5
3. opencv-python>=4.1.1
4. PyYAML>=5.3.1
5. scipy>=1.4.1
6. torch>=1.8.0  
7. torchvision>=0.9.1
8. tqdm>=4.64.0
9. pandas>=1.1.4
10. seaborn>=0.11.0
 
**NOTE**:
Python and pip are a must, using which the above packages can be installed during runtime.
 
**Dataset**:
Creation of custom dataset using web scraping and plotting boundary boxes using "Makesense.ai".
Also, specify the images and labels folder paths in the yaml file, which is later uploaded into the program folder.

## Training on custom dataset
1. Create a dataset folder
2. Use Makesense.ai to create a folder with labels for images from custom dataset
3. Define the paths to images and labels folder in .yaml file.
  
## References
Get the Pre-trained Model: https://github.com/ultralytics/yolov5
Make Sense.Ai: https://www.makesense.ai/
