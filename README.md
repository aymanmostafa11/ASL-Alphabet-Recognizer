# ASL-Alphabet-Recognizer
## Description

 A software able to recognize American Sign Language alphabet in real-time from web-cam using **openCV** and a **CNN Model**
 
## Features
• Support for 25 alphabet letters <font size=1, color='gray'>z is exculded due to it including motion gesture</font> <br>
• Support for 3 extra gestures (delete, space, nothing) <br>
• Display of real-time confidence in the prediction <br>
• Choosing a Region-Of-Interest in the live-cam feed to detect letters from

## Results
https://user-images.githubusercontent.com/60978780/154905962-247662b6-a8a5-4260-b684-6622f80bfb7a.mp4

## Data
The model was trained on the [ASL Alphabet](https://www.kaggle.com/grassknoted/asl-alphabet) dataset from [kaggle](kaggle.com)

## Usage
Download the [Driver Notebook](https://github.com/aymanmostafa11/ASL-Alphabet-Recognizer/blob/main/Sign%20Recognizer%20Driver%20Code.ipynb)<sup>1</sup> and [model weights](https://github.com/aymanmostafa11/ASL-Alphabet-Recognizer/blob/main/final_best_weights.h5)<br>
Run the cell codes and wait for the live-cam feed to start <br>
Select The ROI <br>
Start trying different gestures

<font size=2, color=gray><sup>1</sup> Any IPython notebook would work however it's recommended to use [Jupyter Notebook from Anaconda](https://www.anaconda.com/products/individual)
</font>
