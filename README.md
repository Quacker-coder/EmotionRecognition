# Real-Time Emotion Recognition using DL


## Description
This project attempts to identify 5 emotions namely neutral, sad, happy, surprised and anger in real-time using Mediapipe.


## Visuals
Uploading soon...

## Metadata

### 1. csv
Contains csv files with emotion labels and 52 blendshape scores as features. Use the files containing "Only_5_emotions" as it is tailored for the above mentioned 5 emotions
### 2. model
Contains different models
### 3. plots
Graphs and visuals
### 4. Files 
1. _**face_landmarker.task**_ : Essential for Mediapipe to run
2. _**PrepareDataset.py**_ : This script extracts blendshape scores from images and saves a csv files
3. _**Real-Time Emotion Recognition.py**_ : This script contains real-time recogition using webcam (main file)
4. _**RandomForest.py**_ : Random Forest implementation
5. _**TabNet.py**_ : Neural Network model implementation to train the data obtained from _PrepareDataset.py_

## How to run

### Pre-requites
1. Add images to project folder named _"train_set"_. (Project uses AffectNet dataset and its project structure)
2. Add the above _**Files**_

### Install Packages
mediapipe, opencv, pytorch-tabnet, cv2, numpy, pandas

### Run
**Note** : Run directly step 3 if you just want the demo
1. Run **_PrepareDataset.py_** to get your csv file
2. Run **_TabNet.py_** to train your model (input : step 1)
3. Run **_Real-Time Emotion Recognition.py_**

## Usage
NA

## Support
email: jay-jagadeeshwar.puppala@tu-ilmenau.de


## Authors and acknowledgment
1. Jay Puppala (Author)
2. Qais Yousef M.Sc.

## License
NA

