# Emotion_detection_with_CNN

<img src='https://i.postimg.cc/VJhYmCWq/Screenshot-2024-09-01-at-7-54-04-PM.png' height="50%" width="50%" >

### Packages need to be installed
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow

### download FER2013 dataset
- from below link and put in data folder under your project directory
- https://www.kaggle.com/msambare/fer2013

### Train Emotion detector
- with all face expression images in the FER2013 Dataset
- command --> python TranEmotionDetector.py

It will take several hours depends on your processor. (On i7 processor with 16 GB RAM it took me around 4 hours)
after Training , you will find the trained model structure and weights are stored in your project directory.
emotion_model.json
emotion_model.h5

copy these two files create model folder in your project directory and paste it.

### Run your emotion detection test file
python TestEmotionDetector.py

### [Final Report](https://drive.google.com/file/d/1rLRY2d8dtNyB86rPf3D2sRHRhzrff6Dl/view?usp=sharing)

