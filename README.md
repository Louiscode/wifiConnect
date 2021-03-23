## Phase Based video Motion Magnification
Authors: Alina CIOCARLAN and Louis SANT'ANNA
This project is about motion magnification : Main goal is to amplify some kind of small motions not visible by human retina.
This project has been implemented in python, our activities were based on the paper accessible [here](http://people.csail.mit.edu/nwadhwa/phase-video/ "here").

All the python scripts and files related to our work are located in [this drive folder ](https://drive.google.com/drive/folders/1AzdviIRpevFtiNRG4431bvwi1OJhvI-U?usp=sharing "this drive folder ")

#### Our main functions are organized in the notebook named is in phaseAmplify.ipynb. This notebook contains functions for phase amplifications, it manages : 
* Filtering tests within different types of pyramid
* Amplification and attenuation with different factors 
* Noise handling with different types of noising video frames

#### All the functions involved in the notebook requided the following functions : 
* The file util.py utilities such as converting video formats, loading and writing video frames
* The file filter_tools.py contains the filtering algorithms.
* The file pyramid_tools contains functions dedicated to work with the steerable pyramid.

#### Our main folder project contains 2 subfolders : tests and presentations 
* Tests : This folder contains the results of the videos used for our processing purposes (The original videos used are : baby.avi, woman.avi, Tree-44374.mp4, and those are located in the main folder)
* Presentations : This folder contains our slides and related files for the presentations

### Thanks !
