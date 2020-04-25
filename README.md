# MSCS18022_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# Dataset and Model
Google Drive link for dataset:
https://drive.google.com/drive/u/1/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR

Google Drive link for Models:
https://drive.google.com/open?id=1-VKz7ier3b0MSfBV4HNJIUw3_7oYf46k

Import the above data and models in your "My Drive". You might need to change the PATH depending on where your data is stored.

# First Cell Block
The first cell block contains flags to control the flow of the program.

* test_str controls how validation or test data is faired against the training data.
* net_str controls which network you want to go with (VGG-16 or ResNet-18)
* task lets you choose which task needs to be performed (as provided in assignment)

# Results
The following results show the accuracy obtained by both networks in Infected and Normal X-rays of lungs

Class | VGG-16 | ResNet-18
------------ | ------------- | -------------
Infected | 80% | 90%
Normal | 93% | 89%
