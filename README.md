# Moodify
Emotion recognition and playing of custom build playlists of songs to lift up your mood.
# Table of Content :
1.[Description](#p1)

2.[Installations](#p2)

3.[Usage](#p3)

4.[Dataset](#p4)

<a id="p1"></a> 
# Description:

We are morons driven by our mood to make decisions whether to work or not regardless of it's necessity. So we built moodify to modify your mood as per the current occasion. Your facial expression is a consequence of your mood and therefore we shall detect your emotion and the play songs that shall rejuvinate your mood so that you could maximize your productivity.

<a id="p2"></a> 
# Installations:
-tensorflow

-keras

-imutils

-cv2

-numpy

<a id="p3"></a> 
# Usage:

The program will creat a window to display the scene capture by webcamera and a window representing the probabilities of detected emotions.

> Demo

python real_time_video.py

You can just use this with the provided pretrained model i have included in the path written in the code file, i have choosen this specificaly since it scores the best accuracy, feel free to choose any but in this case you have to run the later file train_emotion_classifier
> If you just want to run this demo, the following content can be skipped
- Train

- python train_emotion_classifier.py


<a id="p4"></a> 
# Dataset:

I have used [this](https://www.kaggle.com/c/3364/download-all) dataset

Download it and put the csv in fer2013/fer2013/

-fer2013 emotion classification test accuracy: 66%


# Credits
1) www.kaggle.com for dataset.
2) Raghav Vashisht and Milind for Linux support
3) https://github.com/omar178/Emotion-recognition.git



# Future Plans
1) Improving Accuracy
2) Converison to app
3) Auto Detecting Cameras
4) Smart homes

# Issues & Suggestions

If any issues and suggestions to me, you can create an [issue].https://github.com/Sahajpal/Moodify/issues.
Give me some stars if you like my work.
