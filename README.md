For this project, we first explored the world of object detection algorithms. This branch or computer vision is fastly advancing, thanks to new Deep Learning techniques and algorithms. We discovered that due to its fast inference time and high accuracy, the most used algorithm is exactly the YOLO one. 
However, from 2015 more than 15 official  versions of YOLO have been released, proving that the object detection field is widely researched and investigated all over the world.

We picked three very different training Datasets that we found interesting:

1.	Thermal Infrared UAV Images: 
Dataset of thermal images taken in a urban setting, created for detecting people, bicycles and vehicles

2.	Satellite Vehicles Images (Sky-Fusion):
Dataset of Satellite and aerial images containing land vehicles, aircrafts and boats

3.	Tree Urban Detection (GreenDetection):
Dataset of Satellite and aerial images for trees and palms recognition.

Code Structure-
All Jupyter Notebooks have the same structure, that is here summarized:
1.	Imports from Libraries:
Run all  imports that are useful in the scripts, including installing Supergradients.
2.	Google Drive Mounting:
Used to quickly retrieve datasets and pre-trained models from this Google Drive Folder
3.	Preparing Dataset:
Defining hyperparameters and dataset folders before training
4.	Training Model:
Train the selected YOLO-NAS model (S, M, L)
5.	Saving Trained Model:
Export to Google Drive a trained model for further importing it
6.	Importing pre-trained model:
Import a pre-trained model that is ready for testing.
7.	Image Testing:
using model.predict(...), takes a folder with images as input and produces images with bounding boxes as output
8.	Video Testing;
using model.predict(...), takes a video as input and produces a video with bounding boxes as output
9.	Auxiliary Functions:
Functions not strictly related to the Object detection task.

To open the whole folder containing also videos and trained models follow this link: https://drive.google.com/drive/folders/1dKbOLQhLvC8tUNnMN8Tw8fz_yStear8a?usp=drive_link

