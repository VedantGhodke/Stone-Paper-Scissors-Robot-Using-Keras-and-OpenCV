# Stone-Paper-Scissors Robot Using Keras And OpenCV

This repository contains the code for the process where I tried to replicate a project by a Japanese scientist who made a machine with 100% accuracy in defeating humans in the game of Stone-Paper-Scissors. The project employs techniques of convolutional neural networks and deep computer vision.

I have used OpenCV for computer vision and Keras library for CNNS.
Link to the video tutorial referred: https://www.youtube.com/watch?v=ecSDKWkktOw

### Requirements:

1. Python 3.x
2. <a href="https://tensorflow.org">TensorFlow 2.0</a>
3. <a href="https://keras.io">Keras</a>
4. OpenCV 4.0 (for loading and resizing images)
5. h5py (for saving the trained model)
6. Pyttsx3


## Installation of the requirements:

1. Start your terminal or 'CMD' (depending on your OS)
  2. If you have a Nvidia GPU, then make sure you have the pre-requisites satisfied for TensorFlow GPU installation (Refer to the official site). Thereafter, use the following commmand:

    pip install -r requirements_gpu.txt

  3. In case you do not have a GPU, then use the following command:

    pip install -r requirements_cpu.txt

## Steps for creating your own training data:

Place the camera in a stable position. As soon as the camera starts, perform only one gesture at a time. The numbered images of this gesture will be stored in the root directory (you can modify the code and append the path to whichever directory you want the images to be stored in).

Gather data for all the classes in the similar way.

## Training your own classifier:

I used my own PC for training purposes, however, you can use AWS, Google Collab, Microsoft Azure etc.

For training:
<br> 
1) Modify the path of the stone, paper and scissors folder in 'hand_gesture_creating_model.py' <br>
2) Run 'hand_gesture_creating_model.py' <br>

After the model is trained you are ready to run it.

## Running the trained model:

1) Modify the path to the model file in 'predicting.py'<br>
2) Run 'predicting.py'

The program setup is complete. Test is out and enjoy!<br>


