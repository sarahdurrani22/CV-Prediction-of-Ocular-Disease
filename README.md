# Computer Vision Prediction of Ocular Disease from Fundal Images
This project is a part of the AAI-501 course in the Applied Artificial Intelligence Program at the
University of San Diego (USD).

### Project Status: Active
## Installation
You should add an instruction how this project to be used, installed, run, edited in others’
machine.


## Project Intro/Objective
The main purpose of this project is to take a given fundal image and classify it as appearing 
healthy or indicative of diabetes, glaucoma, cataracts, age-related macular degeneration, 
hypertension, pathological myopia. This team will explore multiple approaches to determine which 
solution provides the best classification results. These approaches may include Convoluted Neural 
Networks (CNN), Residual Neural Networks (RNN), Support Vector Machines, YOLO, ResNet, and/or 
others. The solution must take a fundal image of a patient, estimate the category it would fall 
into and give a measure of the agent’s confidence in the classification. While accuracy and 
precision are paramount metrics to base performance on, the speed/memory required to perform the 
calculations will be considered. 

### Contributors
Elan Wilkinson, Benjamin Hopwood, Sarah Durrani

## Methods Used
- Computer Vision
- Machine Learning
- Deep Learning
- Classification

## Technologies
A few examples are:
- Python
- Tensorflow, Keras

## Project Description
This project uses the dataset found at 
https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k
comprised of fundal images of 5,000 patients from medical centers in China.
Annotations were labeled by trained human readers with the labels:
- Normal (N),
- Diabetes (D),
- Glaucoma (G),
- Cataract (C),
- Age related Macular Degeneration (A),
- Hypertension (H),
- Pathological Myopia (M),
- Other diseases/abnormalities (O)
with images of both the left and right fundus, as well as the patient sex and age.

This project will demonstrate the feasibility of AI-enabled Ocular Disease Diagnosis by training on the dataset.

### Acknowledgments
Our thanks and appreciation go to our professor Andrew Van Benschoten
