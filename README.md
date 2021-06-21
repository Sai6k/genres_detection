# genres_detection
The objective of this project is to build a Deep Learning Model for detecting Genres of Music. In order to build this model, I have used Python.

About the data:
The provided data consists of 1000 music files divided in to 10 different Genres of 100 each. The music files are in “.au” format with 30 sec each. 

Procedure:

Step 1: Creating Spectrogram images in JPEG format for each Audio file. Below are some examples: 

Figure 1: Image of classical genre audio file:
![classical 00016](https://user-images.githubusercontent.com/82253441/122783236-00e4f400-d2cf-11eb-979e-89229c5140b1.jpg)

Figure 2: Image of Jazz genre audio file:
![jazz 00003](https://user-images.githubusercontent.com/82253441/122783359-207c1c80-d2cf-11eb-8a30-fa582f81056e.jpg)

Figure 3: Image of pop genre audio file:
![pop 00013](https://user-images.githubusercontent.com/82253441/122783525-45708f80-d2cf-11eb-96c6-d53e264350f3.jpg)

Step 2: Segregating the images to Train and Validation data sets.

Step 3: Building a 2D Convolution Neural Network model.

![model](https://user-images.githubusercontent.com/82253441/122783642-5d481380-d2cf-11eb-9b8c-4f73a600d8d0.png)
