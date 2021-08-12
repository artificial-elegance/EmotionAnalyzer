# EmotionAnalyzer

The emotion analyzer uses the Facial Emotion Recognition (FER-2013) dataset, which is a publicly available dataset consisting of 48 x 48 greyscale images of faces. 
There are 7 labels altogether: 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral. The model is a convolutional neural network that runs over 50 epochs
and attempts to learn how to recognize each of these emotions. Given a face, the model is able to identify and recognize the emotion the user is showing at about 70% accuracy.
