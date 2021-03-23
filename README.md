## Phase Based video Motion Magnification
### Authors: CIOCARLAN Alina, KLEIMAN Ilan, LEMERLE Gaspard, SANTANNA Louis

This project is about optical flow : Main goal is implementation of optical flow computation based on flownet within fine-tuning.
This project has been implemented in python, our activities were based on the paper accessible [here](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Dosovitskiy_FlowNet_Learning_Optical_ICCV_2015_paper.pdf "here").

All the python scripts and files related to our work are located in [this drive](https://drive.google.com/drive/folders/1s9p2EZWLD_2DntLngYlr0w6E2-8pVQE6?usp=sharing "this drive").

#### Our main function is located in the notebook named FlowNet_fine_tuning.ipynb. This notebook contains functions for fine-tuning the FlowNetS architecture, it manages : 
* Fine-tuning the FlowNetS
* Using pretained weights for our neural network from 'flownets_EPE1.951.pth.tar' given by Clément Pinard
* Training and validating our network

#### All the functions involved in the notebook requided the following functions : 
* The file util.py contains utilities such as coloring flow, computing and storing average and the current values.
* The file main.py contains the steps for loading, training and validating the dataset.
* The file multiscaleloss.py contains functions dedicated to compute different type of loss in order to have performance estimation. 

#### Our main folder project contains differents subfolders : here are listed the main ones are : 
* datasets : This folder contains python codes for data generations for network training purposes.
* sintel_ds : Contains images related to sintel dataset.
* models : Python codes for different flownet architectures.
* Pretrained : Trained neural network weights.
* Présentations : This folder contains our slides and related files for the presentations.
 

### Thanks !
